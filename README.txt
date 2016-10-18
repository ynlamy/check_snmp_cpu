This plugin can check the CPU load using SNMP v1 queries.

check_snmp_cpu is written in Bash and is distributed under the GPLv2 license. This plugin have been created by Yoann LAMY.

Usage: ./check_snmp_cpu -H 192.168.0.1 -C public -w 80 -c 90

-H ADDRESS
Name or IP address of host (default: 127.0.0.1)
-C STRING
Community name for the host SNMP agent (default: public)
-w INTEGER
Warning level for the cpu load in percent (default: 0)
-c INTEGER
Critical level for the cpu load in percent (default: 0)
-h
Print this help screen
-V
Print version and license information

This plugin uses the 'snmpwalk' command included with the NET-SNMP package.
This plugin support performance data output. 

This nagios plugins comes with ABSOLUTELY NO WARRANTY.

You may redistribute copies of the plugins under the terms of the GNU General Public License v2.
