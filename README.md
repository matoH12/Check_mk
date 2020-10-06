# Check_mk
Check_mk APC PDU temperature plugins. 

Check read temperature from APC PDU sensors. 



Simple check APC PDU :
# snmpwalk -v2c -c public 192.168.253.155 .1.3.6.1.4.1.318.1.1.26.10.2.2.1 

OUTPUT FROM PDU:
#iso.3.6.1.4.1.318.1.1.26.10.2.2.1.1.1 = INTEGER: 1
#iso.3.6.1.4.1.318.1.1.26.10.2.2.1.2.1 = INTEGER: 1
#iso.3.6.1.4.1.318.1.1.26.10.2.2.1.3.1 = STRING: "C1_HORE"  ===== Sensor name
#iso.3.6.1.4.1.318.1.1.26.10.2.2.1.4.1 = INTEGER: 1
#iso.3.6.1.4.1.318.1.1.26.10.2.2.1.5.1 = INTEGER: 1
#iso.3.6.1.4.1.318.1.1.26.10.2.2.1.6.1 = INTEGER: 2
#iso.3.6.1.4.1.318.1.1.26.10.2.2.1.7.1 = INTEGER: 845
#iso.3.6.1.4.1.318.1.1.26.10.2.2.1.8.1 = INTEGER: 292  ====== Temperature value
#iso.3.6.1.4.1.318.1.1.26.10.2.2.1.9.1 = INTEGER: 4
#iso.3.6.1.4.1.318.1.1.26.10.2.2.1.10.1 = INTEGER: -1
#iso.3.6.1.4.1.318.1.1.26.10.2.2.1.11.1 = INTEGER: 1





Compatible APC PDU:

AP8653
AP8886

