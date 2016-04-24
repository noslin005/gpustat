`gpustat`
=========

Just *less* than nvidia-smi?

Usage
-----

`$ gpustat`

A possible output:

```
[0] GeForce GTX TITAN X | 59'C,   0 % | Mem:   109 MiB / 12287 MiB
[1] GeForce GTX TITAN X | 56'C,   0 % | Mem:    23 MiB / 12287 MiB
[2] GeForce GTX TITAN X | 86'C,  93 % | Mem: 11134 MiB / 12287 MiB
```

Quick Installation
------------------

Just download [the script][script_gitio] into somewhere in `PATH`, e.g. `~/.local/bin/`:

```
sudo curl https://git.io/gpustat -O /usr/local/bin/gpustat
sudo chmod +x /usr/local/bin/gpustat
```

[script_gitio]: https://git.io/gpustat

Status and TODOs
----------------

This script is currently in infancy, so please be patient or give me a PR :-)

* [x] the list of Nvidia GPUs, along with temperature/utilization/memory statistics
* [ ] the list of running processes: PIDs and user process
* [ ] more configurable options
* [ ] sensible installation guide
