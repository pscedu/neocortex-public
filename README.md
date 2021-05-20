# Public Neocortex Configurations and Scripts Repository

## Description
The _Neocortex_ system is integrated by a Superdome Flex server that is split into two socket-partitions, 
each one with four individual chassis, and each chassis with 4 CPUs of 28 cores each, 8 NVMe flash drives, 
2 InfiniBand interfaces, and 3 100Gb Ethernet interfaces; and two CS-1 boxes.

For gaining access to the free resources and configurations offered by the Neocortex team, please email us at <a target="_blank" href="mailto:neocortex@psc.edu">neocortex@psc.edu</a>

    .
    ├── LICENSE
    ├── README.md
    ├── slurm
    │   ├── cgroup.conf
    │   ├── etc_sysconfig_slurmd
    │   ├── gres.conf
    │   ├── scripts
    │   │   ├── grepfunc.py
    │   │   └── variables_setter.py
    │   ├── slurm.conf
    │   └── slurmdbd.conf
    └── system_config
        ├── arp_flux.conf
        ├── helper_scripts
        │   └── test_ping.py
        └── policy_routing.conf

For more information about Neocortex, please visit the <a target="_blank" href="https://www.cmu.edu/psc/aibd/neocortex/index.html">project page</a>.
