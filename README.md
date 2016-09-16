127.0.0.1       localhost

# The following lines are desirable for IPv6 capable hosts
#::1     localhost ip6-localhost ip6-loopback
#ff02::1 ip6-allnodes
#ff02::2 ip6-allrouters

# manager #
192.168.35.230 manager namenode

# ubuntu host list #
192.168.35.225 ubuntu0 elasticsearch sname
192.168.35.80  ubuntu1 hadoop2 datanode1
192.168.35.10  ubuntu2 hadoop3 datanode2
192.168.35.5   ubuntu3 control-tower
192.168.35.189 ubuntu4 hadoop1 datanode4
192.168.35.251 ubuntu5 hadoop4 datanode3

192.168.35.132 nutch-control
192.168.35.173 nutch2
192.168.35.85  nutch3
#####################
