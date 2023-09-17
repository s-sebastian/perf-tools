# perf-tools

A miscellaneous collection of in-development and unsupported `perf` scripts.

## Note

`perf` is a core Linux tracing tool included in the kernel source. To use its scripting capabilities, it must be built with scripting enabled.

## Usage

Install `perf`:

```
$ sudo dnf install perf
```

Clone the repository:

```
$ git clone --depth 1 git@github.com:s-sebastian/perf-tools.git
```

Copy the scripts to `PERF_EXEC_PATH` path:

```
$ export PERF_EXEC_PATH=/usr/libexec/perf-core
$ sudo cp -a ~/perf-tools/scripts/* "${PERF_EXEC_PATH}/scripts/"
```

Refer to [perf-script(1)](https://www.man7.org/linux/man-pages/man1/perf-script.1.html) for further usage details.
