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

*RESULTADO*


![image](https://github.com/user-attachments/assets/8759f180-2cce-4595-bce4-ecf9fc86dff6)


*OBS*: Tive que mudar para o template do google pois o facebook atualizou e o método feito pelo professor do curso, não funciona hoje atualmente.
