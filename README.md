# Linux-Tomcat-Server
Servidor Java Web 

Site para gerar um dominio:
- Registro.br -> Pago por ano

#### Quando falar de recursos leve como hardware e capacidade de hardware

Debian tem como principal foco a estabilidade e é muito 
utilizado em servidores.

Apache ou servidor http apache
- Http é o protocolo que transfere os arquivos do servidor 
ao navegador de internet
-  É o mais bem sucedido servidor web livre que existe
- Usado principalmente no linux

O MySQL é um sistema de gerenciamento de bando de dados que utiliza a linguagem SQL como interface.
- Código aberto
- Mais conhecido no mundo

O PHP é uma linguagem que permite criar sites dinâmicos possibilitando uma interação com o usuário atravez de formulários, parâmetros na url, links e principalmente no uso de banco de dados.
-  É executado no lado do servidor

O Wordpress é um cms ou aplicativo de sistema para gerenciar conteúdo na web escrito em php com bando de dados mysql.
- Voltado principalmente para criação de sites, blogs e lojas virtuais

O que é um servidor VPS? 

- Vps significa virtual private server ou servidor virtual privado
- Virtual significa que o servidor é criado por um software de virtualização dentro de um servidor físico

- Private é restrito para você
- Server é o servidor web

Na hospedagem compartilhada o site fica armazenado e dividindo espaço e recursos com centenas de outros sites hospedados no mesmo servidor. Oferece um plano limitado mesmo que seja ilimitado.

No servidor dedicado a máquina física hospeda apenas um site. É possível hospedar outros sites e serviços mas quem pagou decide isso.

Em uma hospedagem compartilhada um único servidor é repartido e custeado entre centenas de clientes ao passo que no servidor dedicado o custo é de apenas um único cliente.

Opção intermediaria, ou seja com mais recursos do que um servidor compartilhado, mas não tão caro quanto um servidor dedicado. É nesse ponto que o VPS se encaixa.

O servidor VPS é um servidor dedicado virtualizado

Quem precisa de um Servidor VPS?

- O primeiro e o mais importante é para quem tem um site hospedado em um servidor compartilhado e o tráfego cresce esponencialmente ou de forma abrupta até que o tempo de resposta do servidor sejam muito longos.

- Para quem tem vários sites hospedados de forma individual. Neste caso o VPS pode ser a solução mais barata.

-  Para quem pretente abrir uma empresa de hospedagem de sites. Neste caso o ideal é começar com um VPS e a medida que o negócio for crescendo ou escalando pode migrar para um servidor dedicado.

- Para quem quer montar um servidor para jogos, por exemplo, um servidor para minecraft

- Para quem é desenvolvedor e precisa de um ambiente real para testes e estudos.

O VPS permite que você escolha o sistema operacional além do acesso como administrador ou root, isso permite instalar, configurar qualquer aplicação que desejar e isso não acontece na hospedagem compartilhada.

Como funciona o servidor VPS?

O servidor virtual funciona dentro de um servidor físico junto com outros servidores virtuais, porém seus recursos e capacidades são bem definidos e separados em cada ambiente virtualizados. Existem areas privadas e exclusivas entre os servidores virtuais isso assegura que um site não vai afetar de maneira alguma outro site hospedado no mesmo servidor.

Quais suas vantagens?

- Autonomia
Além de instalar o sistema operacional de sua preferência, configurar o servidor conforme as necessidades, instalar tudo que quiser, total controle sobre o painel administrativo e poderá reiniciar a máquina para liberar memória ou corrigir algum travamento. Algo que não seria possível em um servidor compartilhado.

- Recursos dedicados
Memoria, espaço em disco, pode usar até o limite que não vai prejudicar ninguém.
- Upgrade
É fácil expandir os recursos
- Segurança
Ambiente fechado e protegido das outras contas VPS, além de ter um número de vizinhos reduzidos. 
- Segurança
Possui privacidade de dados.
- Custo
Embora tenha muitas caracteristicas de um servidor dedicado. Os servidores VPS's possuem um exelente custo benefício.

Como configurar um servidor VPS?

- Gerenciado 
- Semi-gerenciado

Como escolher o melhor VPS? 

Dois fatores, quanto quer gastar e quando necessita de recursos.

O que é um Cloud Server?

- No VPS nos temos um servidor virtual que é formado por uma única máquina física. No Cloud Server também temos um servidor virtual, porém esse servidor virtual usa a infraestrutura nas nuvens que é formada por diversas máquinas físicas que compartilham e dividem os recursos. Isso faz com que o servidor virtual tenha alta disponibilidade e desempenho.

Quem precisa de um cloud server?
- Recomendado para aplicações web que necessitam de velocidade e disponibilidade
- para empresas que desejam baratear sua infraestrutura de TI, migrando seus sistemas internos para as nuvens.

Como funciona o Cloud Server?
- Na prática a nuvem é um rede poderosa de computadores interligados que juntos formam um super computador. Neste super computador podemos ter diversos outros computadores virtuais, cada um com características específicas de processamento, memória, armazenamento e sistema operacional. Por se tratar de espaços virtuais cada máquina virtual pode ter seus recursos expandidos ou reduzidos facilmente.

- Categoria IaaS
Infrastructure as a service ou Infraestrutura como serviço.
- Uma forma de contratar serviços de acordo com seus negócios

Vantagens

- Não depende de um único servidor físico;
- Maior disponibilidade;
- Facilidade no aumento de recursos;
- Maior compatibilidade com hardware/software e segurança;
- Flexibilidade, sua aplicação pode ser acessada de qualquer lugar;
- Elasticidade (aumento ou redução) de recurso;
- Controle de custos (pague à medida que utilizar);
- Capacidade de processamento;
- Barateamento dos custos com infraestrutura de TI;

Dica: Fique atento
- Por sua natureza flexivel os custos que envolvem cloud server podem começar baixos, mas também podem evoluir para algo muito maior do que o planejado inicialmente, caso o uso dos recursos estrapolem o usual, além disso alguns recursos específicos podem ser cobrados separadamente e contribuir para o aumento do custo, por exemplo, a quantidade de dados transferidos para nuvem e o espaço para armazenamento.
- Muito importante fazer um planejamento para tentar prever a quantidade de recursos que deverá ser alocado para a aplicação, se possível comece com poucos recursos e tenha um plano que possa voltar atrás ou mudar de provedor caso o custo se revele maior do que o planejado.

O que é linux?

- Kernel de código fonte aberto
- Kernal é a parte do sistema operacional responsável pela comunicação do software com o hardware é o que existe de mais complexo em termos de programação

- Criado por Linus Torvalds.
- Richard Stallman Criou em 1983 o projeto GNU com o objetivo de desenvolver uma versão do unix com código fonte aberto. Em 1985 ele publicou o manifesto e o tratado anti capyright intitulado GPL, esse tratado cria a free software fundation e dando apoio aos desenvolvedores que queiram liberar seu código fonte. O linux está licenciado sobre a GPL que em termos gerais baseia-se em quatro libertades:
- Executação para qualquer propósito
- Estudas como o programa funciona e adapta-lo as suas necessidades
- A liberdade de redistribuir cópias de modo que possa ajudar a seu próximo. Pre-requiso: acesso ao código fonte
- A liberdade de aperfeiçoar o programa e liberar seus aperfeiçoamentos de modo que todos se beneficiem. Pre-requiso: acesso ao código fonte

- A GPL garante a propriedade intelectual ao seu criador. Você não pode, por exemplo, se apoderar do linux "falar que você que criou" ou "falar que ele é seu".

Tux este é o mascote oficial do linux
- Criado em 1996 por Larry Ewing com o uso da ferramenta GIMP(também é uma ferramenta livre).
- Ideia de pinguim veio do próprio Linus Torvalds.

Distribuição Linux
- Uma distribuição Linux é formada pelo Kernel mais um conjunto de aplicações e serviços.
- Tudo é empacotado e distribuido fazendo do Linux um sistema altamente personalizavel que funciona em direntes arquiteturas de hardware
- O Android é a distribuição Linux mais popular e mais usada no planeta. O sistema Android é baseado no Kernel do Linux.

The Linux Foundation ou Fundação Linux
- Sem fins lucrativos
- Criada para fomentar o crescimento do Linux
- Mantida pelas principais empresas de tecnologia e devs de todo o mundo.

Certificação Linux LPI
- Uma das maneiras que os fabricantes de hardware e hardware encontram para medir o quanto um profissional conhece de determinado assunto.
- A certificação é usada para processos seletivos
- A certificação LPI é reconhecida internacionalmente
- Vídeo que fala sobre as certificações https://youtu.be/fM3G7yLNAjQ

Instalação:
- Configurações -> armazenamento -> escolher a iso
- Rede -> Modo bridge 
- ``` IMPORTANTE Deixar pelomenos 16GB para o sistema ```

Configurando Debian

Particionar Disco
- Assistido - usar o disco inteiro e configurar LVM 
Permite adicionar novos discos físicos e redimencione as partições sem desligar o servidor
- Essa questão do LVM é muito IMPORTANTE
- Vídeo configurando LVM com servidor em PRODUÇÃO: 
https://www.youtube.com/watch?v=65Kr70FSk6Y

- Sempre devemos planejar o particionamento do disco de um servidor em função dos serviços
- O tomcat armazena os Sites e as aplicações em Java dentro do diretório /var

- Separamos então a partição de usuários /home, /var e /tmp 
isso traz mais segurança e desempenho ao servidor

Comandos:
- ``` hostnamectl ``` -> exibe a versão do debian e a versão do Kernel do Linux
- ``` shutdown -h now ``` -> desliga o servidor

Configurando um IP Fixo no Servidor Apache tomcat
- ``` ip a ``` -> exibe as configurações de ip
- como estou com a placa em modo bridge ele pegou o ip direto do roteador
- No cmd do hospedeiro executamos o comando 
ipconfig /all
- Pegamos o gateway e apontamos o ip no navegador
Configurações avançadas -> definição do servidor DHCP 
- O passo a cima é importante para não gerar conflito de IP
- ``` cd /etc/network ```
- ``` pwd ``` -> ver o diretório atual
- ``` ls ``` -> lista arquivos e diretórios
- Precisamos configuras o arquivo INTERFACES para obter um IP Fixo
- Fazendo uma cópia de segurança do arquivo antes de modifica-lo.
- ``` cp interfaces interfaces.bkp ```
- ``` vi interfaces ``` -> abre o arquivo no editor vi
- ``` Esc :set number ``` -> numerar as linhas
- Na linha 12 apagamos o DHCP
- Precionamos a tecla "a" para ativar o modo de inserção
- A linha 12 ficará assim:
  ``` iface enp0s3 inet static ```
- Na linha 13 definindo o endereço:
  ``` address <endereço IP disponível na rede> ``` SEM os sinais de < e >
- Na linha 14 definindo a máscara:
  ``` netmask <máscara da rede> ``` SEM os sinais de < e >
- Procurar por classes de máscaras para fazer o passo a cima.
- Na linha 15 definindo a rede: 
 ``` network 192.168.0.0 ```
- A rede sempre inicia com o final 0
- Na linha 16 definindo o broadcast:
 ``` broadcast 192.168.0.255 ```
- broadcast sempre finaliza com IP 255
- Na linha 17 definindo gateway: 
```  gateway 192.168.0.1 ```
- Na linha 18 definindo dns:
``` dns-nameservers 8.8.8.8 8.8.4.4 ```

- Depois que estiver tudo correto fechamos o vi 
``` :wq ``` -> write quit
- Reiniciar o servidor com systemctl reboot

- Verificar se o IP realmente mudou 
 ``` ip a ```
- Verificar se a internet está chegando e se o hospedeiro está conseguindo se comunicar com a máquina virtual
``` ping www.google.com ```

- Atualizar o repositório do debian
apt update
- Instalando o editor de texto VIM
``` apt install vim ```

- Testando a comunicação entre a máquina real e a virtual
Na máquina real ping o IP da máquina virtual

Para instalar o tomcat é necessario ter o Java instalado
- ``` apt install default-jdk ``` -> instala o jdk
- ``` java -version ``` -> versão do java
- ``` javac -version ``` -> versão da máquina virtual java
- quando instalamos o jdk no debian as variáveis de ambiente já vem configuradas

Instalando o Servidor tomcat
- ``` apt install tomcat9 ``` -> instala o tomcat v9
- ``` systemctl status tomcat9 ``` -> verifica o status
-  tecla "q" para sair do verificador de status
- Testando o tomcat na máquina real
No nagevador apontado para o IP do servodor e a porta 8080

Entrando na raiz do servidor tomcat
- ``` cd /var ```
- ``` cd lib ```
- ``` cd tomcat9 ```
- ``` cd webapps ```
- ``` cd ROOT ```
- É dentro do diretório ROOT que hospedamos os sites´

Administrando o tomcat com interface gráfica
- ``` apt install tomcat9-admin tomcat9-examples tomcat9-docs ```
- ``` cd /etc/tomcat9 ```
- ``` cp tomcat-users.xml tomcat-users.xml.bkp ```
- ``` vim tomcat-users.xml ```
- ``` tecla "Esc" :set number ```
- Na linha 21 e apertar a tecla "o" -> pula uma linha e ativo o modo inserção
- ``` <user username="admin" password="admin" roles="manager-gui, admin-gui" /> ```
- Finalizando tecla "Esc" :wq tecla "enter"
- ``` systemctl restart tomcat9 ``` -> reinicia o servidor tomcat9

- ``` 192.168.0.2:8080/docs ```
- ``` 192.168.0.2:8080/examples ```
- ``` 192.168.0.2:8080/manager/html ``` -> UI gerencia o tomcat

Comando java que exibe o IP do cliente 
- ``` request.getRemoteHost() ```

Adicionando o repositório do MySQL
- apt install gnupg -> gerenciamento das chaves
- No site do MySQL na sessão MySQL Community (GPL) Downloads »
- ``` MySQL APT Repository ```
- Copiamos o link direto do download
- Copie o link para um bloco de notas para facilitar
- No terminal do servidor colocamos o seguinte comando: 
wget <url do download direto aqui> 
- ``` dpkg -i <nome do arquivo> ``` -> instala o pacote
- instalar tudo padrão tecla "tab" seleciona e tecla "enter" próximo

dpkg: aviso: ‘ldconfig’ não foi encontrado em PATH ou não é executável
dpkg: aviso: ‘start-stop-daemon’ não foi encontrado em PATH ou não é executável
dpkg: erro: 2 programas esperados não foram encontrados em PATH ou não são executáveis
Nota: a PATH do root normalmente deve conter /usr/local/sbin, /usr/sbin e /sbin

Esse erro ocorre quando o dpkg não encontra o comando ldconfig, que é necessário para fazer seus procedimentos. Ou seja você precisa fazer seu PATH identificar a localização do ldconfig.

Esse software está dentro da pasta /sbin, e como você e eu vamos notar o /sbin realmente não vai estar apontado corretamente no PATH

Para resolver esse problema e bem simples.

Edite o arquivo com o seu editor de texto favorito, no meu caso vou usar o vim

- ``` vim /etc/profile ```
- Basta colocar /sbin após “games“, ficando como o exemplo a baixo
- ``` PATH="/usr/local/bin:/usr/bin:/bin:/usr/games/sbin" ```
- Salve e Atualize o arquivo
- source /etc/profile -> atualiza o arquivo
- fonte da solução: https://relatosti.com.br/2021/08/resolvendo-erro-no-terminal-dpkg-aviso-ldconfig-nao-foi-encontrado-em-path/

Atualizar o repositório e instalar o MySQL
- ``` apt update ```
- ``` apt install mysql-server ```
- Criar uma senha para o root do MySQL(Não tem nada havar com o root da máquina)
- ``` mysql -V ``` -> verifica a versão do MySQL
- ``` systemctl status mysql ``` -> verifica o status
- tecla "q" para sair

Reforçando a segurança no banco de dados
- mysql_secure_installation

Criando usuário para acessar o mysql remotamente
- ``` mysql -u root -p ```
- ``` CTRL + L ``` -> limpa o console
- ``` select user, host from mysql.user; ``` -> lista os usuários do mysql
- ``` create user 'user'@'%' identified by 'password'; ```
- ``` user ``` -> nome do novo usuário sem espaço e tudo minúsculo
- ``` % ``` -> significa que o usuário vai poder acessar o banco de qualquer lugar
- ``` password ``` -> depende do nível de segurança escolhido nos passos anteriores
- ``` flush privileges; ``` -> Atualiza as alterações sem precisar reiniciar o banco de dados

 Dando previlégios ao usuário para administrar qualquer banco de dados
 - grant all privileges on *.* to 'user'@'%';
 - O primeiro * significa todos os bancos de dados
 - o segundo * significa todas as tabelas
 - CTRL + D -> sai do console do mysql
 
 Instalando uma ferramenta no windows para administrar remotamente o bando de dados
 - MySQL WorkBench
 - Crie uma nova conexão no workbench
 - Coloque as informações do servidor
 
 Hosts Virtuais
 - O servidor web dinâmico permite hospedar vários projetos e associar cada projeto a um dominio. Ex:``` aplicativo1.com ``` ``` aplicativo2.com ```
- São dominios ficticios. Em um projeto real apontaria os domonios registrados para o IP da VPS que tem o servidor tomcat instaldo.
- sempre fazer uma cópia antes de mexer nos arquivos chaves do linux
- ``` cp server.xml server.xml.bkp ```
- Dentro de /etc/tomcat9 editar o arquivo server.xml 
- ``` vim server.xml ```
-  ``` Esc + :set number ```
-  Na linha 70 ``` port="80" ``` -> não precisa colocar a porta :8080 para acessar o servidor
- Salvar e sair
- ``` systemctl restart tomcat9 ``` -> reiniciar o servidor tomcat
Fazendo o windows apontar para os dominios
- Abrir o notepad como admin
- ``` arquivo ```
  -- ``` abrir ``` 
  --- ``` Disco Local C: ``` 
  ---- ```  Windows ```
  ----- ``` System32 ```
  ------ ``` drivers ```
  ------- ``` etc ```
- Mudar para poder ver ``` todos os arquivos ```
- Editar o arquivo ``` hosts ```
- Ir até o final do documento
-  Coloque o IP onde está o servidor e o dominio. 
- Ex: ``` 192.168.0.2 aplicativo1.com ```
- tecla ``` Enter ``` -> para pular uma linha
- ``` 192.168.0.2 aplicativo2.com ```

Fazendo o servidor servir páginas diferentes para cada dominio
- ``` cd /var/lib/tomcat9 ```
- ``` cp -R webapps aplicativo1 ``` -> ```cp -R``` copia todo conteúdo de forma recursiva
- ``` cp -R webapps aplicativo2 ```
- Romover todos os arquivos dentro de ``` ROOT/ ``` e deixar apenas o ``` META-INF ``` nos dois novos diretórios
-  Criar um ``` index.html ``` simples para os dois novos diretórios
- Redirecionando os arquivos
- ``` cd /etc/tomcat9 ```
- ``` vim server.xml ```
- Na linha 151 tem a primeira tag ``` Host ```
- Na linha de fechamento da tag ``` Host ```
- Tecla ``` o ``` para pular uma linha e abrir o modo inserção
- A nova tag ficará assim:
- Aplicativo 1
- ``` <Host name="aplicativo1.com" appBase="aplicativo1" unpackWARs="true" autodeploy="true"></Host> ```
- Aplicativo 2
- ``` <Host name="aplicativo2.com" appBase="aplicativo2" unpackWARs="true" autodeploy="true"></Host> ```
- Salvar e sair
- ``` systemctl restart tomcat9 ``` -> reiniciar o servidor tomcat
- ``` systemctl status tomcat9 ``` -> verifica se está tudo certo com o servidor
- Tecla ``` q ``` -> Para sair
- Pronto agora as páginas estão sendo redirecionadas pelo dominio
