# X310-octoclock
commands and config for X310 
Set on host


set network interface mtu size:
sudo ifconfig enp23s0f0 mtu 9000


set read and write buffers:
sudo sysctl -w net.core.wmem_max=24862979
sudo sysctl -w net.core.rmem_max=24862979

