# 打开网卡
vi /etc/sysconfig/network-scripts/ifcfg-eth33

# 填入配置项(固定IP)
TYPE="Ethernet"  
BOOTPROTO="static"  
DEFROUTE="yes"  
NAME="ens33"  
DEVICE="ens33"  
ONBOOT="yes"  
IPADDR=1.1.1.5  
PREFIX=24  
GATEWAY=1.1.1.2  
DNS1=8.8.8.8  
DNS2=8.8.4.4

# 编辑->虚拟网络编辑器

![avatar](/xiaofancomputer/image/blob/main/vmware_set.png?raw=true)
