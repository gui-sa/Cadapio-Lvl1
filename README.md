# Cardapio-Lvl1
Esse repositório cria um cardápio nível básico: em uma pagina estática sem banco de dados com HTML, CSS e JS. O backend é um container Apache.

*******
Tabelas de conteúdo
 - [Sobre o Site](#sobre)
 - [Desenvolvimento em Container](#devcont)
 - [Pull-Requests e Contribuições](#contrib)

*******
<div id='sobre'/>

## Sobre o Site:
 - Barra de navegação acompanha a rolagem de tela
 - Ao clicar no link de navegação ele rola a tela rapidamente até o ponto desejado
 - Ainda não é responsivo mas esta planejado.

![image](https://user-images.githubusercontent.com/58073678/234885696-2121977d-3c21-4aea-ada4-92152b768d8e.png)
![image](https://user-images.githubusercontent.com/58073678/234885923-7a4281a1-9aa2-4049-8bce-2427cc896acc.png)
![image](https://user-images.githubusercontent.com/58073678/234886018-ba4baf0c-1252-4c2a-85e4-cbeece2e2022.png)

<div id='devcont'/>

## Desenvolvimento em Container:

O desenvolvimento será realizado usando um volume com referencia no **diretorio raíz desse git**.

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
 6. [Acessar aplicação local](http://localhost:80)
 7. Para desligar o servidor rode:
 ~~~
 docker-compose down
 ~~~
 
Utilize com sabedoria :wink:

![image](https://user-images.githubusercontent.com/58073678/234886237-7c940279-5726-425a-a8bd-a7bb3edd5c3f.png)

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
