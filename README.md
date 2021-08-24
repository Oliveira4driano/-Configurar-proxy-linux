# -Configurar-proxy-linux

requisitos, utlizar o editor de arquivos nano ou vim

cd /etc/apt

nano apt.conf

-#dentro do arquivo adicione o comando
Acquire::proxy "http://172.22.2.1:2121/";

obs: substitua pelo proxy de sua rede
precione: ctrol+o para salve
ctrol+x para sair
