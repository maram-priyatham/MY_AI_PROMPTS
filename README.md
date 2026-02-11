1  df -h
    2  df -HT
    3  df -hT
    4  df -T
    5  df -H
    6  df -h
    7  lsblk --fs
    8  lsblk --f
    9  fdisk -l /dev/nvme1n1
   10  parted /dev/nvme1n1
   11  parted /dev/nvme1n1 unit s
   12  parted /dev/nvme1n1 unit s print
   13  parted /dev/nvme1n1 unit MiB print
   14  parted /dev/nvme1n1
   15  df -h
   16  parted /dev/nvme1n1
   17  mkfs.xfs /dev/nvme1n1
   18  lsblk
   19  mkfs.xfs /dev/└─nvme1n1p1
   20  mkfs.xfs /dev/nvme1n1p1
   21  ls
   22  df -h
   23  cd /
   24  mkdir -p data
   25  cd ~
   26  mount /dev/nvme1n1p1 /data
   27  df -h
   28  parted /dev/nvme1n1p1
   29  history
   30  parted /dev/nvme1n1 mklabel gpt
   31  parted /dev/nvme1n1 mkpart data xfs 1MiB 2GB
   32  parted /dev/nvme1n1 mkpart data xfs 2048s 2GB
   33  parted /dev/nvme1n1 mkpart data xfs 0 2GB

wipefs -a /dev/nvme1n1p1
   37  mkfs.xfs /dev/nvme1n1p1 /data





1  lsblk -f
    2  mkdir -p /data
    3  mount /dev/nvme1n1p1 /data/
    4  mount -o --nouuid /dev/nvme1n1p1 /data/
    5  mount -o nouuid /dev/nvme1n1p1 /data/
    6  df -h
    7  cd /data/
    8  ls
    9  cd ..
   10  ls
   11  cd /data/
   12  ls
   13  cd ~
   14  df -h
   15  parted /dev/nvme1n1p1
   16  ls
   17  cd /
   18  ls
   19  cd data/
   20  ls
   21  cd ..
   22  df -h
   23  mount -a
   24  df -h
   25  mount -a
   26  df -h
   27  lsblk
   28  ls
   29  uptime
   30  last -a
