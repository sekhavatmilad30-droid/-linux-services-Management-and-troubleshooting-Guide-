*linux services Management and troubleshooting Guide*
	1.check service status 
                 To check the status of a specific service  
	Systemctl status sshd 
2. list running services 
 To list all active services running on the system
           Systemctl  list-units  --type=services  --state=running 
3.advanced  log troubleshooting  with journalctl
  To view critical system error logs from the current boot 
           Journalctl -p err -b 
 
 
