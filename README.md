# Criação do site em Wordpress
Ao abrir um terminal, deve-se atualizar o catalogo atraves docomando: apt install update
Em seguda deve-se realizar a instalação dos principais recursos que iremos utilizar ao longo desse processo de criação. Para realizar essa instalação deve-se utilizar o comando: apt install -y tree curl wget exa
Para realizar acriação do conetener deve execultar o seguinte comando: lxc launch images:debian/12/cloud nome-contener 
Instalar as principais ferramentas com o seguinte comando: sudo apr install -y mariadb-server php libapache2-mod-php php-mysql
para verificar os contenier criados digite: lxc list 
para acessar o conteaner digite: lxc exec nome-contenier bash
utilizando o tree para verificar a estrutura do arquivo, junto com o -d ele faz com que o tree mostre apenas a estrutura de diretorios: tree -d /etc/apache2
dentro desse mesmo diretorio, entrar na pasta sites-avalable/ para verificar os arquivos de configuração criados dentro dele: 000-default.conf e default-ssl.cong

