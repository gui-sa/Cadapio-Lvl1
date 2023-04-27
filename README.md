# Cardapio-Lvl1
Esse repositório cria um cardápio nível básico: em uma pagina estática sem banco de dados com HTML, CSS e JS. O backend é um container Apache.

*******
Tabelas de conteúdo 
 - [Desenvolvimento em Container](#devcont)
 - [Pull-Requests e Contribuições](#contrib)

*******

<div id='devcont'/>

## Desenvolvimento em Container:

O desenvolvimento será realizado usando um volume com referencia no diretorio raíz desse git.

 1. [Instalar Docker](https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository) no seu Sistema Operacional (nesse caso usaremos versão 20.04)
 2. Instalar ferramenta *docker-compose* no seu Sistema Operacional (nesse caso usaremos a versão 3.8)
 3. Clonar este repositorio:
 ~~~
 git clone https://github.com/gui-sa/Cardapio-Lvl1.git
 ~~~
 4. Entrar no diretorio raíz desse repositorio.
 5. Docker-compose o arquivo *compose.yml*:
 ~~~
 docker-compose up -d
 ~~~
 6. [Acessar aplicação local](https://localhost:80)

Utilize com sabedoria :wink:


<div id='contrib'/>

## Pull-Requests e Contribuições

Caso queira contribuir com esse repositorio:

 1. Faça o *fork* do repositorio na nuvem do GIT
 2. Clone seu repositorio forkado para sua maquina
 ~~~
 git clone [seu_repo_fork]
 ~~~
 3. Crie uma branch nova:
 ~~~
 git checkout -b novafunc
 ~~~
 4. Faça suas alterações normalmente e dê push para a sua nuvem
 5. Na nuvem do Git realize o Pull Request explicando as alterações e levando sua nova branch para a branch master/main.

 Da mesma forma, sinta-se a vontade em abrir uma nova *ISSUE*