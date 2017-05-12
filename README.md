# template-zabbix-apc-pdu

**PT-BR**

Template criado para o APC PDU.
Equipamentos homologados: AP8841
Versão do zabbix homologados: 3.0


Atualmente mostra só a temperatura, irei configurar mais parâmetros dele.

Instalação:

Faça a importação do xml no seu zabbix. É necessário cadastrar um macro no seu host, apontando para a sua community:
{$SNMP_COMMUNITY} -> sua community.



**ENG**

Template created for APC PDU.
Tested equipments: AP8841
Tested zabbix versions: 3.0

Currently only shows the temperature, I will configure more parameters when I have time.


Installation:

import the xml on your zabbix. You need to register a macro on your host, pointing to your community:
{$SNMP_COMMUNITY} -> your community.
