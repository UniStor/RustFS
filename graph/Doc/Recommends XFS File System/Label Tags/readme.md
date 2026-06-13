"For better disk discovery, when formatting xfs file systems, we recommend using Label tags to mark disks."

"sudo mkfs.xfs  -i size=512 -n ftype=1 -L RUSTFS0 /dev/sdb"

https://docs.rustfs.com/installation/linux/single-node-single-disk.html#_2-7-file-system-selection
