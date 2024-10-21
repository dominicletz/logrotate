# LogRotator

Simple log rotation script that rotates and compresses the log file (using zstd, xz, or gzip by default) and deletes the original.

It is created to be used with [svscan](https://cr.yp.to/daemontools/svscan.html). Put the `run` file into the `log` directory of your service.

Requires elixir to be installed.