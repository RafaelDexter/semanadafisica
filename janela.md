# Instalação no Windows :unamused:

No Windows :unamused: vamos precisar baixar o compilador no site do MiKTeX

* [http://miktex.org/](http://miktex.org/)

e o editor no site do Texmaker

* [http://www.xm1math.net/texmaker/](http://www.xm1math.net/texmaker/)

## Instalando o MiKTeX

No *website* do MiKTeX, optei por baixar a versão 64-bit.

![img1](https://github.com/RafaelDexter/semanadafisica/blob/master/img/miktex/01.PNG)

A primeira tela de instalação do programa são os termos e condições:

![img2](https://github.com/RafaelDexter/semanadafisica/blob/master/img/miktex/02.PNG)

Após ter lido todas as informações :smirk: e concordar com os termos, marque a opção
*`I accept the MiKTeX copying conditions`*, e clicar em *`Avançar >`* Você pode não
concordar com alguma condição e clicar em *`Cancelar`* e não instalar :laughing: 

![img3](https://github.com/RafaelDexter/semanadafisica/blob/master/img/miktex/03.PNG)

Somente para não ter problemas deixe a opção *`Anyone who uses this computer (all users)`*
marcada e clique em *`Avançar >`*.

![img4](https://github.com/RafaelDexter/semanadafisica/blob/master/img/miktex/04.PNG)

Agora o programa prucura por um diretório onde este será instalado. Não aconselho
você mudar o diretório, pois não há necessidade. Entretanto se tiver banstante
experiência... 

... se tiver bastante experinência com o Windowns então você não presisa deste
tutorial :sunglasses:

Só clique em *`Avançar >`*.

![img5](https://github.com/RafaelDexter/semanadafisica/blob/master/img/miktex/05.PNG)

Configurações (*Settings*): Em *`Preferred paper:`* ecolha `A4` e em *`Install missing packages on-the-fly:`* ecolha `Yes`, por fim clique em *`Avançar >`*.

**Nota:** *Install missing packages on-the-fly* + *Yes* siguinifica que o MiKTeX
irá baixar os pacotes :package: que estão faltando, pois o arquivo que você baixou
não possui todas elas.

![img6](https://github.com/RafaelDexter/semanadafisica/blob/master/img/miktex/06.PNG)

Neste ponto o instalador mostra um resumo das configurações escolhidas, basta clicar
em *`Start`*

![img7](https://github.com/RafaelDexter/semanadafisica/blob/master/img/miktex/07.PNG)

Enfim, o programa comecará a ser instalado em sua máquina. Este processo dependerá
da velocidade de *download* se sua *internet*.

![img8](https://github.com/RafaelDexter/semanadafisica/blob/master/img/miktex/08.PNG)

Quando este processo terminar, o botão *`Avançar >`* estará abilitado, clique neste.

![img9](https://github.com/RafaelDexter/semanadafisica/blob/master/img/miktex/09.PNG)

Finalmente, se tudo ocorreu bem, a seguinte tela será apresentada:

![img10](https://github.com/RafaelDexter/semanadafisica/blob/master/img/miktex/10.PNG)

Pronto, basta clicar em *`Close`* e seu compilador LaTeX MiKTeX está instalando :blush:

## Instalando o Texmaker

No *website* do Texmaker, baixei a versão 4.5 32-bit (até o dia que eu fiz este
tutorial não exitia uma versão 64-bit, mas isto não importa :stuck_out_tongue_closed_eyes: ).

![img1](https://github.com/RafaelDexter/semanadafisica/blob/master/img/texmaker/01.PNG)

Após ter baixado o instalador, inicie-o. A na primeira janela será a de licensa,
basta ler e clicar em *`I Agree`*, caso você concorde ou em *`Cancel`*. Você decide.

![img2](https://github.com/RafaelDexter/semanadafisica/blob/master/img/texmaker/02.PNG)

O instalador procura pelo diretório padrão, não precisa mudar. Então clique em
*`Install`*

![img3](https://github.com/RafaelDexter/semanadafisica/blob/master/img/texmaker/03.PNG)

O Texmaker comecará a ser instalado em seu computador.

![img4](https://github.com/RafaelDexter/semanadafisica/blob/master/img/texmaker/04.PNG)

Terminado o processo de instalação, o botão *`Close`* está abilitado, clique nele e
pronto, o Texmaker já está instalado!

![img5](https://github.com/RafaelDexter/semanadafisica/blob/master/img/texmaker/05.PNG)

# Testando!!!

Inicie o Texmaker e copie e cole o seguinte texto:

```tex
\documentclass[10pt,a4paper]{article}
\usepackage[utf8]{inputenc}
\usepackage[portuguese]{babel}
\usepackage[T1]{fontenc}
\usepackage{amsmath}
\usepackage{amsfonts}
\usepackage{amssymb}
\usepackage{lmodern}
\usepackage[left=2cm,right=2cm,top=2cm,bottom=2cm]{geometry}
\author{Rafael Dexter}
\title{Teste}
\begin{document}

Teste de compilação

Equação:

\begin{equation}
E = m c^{2}
\end{equation}

\end{document}
```


Ficará parecido com isso:

![img7](https://github.com/RafaelDexter/semanadafisica/blob/master/img/texmaker/07.PNG)

Salve o aquivo em qualquer lugar do seu computador. No meu caso criei um diretório
com o nome `teste` e salvei o aqruivo dentro deste com o mesmo nome que o
diretório.

![img8](https://github.com/RafaelDexter/semanadafisica/blob/master/img/texmaker/08.PNG)

Vamos ao teste :bangbang: Procure pelo botão "compilar" e clique na "seta" que
antecede-o.

![img9](https://github.com/RafaelDexter/semanadafisica/blob/master/img/texmaker/09.PNG)

O Texmaker abrirá uma nova janela (que pode estar embutida e a esqueda ou uma nova janela)
com o texto compilado. Pronto, o "LaTeX" está funcionando em seu computador.

O Texmaker cria vários documentos durante a compilação, para o caso mostrado anteriormente
os arquivos criados foram:

![img10](https://github.com/RafaelDexter/semanadafisica/blob/master/img/texmaker/10.PNG)

Você não precisa manter todos salvos. Ao final da compilação pode-se apagar os
aqruivos com as extensões `.aux` (Arquivo AUX) `.synctex`. Mas só os apague quando
tiver terminado seu trabalho ou quando algum erro não para de aparecer e você não
sabe mais o que fazer.
