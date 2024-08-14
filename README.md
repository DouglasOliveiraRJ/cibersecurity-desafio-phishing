# Phishing para captura de senhas do Facebook

*FERRAMENTAS*
- Kali Linux
- setoolkit

*CONFIGURANDO O PHISHING NO KALI LINUX* 
- Acesso do root: sudo su
- sudo lsof -t -i tcp:80 -s tcp:listen | sudo xargs kill (devido ao erro do apache que reiniciava o setoolkit, optei por usar esse comando.)
- Iniciando o setoolkit: setoolkit
- Tipo de ataque: Social-Engineering Attacks
- Vetor de ataque: Web Site Attack Vectors
- Método de ataque: Credential Harvester Attack Method
- Método de ataque: Web Template
- Obtendo o endereço da máquina: ifconfig
- URL para clone: google




