
### UNIX shell e o Terminal

##### GUI x CLI
Algo muito comum de acontecer com estudantes no final da graduação ou recém-ingressados na pós é a grande frustração ao primeiro contato com uma linguagem de programação, especialmente o popular **R**, pela falta de familiarização com outras interfaces similares.
O R é uma linguagem usada para testes estatísticos, o que explica sua popularidade entre os cientistas naturais. Normalmente essa linguagem é utilizada através do programa do mesmo nome, que apresenta uma *interface de linha de comando* (ou **CLI**, do inglês *command-line interface*), diferente de uma interface **GUI**, uma *graphical user interface*, na qual o usuário clica nos comandos que deseja realizar.

<img src="images/console.png" width="400">
<sub>
Interface típica do R, uma *command-line interface*.</sub>


A interface CLI do R, como é observável na figura, apresenta um *prompt*, identificável pelo símbolo ">" abaixo do texto. Esse *prompt* indica que o programa está pronto para receber um comando digitado pelo usuário. No texto da figura, vemos que podemos escrever, por exemplo, 'help()' para obter ajuda ou 'q()' para sair do R. Nosso foco aqui não é aprender a usar o R ou qualquer linguagem específica (apesar de que vamos ver exemplos de algumas linguagens), mas é fundamental entender o funcionamento da CLI para prosseguirmos no tutorial. **No começo, muitos usuários estranham o uso de uma CLI, porém com o tempo é fácil perceber como ela torna muito mais rápida a entrada de comandos que podem ser usados para diversas funções.**

[](Penso que seria mais interessante aqui colocar uma imagem do Spyder, ao invés do Anaconda. (talvez possas falar disso no capítulo das IDEs)
[]( Com o Anaconda Navigator se pode abrir múltiplas GUIs (Rstudio, SPyder, Jupyter, etc).

<img src="images/navigator.png" width="400">
<sub>
Exemplo de uma GUI simples, o *Anaconda Navigator*.</sub>

##### Introduzindo a shell
"A UNIX shell existe há mais tempo do que muitos de seus usuários. Isto por que ela é uma ferramenta tão poderosa e simples de utilizar, permitindo o usuário executar tarefas complexas com apenas algumas teclas."<sup>1 (Tradução livre do autor)</sup>

A versão mais popular da UNIX shell é a bash (Bourne Again SHell), que é uma CLI muito popular entre usuários de Linux através do programa **Terminal**, incorporado ao sistema OS X da Apple. Isto e outras características conferem uma certa similaridade em alguns aspectos desses sistemas operacionais. Há grande chance que você, leitor ou leitora, seja usuário de Windows, pois sua grande popularidade condicionou muitos usuários à utilizarem-no durante a vida toda, e sentirem-se desconfortáveis com outro sistema. Mas não se desespere! Se esse for o caso, você ainda pode ~~desinstalar o Windows agora e instalar o Linux~~ baixar uma outra versão do Terminal e fazer as mesmas coisas.

<img src="images/terminal.png" width="400">
<sub>
Console do Terminal do OS X. Note o "$" indicando o *prompt*. O Terminal é um programa para executar comandos bash.</sub>

Para quem é averso a essas nerdices, digitar comandos no Terminal é quase como entrar na Matrix, ainda mais se houver um fundo preto e letras verdes fluorescentes. Porém, ele é uma ferramenta informática **básica** para muitas funções, como editar e gerenciar arquivos, executar scripts, acessar servidores remotos e ambientes virtuais, entre outras funções. É imensamente útil sentir-se à vontade utilizando o Terminal e logo percebe-se o porquê. Agora, veremos um pouco dos comandos básicos do Terminal e como ele será útil no futuro.

<sub><sup>1</sup>[Aula de shell do Software Carpentry](http://swcarpentry.github.io/shell-novice/)</sub>

---
