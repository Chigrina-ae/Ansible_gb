# Ansible_gb

ubuntu@ansible-gb:~$ ansible localhost -m setup
localhost | SUCCESS => {
    "ansible_facts": {
        "ansible_all_ipv4_addresses": [
            "10.0.0.14"
        ],
        "ansible_all_ipv6_addresses": [
            "fe80::f816:3eff:fec3:86e9"
        ],
        "ansible_apparmor": {
            "status": "enabled"
        },
        "ansible_architecture": "x86_64",
        "ansible_bios_date": "04/01/2014",
        "ansible_bios_version": "1.11.0-2.el7",
        "ansible_cmdline": {
            "BOOT_IMAGE": "/boot/vmlinuz-5.4.0-42-generic",
            "console": "ttyS0",
            "ro": true,
            "root": "LABEL=cloudimg-rootfs"
        },
        "ansible_date_time": {
            "date": "2023-01-10",
            "day": "10",
            "epoch": "1673381428",
            "hour": "20",
            "iso8601": "2023-01-10T20:10:28Z",
            "iso8601_basic": "20230110T201028825821",
            "iso8601_basic_short": "20230110T201028",
            "iso8601_micro": "2023-01-10T20:10:28.825891Z",
            "minute": "10",
            "month": "01",
            "second": "28",
            "time": "20:10:28",
            "tz": "UTC",
            "tz_offset": "+0000",
            "weekday": "Tuesday",
            "weekday_number": "2",
            "weeknumber": "02",
            "year": "2023"
        },
        "ansible_default_ipv4": {
            "address": "10.0.0.14",
            "alias": "ens3",
            "broadcast": "10.0.0.255",
            "gateway": "10.0.0.1",
            "interface": "ens3",
            "macaddress": "fa:16:3e:c3:86:e9",
            "mtu": 1500,
            "netmask": "255.255.255.0",
            "network": "10.0.0.0",
            "type": "ether"
        },
        "ansible_default_ipv6": {},
        "ansible_device_links": {
            "ids": {
                "vda": [
                    "virtio-26497812-fda5-485f-8"
                ],
                "vda1": [
                    "virtio-26497812-fda5-485f-8-part1"
                ]
            },
            "labels": {
                "vda1": [
                    "cloudimg-rootfs"
                ]
            },
            "masters": {},
            "uuids": {
                "vda1": [
                    "dd24e6a1-65c2-46c4-860a-a67634d55a24"
                ]
            }
        },
        "ansible_devices": {
            "loop0": {
                "holders": [],
                "host": "",
                "links": {
                    "ids": [],
                    "labels": [],
                    "masters": [],
                    "uuids": []
                },
                "model": null,
                "partitions": {},
                "removable": "0",
                "rotational": "1",
                "sas_address": null,
                "sas_device_handle": null,
                "scheduler_mode": "mq-deadline",
                "sectors": "112552",
                "sectorsize": "512",
                "size": "54.96 MB",
                "support_discard": "4096",
                "vendor": null,
                "virtual": 1
            },
            "loop1": {
                "holders": [],
                "host": "",
                "links": {
                    "ids": [],
                    "labels": [],
                    "masters": [],
                    "uuids": []
                },
                "model": null,
                "partitions": {},
                "removable": "0",
                "rotational": "1",
                "sas_address": null,
                "sas_device_handle": null,
                "scheduler_mode": "mq-deadline",
                "sectors": "61200",
                "sectorsize": "512",
                "size": "29.88 MB",
                "support_discard": "4096",
                "vendor": null,
                "virtual": 1
            },
            "loop2": {
                "holders": [],
                "host": "",
                "links": {
                    "ids": [],
                    "labels": [],
                    "masters": [],
                    "uuids": []
                },
                "model": null,
                "partitions": {},
                "removable": "0",
                "rotational": "1",
                "sas_address": null,
                "sas_device_handle": null,
                "scheduler_mode": "mq-deadline",
                "sectors": "146168",
                "sectorsize": "512",
                "size": "71.37 MB",
                "support_discard": "4096",
                "vendor": null,
                "virtual": 1
            },
            "loop3": {
                "holders": [],
                "host": "",
                "links": {
                    "ids": [],
                    "labels": [],
                    "masters": [],
                    "uuids": []
                },
                "model": null,
                "partitions": {},
                "removable": "0",
                "rotational": "1",
                "sas_address": null,
                "sas_device_handle": null,
                "scheduler_mode": "mq-deadline",
                "sectors": "0",
                "sectorsize": "512",
                "size": "0.00 Bytes",
                "support_discard": "4096",
                "vendor": null,
                "virtual": 1
            },
            "loop4": {
                "holders": [],
                "host": "",
                "links": {
                    "ids": [],
                    "labels": [],
                    "masters": [],
                    "uuids": []
                },
                "model": null,
                "partitions": {},
                "removable": "0",
                "rotational": "1",
                "sas_address": null,
                "sas_device_handle": null,
                "scheduler_mode": "mq-deadline",
                "sectors": "0",
                "sectorsize": "512",
                "size": "0.00 Bytes",
                "support_discard": "0",
                "vendor": null,
                "virtual": 1
            },
            "loop5": {
                "holders": [],
                "host": "",
                "links": {
                    "ids": [],
                    "labels": [],
                    "masters": [],
                    "uuids": []
                },
                "model": null,
                "partitions": {},
                "removable": "0",
                "rotational": "1",
                "sas_address": null,
                "sas_device_handle": null,
                "scheduler_mode": "mq-deadline",
                "sectors": "0",
                "sectorsize": "512",
                "size": "0.00 Bytes",
                "support_discard": "0",
                "vendor": null,
                "virtual": 1
            },
            "loop6": {
                "holders": [],
                "host": "",
                "links": {
                    "ids": [],
                    "labels": [],
                    "masters": [],
                    "uuids": []
                },
                "model": null,
                "partitions": {},
                "removable": "0",
                "rotational": "1",
                "sas_address": null,
                "sas_device_handle": null,
                "scheduler_mode": "mq-deadline",
                "sectors": "0",
                "sectorsize": "512",
                "size": "0.00 Bytes",
                "support_discard": "0",
                "vendor": null,
                "virtual": 1
            },
            "loop7": {
                "holders": [],
                "host": "",
                "links": {
                    "ids": [],
                    "labels": [],
                    "masters": [],
                    "uuids": []
                },
                "model": null,
                "partitions": {},
                "removable": "0",
                "rotational": "1",
                "sas_address": null,
                "sas_device_handle": null,
                "scheduler_mode": "mq-deadline",
                "sectors": "0",
                "sectorsize": "512",
                "size": "0.00 Bytes",
                "support_discard": "0",
                "vendor": null,
                "virtual": 1
            },
            "vda": {
                "holders": [],
                "host": "SCSI storage controller: Red Hat, Inc. Virtio block device",
                "links": {
                    "ids": [
                        "virtio-26497812-fda5-485f-8"
                    ],
                    "labels": [],
                    "masters": [],
                    "uuids": []
                },
                "model": null,
                "partitions": {
                    "vda1": {
                        "holders": [],
                        "links": {
                            "ids": [
                                "virtio-26497812-fda5-485f-8-part1"
                            ],
                            "labels": [
                                "cloudimg-rootfs"
                            ],
                            "masters": [],
                            "uuids": [
                                "dd24e6a1-65c2-46c4-860a-a67634d55a24"
                            ]
                        },
                        "sectors": "20969439",
                        "sectorsize": 512,
                        "size": "10.00 GB",
                        "start": "2048",
                        "uuid": "dd24e6a1-65c2-46c4-860a-a67634d55a24"
                    }
                },
                "removable": "0",
                "rotational": "1",
                "sas_address": null,
                "sas_device_handle": null,
                "scheduler_mode": "mq-deadline",
                "sectors": "20971520",
                "sectorsize": "512",
                "size": "10.00 GB",
                "support_discard": "0",
                "vendor": "0x1af4",
                "virtual": 1
            }
        },
        "ansible_distribution": "Ubuntu",
        "ansible_distribution_file_parsed": true,
        "ansible_distribution_file_path": "/etc/os-release",
        "ansible_distribution_file_variety": "Debian",
        "ansible_distribution_major_version": "20",
        "ansible_distribution_release": "focal",
        "ansible_distribution_version": "20.04",
        "ansible_dns": {
            "nameservers": [
                "127.0.0.53"
            ],
            "options": {
                "edns0": true
            },
            "search": [
                "mcs.local"
            ]
        },
        "ansible_domain": "mcs.local",
        "ansible_effective_group_id": 1000,
        "ansible_effective_user_id": 1000,
        "ansible_ens3": {
            "active": true,
            "device": "ens3",
            "features": {
                "esp_hw_offload": "off [fixed]",
                "esp_tx_csum_hw_offload": "off [fixed]",
                "fcoe_mtu": "off [fixed]",
                "generic_receive_offload": "on",
                "generic_segmentation_offload": "on",
                "highdma": "on [fixed]",
                "hw_tc_offload": "off [fixed]",
                "l2_fwd_offload": "off [fixed]",
                "large_receive_offload": "on",
                "loopback": "off [fixed]",
                "netns_local": "off [fixed]",
                "ntuple_filters": "off [fixed]",
                "receive_hashing": "off [fixed]",
                "rx_all": "off [fixed]",
                "rx_checksumming": "on [fixed]",
                "rx_fcs": "off [fixed]",
                "rx_gro_hw": "off [fixed]",
                "rx_udp_tunnel_port_offload": "off [fixed]",
                "rx_vlan_filter": "on [fixed]",
                "rx_vlan_offload": "off [fixed]",
                "rx_vlan_stag_filter": "off [fixed]",
                "rx_vlan_stag_hw_parse": "off [fixed]",
                "scatter_gather": "on",
                "tcp_segmentation_offload": "on",
                "tls_hw_record": "off [fixed]",
                "tls_hw_rx_offload": "off [fixed]",
                "tls_hw_tx_offload": "off [fixed]",
                "tx_checksum_fcoe_crc": "off [fixed]",
                "tx_checksum_ip_generic": "on",
                "tx_checksum_ipv4": "off [fixed]",
                "tx_checksum_ipv6": "off [fixed]",
                "tx_checksum_sctp": "off [fixed]",
                "tx_checksumming": "on",
                "tx_esp_segmentation": "off [fixed]",
                "tx_fcoe_segmentation": "off [fixed]",
                "tx_gre_csum_segmentation": "off [fixed]",
                "tx_gre_segmentation": "off [fixed]",
                "tx_gso_partial": "off [fixed]",
                "tx_gso_robust": "on [fixed]",
                "tx_ipxip4_segmentation": "off [fixed]",
                "tx_ipxip6_segmentation": "off [fixed]",
                "tx_lockless": "off [fixed]",
                "tx_nocache_copy": "off",
                "tx_scatter_gather": "on",
                "tx_scatter_gather_fraglist": "off [fixed]",
                "tx_sctp_segmentation": "off [fixed]",
                "tx_tcp6_segmentation": "on",
                "tx_tcp_ecn_segmentation": "on",
                "tx_tcp_mangleid_segmentation": "off",
                "tx_tcp_segmentation": "on",
                "tx_udp_segmentation": "off [fixed]",
                "tx_udp_tnl_csum_segmentation": "off [fixed]",
                "tx_udp_tnl_segmentation": "off [fixed]",
                "tx_vlan_offload": "off [fixed]",
                "tx_vlan_stag_hw_insert": "off [fixed]",
                "vlan_challenged": "off [fixed]"
            },
            "hw_timestamp_filters": [],
            "ipv4": {
                "address": "10.0.0.14",
                "broadcast": "10.0.0.255",
                "netmask": "255.255.255.0",
                "network": "10.0.0.0"
            },
            "ipv6": [
                {
                    "address": "fe80::f816:3eff:fec3:86e9",
                    "prefix": "64",
                    "scope": "link"
                }
            ],
            "macaddress": "fa:16:3e:c3:86:e9",
            "module": "virtio_net",
            "mtu": 1500,
            "pciid": "virtio0",
            "promisc": false,
            "speed": -1,
            "timestamping": [
                "tx_software",
                "rx_software",
                "software"
            ],
            "type": "ether"
        },
        "ansible_env": {
            "DBUS_SESSION_BUS_ADDRESS": "unix:path=/run/user/1000/bus",
            "HOME": "/home/ubuntu",
            "LANG": "C.UTF-8",
            "LESSCLOSE": "/usr/bin/lesspipe %s %s",
            "LESSOPEN": "| /usr/bin/lesspipe %s",
            "LOGNAME": "ubuntu",
            "LS_COLORS": "rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:",
            "MOTD_SHOWN": "pam",
            "PATH": "/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin",
            "PWD": "/home/ubuntu",
            "SHELL": "/bin/bash",
            "SHLVL": "1",
            "SSH_CLIENT": "90.154.73.11 4705 22",
            "SSH_CONNECTION": "90.154.73.11 4705 10.0.0.14 22",
            "SSH_TTY": "/dev/pts/0",
            "TERM": "xterm-256color",
            "USER": "ubuntu",
            "XDG_DATA_DIRS": "/usr/local/share:/usr/share:/var/lib/snapd/desktop",
            "XDG_RUNTIME_DIR": "/run/user/1000",
            "XDG_SESSION_CLASS": "user",
            "XDG_SESSION_ID": "1",
            "XDG_SESSION_TYPE": "tty",
            "_": "/usr/bin/ansible"
        },
        "ansible_fibre_channel_wwn": [],
        "ansible_fips": false,
        "ansible_form_factor": "Other",
        "ansible_fqdn": "ansible-gb.mcs.local",
        "ansible_hostname": "ansible-gb",
        "ansible_hostnqn": "",
        "ansible_interfaces": [
            "lo",
            "ens3"
        ],
        "ansible_is_chroot": false,
        "ansible_iscsi_iqn": "",
        "ansible_kernel": "5.4.0-42-generic",
        "ansible_kernel_version": "#46-Ubuntu SMP Fri Jul 10 00:24:02 UTC 2020",
        "ansible_lo": {
            "active": true,
            "device": "lo",
            "features": {
                "esp_hw_offload": "off [fixed]",
                "esp_tx_csum_hw_offload": "off [fixed]",
                "fcoe_mtu": "off [fixed]",
                "generic_receive_offload": "on",
                "generic_segmentation_offload": "on",
                "highdma": "on [fixed]",
                "hw_tc_offload": "off [fixed]",
                "l2_fwd_offload": "off [fixed]",
                "large_receive_offload": "off [fixed]",
                "loopback": "on [fixed]",
                "netns_local": "on [fixed]",
                "ntuple_filters": "off [fixed]",
                "receive_hashing": "off [fixed]",
                "rx_all": "off [fixed]",
                "rx_checksumming": "on [fixed]",
                "rx_fcs": "off [fixed]",
                "rx_gro_hw": "off [fixed]",
                "rx_udp_tunnel_port_offload": "off [fixed]",
                "rx_vlan_filter": "off [fixed]",
                "rx_vlan_offload": "off [fixed]",
                "rx_vlan_stag_filter": "off [fixed]",
                "rx_vlan_stag_hw_parse": "off [fixed]",
                "scatter_gather": "on",
                "tcp_segmentation_offload": "on",
                "tls_hw_record": "off [fixed]",
                "tls_hw_rx_offload": "off [fixed]",
                "tls_hw_tx_offload": "off [fixed]",
                "tx_checksum_fcoe_crc": "off [fixed]",
                "tx_checksum_ip_generic": "on [fixed]",
                "tx_checksum_ipv4": "off [fixed]",
                "tx_checksum_ipv6": "off [fixed]",
                "tx_checksum_sctp": "on [fixed]",
                "tx_checksumming": "on",
                "tx_esp_segmentation": "off [fixed]",
                "tx_fcoe_segmentation": "off [fixed]",
                "tx_gre_csum_segmentation": "off [fixed]",
                "tx_gre_segmentation": "off [fixed]",
                "tx_gso_partial": "off [fixed]",
                "tx_gso_robust": "off [fixed]",
                "tx_ipxip4_segmentation": "off [fixed]",
                "tx_ipxip6_segmentation": "off [fixed]",
                "tx_lockless": "on [fixed]",
                "tx_nocache_copy": "off [fixed]",
                "tx_scatter_gather": "on [fixed]",
                "tx_scatter_gather_fraglist": "on [fixed]",
                "tx_sctp_segmentation": "on",
                "tx_tcp6_segmentation": "on",
                "tx_tcp_ecn_segmentation": "on",
                "tx_tcp_mangleid_segmentation": "on",
                "tx_tcp_segmentation": "on",
                "tx_udp_segmentation": "off [fixed]",
                "tx_udp_tnl_csum_segmentation": "off [fixed]",
                "tx_udp_tnl_segmentation": "off [fixed]",
                "tx_vlan_offload": "off [fixed]",
                "tx_vlan_stag_hw_insert": "off [fixed]",
                "vlan_challenged": "on [fixed]"
            },
            "hw_timestamp_filters": [],
            "ipv4": {
                "address": "127.0.0.1",
                "broadcast": "host",
                "netmask": "255.0.0.0",
                "network": "127.0.0.0"
            },
            "ipv6": [
                {
                    "address": "::1",
                    "prefix": "128",
                    "scope": "host"
                }
            ],
            "mtu": 65536,
            "promisc": false,
            "timestamping": [
                "tx_software",
                "rx_software",
                "software"
            ],
            "type": "loopback"
        },
        "ansible_local": {},
        "ansible_lsb": {
            "codename": "focal",
            "description": "Ubuntu 20.04.1 LTS",
            "id": "Ubuntu",
            "major_release": "20",
            "release": "20.04"
        },
        "ansible_machine": "x86_64",
        "ansible_machine_id": "b1e7f113a8454e1a8203040e282cedbe",
        "ansible_memfree_mb": 515,
        "ansible_memory_mb": {
            "nocache": {
                "free": 764,
                "used": 217
            },
            "real": {
                "free": 515,
                "total": 981,
                "used": 466
            },
            "swap": {
                "cached": 0,
                "free": 0,
                "total": 0,
                "used": 0
            }
        },
        "ansible_memtotal_mb": 981,
        "ansible_mounts": [
            {
                "block_available": 1757229,
                "block_size": 4096,
                "block_total": 2440848,
                "block_used": 683619,
                "device": "/dev/vda1",
                "fstype": "ext4",
                "inode_available": 2556328,
                "inode_total": 2620160,
                "inode_used": 63832,
                "mount": "/",
                "options": "rw,relatime",
                "size_available": 7197609984,
                "size_total": 9997713408,
                "uuid": "dd24e6a1-65c2-46c4-860a-a67634d55a24"
            },
            {
                "block_available": 0,
                "block_size": 131072,
                "block_total": 440,
                "block_used": 440,
                "device": "/dev/loop0",
                "fstype": "squashfs",
                "inode_available": 0,
                "inode_total": 10756,
                "inode_used": 10756,
                "mount": "/snap/core18/1880",
                "options": "ro,nodev,relatime",
                "size_available": 0,
                "size_total": 57671680,
                "uuid": "N/A"
            },
            {
                "block_available": 0,
                "block_size": 131072,
                "block_total": 240,
                "block_used": 240,
                "device": "/dev/loop1",
                "fstype": "squashfs",
                "inode_available": 0,
                "inode_total": 463,
                "inode_used": 463,
                "mount": "/snap/snapd/8542",
                "options": "ro,nodev,relatime",
                "size_available": 0,
                "size_total": 31457280,
                "uuid": "N/A"
            },
            {
                "block_available": 0,
                "block_size": 131072,
                "block_total": 571,
                "block_used": 571,
                "device": "/dev/loop2",
                "fstype": "squashfs",
                "inode_available": 0,
                "inode_total": 1496,
                "inode_used": 1496,
                "mount": "/snap/lxd/16558",
                "options": "ro,nodev,relatime",
                "size_available": 0,
                "size_total": 74842112,
                "uuid": "N/A"
            }
        ],
        "ansible_nodename": "ansible-gb",
        "ansible_os_family": "Debian",
        "ansible_pkg_mgr": "apt",
        "ansible_proc_cmdline": {
            "BOOT_IMAGE": "/boot/vmlinuz-5.4.0-42-generic",
            "console": [
                "tty1",
                "ttyS0"
            ],
            "ro": true,
            "root": "LABEL=cloudimg-rootfs"
        },
        "ansible_processor": [
            "0",
            "GenuineIntel",
            "Intel Xeon Processor (Skylake, IBRS)"
        ],
        "ansible_processor_cores": 1,
        "ansible_processor_count": 1,
        "ansible_processor_threads_per_core": 1,
        "ansible_processor_vcpus": 1,
        "ansible_product_name": "OpenStack Compute",
        "ansible_product_serial": "NA",
        "ansible_product_uuid": "NA",
        "ansible_product_version": "15.1.3-202212191438.git090af6a187.cmpt.el7",
        "ansible_python": {
            "executable": "/usr/bin/python3",
            "has_sslcontext": true,
            "type": "cpython",
            "version": {
                "major": 3,
                "micro": 2,
                "minor": 8,
                "releaselevel": "final",
                "serial": 0
            },
            "version_info": [
                3,
                8,
                2,
                "final",
                0
            ]
        },
        "ansible_python_version": "3.8.2",
        "ansible_real_group_id": 1000,
        "ansible_real_user_id": 1000,
        "ansible_selinux": {
            "status": "Missing selinux Python library"
        },
        "ansible_selinux_python_present": false,
        "ansible_service_mgr": "systemd",
        "ansible_ssh_host_key_dsa_public": "AAAAB3NzaC1kc3MAAACBALAQd/x09eP+t+mBym2D6LatAa48gEqsBtCwSPczEXFBPxGA5zINbrUDVNzoMgTA1Zglgare4b3n1+rhA/GcTj9Phb9cKHNGu3mxf4FBp2tjFt7UI0tzwz4qWB8YAddHDMEO62fLHQeBKty/WknUNj8T6O3pMrwpt3Ehz37/sSaPAAAAFQDykSyZO6IqZkPRsbs6YvH9Fs/vJwAAAIEAgIRx9w1r904FGtatJbH8pZbAjzZ8N+NHTZxn4W5Sd8N5WWRJosPXQoRX/zWJErzuzW7ZqPIXtEH88tHDCXGnEx3KpqbvhpdO38e7dQeY++CJ+fVs2e4kY/yfXiYxqn1+Fc82bYYglFD00EhIgcjaaKeO6cLEd9iQYbr+84j1HdUAAACBAKhUBmDLj+otkx5D747lr3YftWOVLsKmvF3VmsTXTfee6ykgNWeMCl47Bt6aIIP4xJh2T1crFsd1iwVhHsD3e/b65EkY2/yucpF7rjpCoFsOk8VfJvd6GfTSARIZBwxP7PfELkpxHLGRtuT7ogSPz30s+FCaSsgvE0LEna3YjpUG",
        "ansible_ssh_host_key_ecdsa_public": "AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBLIljsVRmNi4/T/EEDYO5CMTOA8jP72qTcSz7F6m6EA0upDYX9w3kf2bFLF5u+wBYcgKEhixSe+HeJXsH6oDaIs=",
        "ansible_ssh_host_key_ed25519_public": "AAAAC3NzaC1lZDI1NTE5AAAAIOjSeocRlliI74T+MtQzY/XFUq/Ln0sX7H/gIRaBV4od",
        "ansible_ssh_host_key_rsa_public": "AAAAB3NzaC1yc2EAAAADAQABAAABgQDcVkeNX/QPWMyw5fWZc2vIQCt6fWsXe8xFXdGBgc2k/sxIf/hrE11IK+vcs/M77Wupwg0sEpSr+z0qxPfpcUP3GT0i1eP5KnzOiMkGBulrKBMSFoIHIIStdD9Hkx4oYeLMc0M2oGqZ0my1459xMyxAV6CRaIIjXYV6TbroY4rI+Fkvjx+otFT+sG0X1r1LYiHjpaFQX7ti5MCjJpnGUqslXjp8RAQV/2fEZxMREeueOIywk2ZzlrzuSJ4hwTdvqJMXInLIAplX+xntK1XN95Ipa727/ff3y8uuxEQwEI1UzfnSmUOt3SJykXikH80MuW57vk8pmkHd4+69VM6Zikq9qxcmgl/tsN9JtS8hieQBi4wsS8UC5mII/uLmmVUQliukX/TVhrUtSbL/q4ODlyyXLPxnIc8rq1QBY5D4x0f8/1lFcxEYO0tx5IT0n//0j7rkVnrpVAQpGD1EM1WCsCK0XWWpEeda36X8DdDRqVvq7eQfrNYip6rmSXdRz//ftJ8=",
        "ansible_swapfree_mb": 0,
        "ansible_swaptotal_mb": 0,
        "ansible_system": "Linux",
        "ansible_system_capabilities": [
            ""
        ],
        "ansible_system_capabilities_enforced": "True",
        "ansible_system_vendor": "cmpt",
        "ansible_uptime_seconds": 149,
        "ansible_user_dir": "/home/ubuntu",
        "ansible_user_gecos": "Ubuntu",
        "ansible_user_gid": 1000,
        "ansible_user_id": "ubuntu",
        "ansible_user_shell": "/bin/bash",
        "ansible_user_uid": 1000,
        "ansible_userspace_architecture": "x86_64",
        "ansible_userspace_bits": "64",
        "ansible_virtualization_role": "guest",
        "ansible_virtualization_type": "openstack",
        "gather_subset": [
            "all"
        ],
        "module_setup": true
    },
    "changed": false
}
ubuntu@ansible-gb:~$
