# Linux diagnostics

- [System overview](#system-overview)
- [CPU tools](#cpu)
- [Disk tools](#disk)
- [Memory tools](#memory)
- [Network tools](#network)

## System overview

### uname
### lspci
### lshw
### lsmod
### lsusb
### glances, top, htop, iotop, atop
### dmesg
### strace
### ps
### pstree
### sysctl -a

## CPU

### lscpu
### gprof
### /proc/cpuinfo

## Disk

### iostat
### lsof
### fuser
### hdparm
### smartctl
### dstat
### stat

## Memory

### vmstat
### free -m
### /proc/meminfo

## Network

### ifconfig
### dig
### ping
### netstat
### tracepath
### ip
### route
### host
### lsof
### ss
### iptables
### ngrep
### iptraf
### conntrack

See http://xmodulo.com/how-to-count-the-number-of-open-network-connections-on-linux.html. Monitor connections in realtime (e.g. `sudo conntrack -E -e NEW -p tcp --dport 22`).

## Unsorted

### auditctl
