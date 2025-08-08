# Comandos linux

#### sudo apt upgrade

- comando sudo: concede privilegios de administrador(superusuário)
- comando apt: gerenciador de pacotes
- sudo upgrade:  gerenciador de pacotes
- sudo apt upgrade: baixa os pacotes + recentes
  
- sudo reboot: reinicializa

#### sudo apt install build-essencial dkms linux-headers-$(uname -r)

- Instala: build-essencial: um pacote que instala várias ferramentas essenciais para programar e compilar programas.
- dkms: recompilador de aplicações para compatibilidade com Kernek do convidado(guest).
- linux-headers: são os arquivos de cabeçalho do kernel Linux que são necessários para compilar módulos do kernel, como drivers
- $(uname -r) é um comando que pega a versão exata do seu Linux atual.

#### cd/media/$USER/Vbox_GA_7.0.6

- Caminha até o diretório onde está o aplicativo para instalar recursos adicionais de convidado
  
#### $USER 

- é uma variável de ambiente que referencia o valor do usuário que está logado (nome usuário)

- echo $USER - traz o nome do usuário

- sudo ./VboxLinuxAdditions.run (. run é a mesma coisa do .exe do Linux) - Executa a aplicação disponível no diretório que acessou e instala os recursos

#### lsmod | grep vbox

- lsmod - Listar módulos carregados no Kernel 
- grep vbox - funciona como um filtro para pesquisar apenas as linhas que contenham o texto que deseja pesquisar (nesse caso, vbox)
- vbox - prefixo que inicia normalmente os nomes dos módulos do VirtualBox
 
