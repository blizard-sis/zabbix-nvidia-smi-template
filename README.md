# zabbix-nvidia-smi-template

Template and files for OS Windows and Linux
Use for get metrics from multi GPU system
tested on Zabbix 5.4 with zabbix-agent2

Install:
1) Import Template to your zabbix system
2.1) For Linux copy "userparameter_nvidia-smi_linux.conf" to /etc/zabbix/zabbix_agent2.d/
2.2) For Windows copy "userparameter_nvidia-smi_win.conf" to C:/ProgrammFiles/zabbix/zabbix-agent2.d/
3) restart zabbix-agent2
4) attache Template to your Host
