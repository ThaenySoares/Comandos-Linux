# Pasta Compartilhada no Linux ✈️

- vai no VirtualBox -> configurações -> pastas compartilhadas -> + -> C:\virtualBox-PastaCompartilhada -> coloca um nome na pasta -> dar check em montar automaticamente e tornar permanentemente (desmarca apenas leitura) -> ok -> reinicalizar o Linux.
- Agora vai na unidade C: do Windows -> criar pasta -> criar um arquivo dentro da pasta -> arquivo_text_host -> colocar alguma coisa e salvar.

### Via Terminal Linux

- comando ls serve para listar
- ls\media
- cd é comando dentro da pasta
- cd/media
- cd sf_virtualbox-PastaCompartilhada/  // se usar essse comando sem adiconar o usuário vai dar permissão negada
- sudo adduser $USER vboxsf -> adiciona um novo usuário ao grupo
- sudo reboot

- Após reincializar você executa os comandos
- cd/media
- cd sf_virtualbox-PastaCompartilhada/
- ls -> lista o que tem dentro do arquivo

- comando clear -> serve para limpar o terminal

### Comando cat - serve para ler e exibir o que foi colocado

- cat arquivo_test_host.txt -> esse é o nome do arquivo que coloquei dentro da pasta compartilhada

### Comando echo - serve para gravar um texto

- echo "este é um teste para verificar se funciona"> arquivo_teste_guest.txt ------ faz gravação em uma nova pasta.

### Editor: VIM e Nano

nano arquivo_teste_guest ----- dentro do arquivo para editar

### Instalar o Vim

- sudo get install vim -> sim
- reboot
- vim nome_arquivo
- : set number -> colocar linhas
- :wq-> grave e saia 
- q! -> sair sem salvar
- tecla insert -> insere valores

- comando cd home - home do usuário
- cd linux (nome usuário)
- C: DO Windows é o $ do Linux (Raiz)
- vim ~/.vimrc -> enter

