# template-zabbix-apc-pdu

[en-US](readme.md) / pt-BR

Template criado para o APC PDU.
Equipamentos homologados: AP8841
Versão do zabbix homologados: 3.0

Atualmente mostra só a temperatura, irei configurar mais parâmetros dele.

## Instalação ##

Faça a importação do xml no seu zabbix. É necessário cadastrar um macro no seu host, apontando para a sua community:
{$SNMP_COMMUNITY} -> sua community.
