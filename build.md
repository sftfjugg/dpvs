yum install numactl-devel popt-devel openssl-devel libpcap-devel libpcap autoreconf automake kernel-devel

cat /boot/grub2/grub.cfg | grep menuentry | awk -F\' '{if(NF>1)print $2}'

grub2-set-default 'CentOS Linux (0-rescue-9bc9d3b997484f05acdf542e11320186) 7 (Core)'

grub2-editenv list
