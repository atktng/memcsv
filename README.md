# memcsv

Monitor the following physical memory usage (KB) of the target process and output in csv format.

- USS: Unique Set Size
- PSS: Proportional Set Size
- RSS: Resident Set Size

## Installation

Download [memcsv](memcsv) and add to your `$PATH` or run directly.

## Usage

```sh
memcsv -h
```

For example, monitor the memory usage of a process with pid 10000 at 1 second intervals, run followings.

```sh
memcsv 10000 -i 1
Timestamp,USS,PSS,RSS
2021-01-01T05:09:15Z,3086576,3086646,3086720
2021-01-01T05:09:16Z,3086576,3086646,3086720
2021-01-01T05:09:17Z,3086576,3086646,3086720
...
```

