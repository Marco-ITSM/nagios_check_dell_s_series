# nagios_check_dell_s_series

Nagios check plugin for Dell | EMC² S-series switches, running OS10 firmware

This check retrieve operational values from Dell specific SNMP MIBs :
  - hardware health
  - power unit status
  - fans status
  - temperatures

For switching specific metrics (interface stats, etc) it uses standard NET-SNMP MIBs, so you can use generic SNMP check as the excellent check_nwc_health from Consol Labs:

https://labs.consol.de/nagios/check_nwc_health/

2018-09-04 - Eric Belhomme <rico-github@ricozome.net> - Published under MIT license

2022-03-03 - Jon Witts - Updated for Python 3

2025-02-20 - Marco Hahnen - Replaced netsnmp with easysnmp for Debian 12 compatibility
