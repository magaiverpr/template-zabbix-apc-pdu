# template-zabbix-apc-pdu

en-US / [pt-BR](readme_pt-br.md)

Template created for APC PDU.
Tested equipments: AP8841
Tested zabbix versions: 3.0

Currently only shows the temperature, I will configure more parameters when I have time.

## Installation ##

import the xml on your zabbix. You need to register a macro on your host, pointing to your community:
{$SNMP_COMMUNITY} -> your community.
