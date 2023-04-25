# *DR-Worker*
A High Performance Cryptocurrency Worker


## Supported algorithms
* ironfish (Iron Fish)

## Developer fee
| Algorithm   | Fee  |
| ----------- | -----|
| ironfish    | 1.0% |

## Features
* Available on Linux and Windows
* Terminal user interface

## Usage
```
  -a, --algorithm <ALGORITHM>
          Select the algorithm

          Currently supported:
          ironfish    (IRON)

  -u, --url <URL>
          Set the pool URL

          Format:
          <working protocol>+<transport protocol>://<pool>:<port>

          Working protocol:    stratum
          Transport protocols: tcp, ssl

  -w, --worker <WORKER>
          Sets the worker name

  -d, --devices <D1,D2,...>
          Set GPU devices for working

          Must be a comma-separated list of device indices. If not specified,
          all detected devices will be used. Devices are ordered by their
          PCI bus addresses. First GPU has index of 0.
          To display all available devices, use --list-devices.

          Example:
          -d 0,2,4,5

      --list-devices
          List available mining devices and exit

  -l, --log-file <LOG_FILE>
          Enable logging output of the worker to the specified log file

  -h, --help
          Print help information (use `-h` for a summary)

  -V, --version
          Print version information
```
