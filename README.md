## SnakeUbuntu
This is a repository that contains a classic snake game version created using c and compiling the code in ubunto using the gcc compiler.
It utilizes the aid of the CLI-lib to recieve inputs from the user's keyboard and to have a timer. Since it doesn't compile in windows, we made a game that compiled in linux/Mac

--------------------------------------------------------------------------------------------
 ## Colaboradores 

Isabela Spinelli  (bela975 on github) <br/>
Maria Julia Pessoa (mariajuliapessoa on github) <br/>
Nicolas Sena (nicolasSenna on github) 

-------------------------------------------------------------------------------------------
## Bibliotecas utilizadas
### CLI-LIB
cli-lib : https://github.com/tgfb/cli-lib/blob/main/README.md

Cli-lib é uma biblioteca desenvolvida para a realização de aplicações e jogos em C, e com ela,
iremos gerenciar as telas do jogador e as entradas através do periférico do teclado.

Para utilizá-la, só precisamos pegar os arquivos de código-fonte (source) e cabeçalho
(header) deste repositório e adicioná-los ao nosso programa, substituindo o main 
neste repositório pelo nosso próprio.

------------------------------------------------------------------------------------------
## Requisitos
A biblioteca cli-lib funciona nos seguintes sistemas operacionais: <br/>
      Baseados em Linux (Ubuntu, etc)<br/>
      MacOS<br/>
Portanto, é necessário ter o GCC instalado para poder desenvolver o jogo.

-------------------------------------------------------------------------------------------
## Como executar e compilar nosso jogo? 
É preciso estar no sistema operacional Linux!
Nosso jogo foi feito no terminal do linux. Por isso, para compilá-lo é necessário instalar
o GCC.

bibliotecas do projeto:
Para construir a interface do nosso jogo e pegar os inputs dos periféricos dos usuários, 
contamos  com o auxílio das biblioteca cli-lib.

##OBSERVAÇÃO <br/>
como subimos esse código via windows para o vs code, o git ajusou para ficar de acordo com o SO e trocou o caracter LF (Linefeed ch em LINUX) para CRLF (carriage return lineFeed usado em Windows). Certifique-se de que seu sistema está usando o correto ao executar no linux.<br/>
Não dá para executar esse jogo em windows.

-------------------------------------------------------------------------------------------
## Como instalar a biblioteca cli-lib?
Para utilizá-la, é necessário somente pegar os source e o header file desse repositório 
e juntar ao nosso programa, trocando a main desse repositório pela nossa main.

--------------------------------------------------------------------------------------------

## Executando o jogo:
1. Faça o download da pasta do jogo no github e extraia ela (Commit mais recente)
   
2.  Após baixar a pasta, dentro dela, clique com o botão direito em executar terminal como administrador.
 
3. Com o terminal aberto, no Linux, certifique-se de que você está na pasta do projeto, caso necessário, use “cd” e o nome da pasta do jogo em seu computador. “cd SnakeUbuntu” por exemplo.

4. após entrar nela, no terminal, com o gcc instalado claro, é só inserir o comando “gcc main.c -o main” e logo após essa execução inserir o comando  “./main” .
Pronto! O jogo já estará em execução.
 
5. Nosso código já está com os arquivos necessários oriundos da CLI-Lib, então não precisa se preocupar com importar nada dela.


