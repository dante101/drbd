# drbd
drbdadm create-md storage1 
systemctl enable drbd.service 
systemctl start drbd.service 
systemctl status drbd.service 
drbdadm primary storage1 --force
cat /proc/drbd
