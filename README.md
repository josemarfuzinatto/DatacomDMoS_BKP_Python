English: Script Python do to backup on hosts with running Datacom DMoS, to run follow steps:

1#file hosts.csv, needs to be edited with IP address and file-path to be send to FTP server

2#needs to be criated file-path insite the FTP server equals file hosts.csv

3#on the hosts, needs to be addeded user and password to script (needs only group "audit")  

4#on the hosts, needs to be enabled telnet server (datacom(config)# telnet-server enabled)

5#on file script_bkp_dmos.py, needs to be edited with the user and password created on before step

6#on file arquivo script_bkp_dmos.py, needs to be edited with the user and password of FTP server

7#Usage: "python3 script_bkp_dmos.py -f hosts.csv"

8#Enable the script on Crontab of your Operation Sistem to be automatizated


Portuguese: Script Python para backup de hosts que executam Datacom DMoS, para funcionar o mesmo é necessário os passos:

1#arquivo hosts.csv tem que ser editado de acordo com endereços de IP e pasta-destino que será enviado o arquivo de backup dentro do servidor FTP

2#tem que ser criado a pasta-destino dentro do servidor FTP de acordo com o arquivo hosts.csv

3#nos hosts, tem que ser adicionado um usuario e senha (necessita somente grupo "audit")  

4#nos hosts, tem que ser habilitado telnet server (datacom(config)# telnet-server enabled)

5#no arquivo script_bkp_dmos.py tem que ser editado o usuario e senha de acesso ao host de acordo como criado no passo anterior

6#no arquivo script_bkp_dmos.py tem que ser editado o usuario e senha do servidor FTP

7#Uso: "python3 script_bkp_dmos.py -f hosts.csv"

8#DICA: Adicionar o script no Crontab do sistema operacional para automarização


Suporte Oficial Datacom:
https://www.datacom.com.br/pt/suporte

https://supportcenter.datacom.com.br/