Exit 78 on docker => grep vm.max_map_count /etc/sysctl.conf
sudo sysctl -w vm.max_map_count=262144
