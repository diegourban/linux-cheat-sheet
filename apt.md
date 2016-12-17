# apt commands

* `apt-get update` - update the list of programs
* `apt-get upgrade` - upgrade the programs
* `apt-cache search` - search for a program
* `apt-get install` - install a program
* `apt-get remove` - remove a program
* `apt-get check` - look for invalid dependencies

----

Atualizar a lista de pacotes: sudo apt-get update
Efetua a atualização: sudo apt-get upgrade
Instalar pacotes: sudo apt-get install nome do pacote
Procurar pacotes: apt-cache search palavras chave
Procurar por dependências inválidas: sudo apt-get check
Corrigir problemas de dependências, concluir instalação de pacotes pendentes e outros erros: sudo apt-get -f install
Se o comando sudo apt-get -f install não resolver use: sudo dpkg -i –force-all para forçar a instalação ou sudo dpkg -r nome do pacote para desistir da instalação
Remover arquivos inúteis do cache, onde são registradas as cópias das atualizações que são instaladas pelo gerenciador de pacotes: sudo apt-get clean
Remover pacotes instalados automaticamente e que não tem mais nenhuma utilidade para o sistema: sudo apt-get autoremove
Remover pacotes antigos ou duplicados: sudo apt-get autoclean
Remover pacotes com problemas: sudo apt-get -f remove
Remover pacotes instalados: sudo apt-get remove nome do pacote
halt, reboot, shutdown:  Respectivamente encerra, reinicializa e encerra ou reinicializa o sistema.
“sudo halt” para encerrar o sistema.
”sudo reboot” para reiniciar imediatamente o sistema. Este comando equivale aos comandos: ”sudo init 6” e ”sudo shutdown -r now”.
”sudo shutdown -h now” para encerrar o sistema imediatamente.
”sudo shutdown -h +15” para encerrar o sistema daqui a 15 minutos.


http://ubuntuforum-br.org/index.php?topic=110854.0
sudo update-alternatives --install /usr/bin/java java /opt/java/jre/bin/java 10 && sudo update-alternatives --set java /opt/java/jre/bin/java
