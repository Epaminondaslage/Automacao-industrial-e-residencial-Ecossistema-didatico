<td style="width: 20%;"><img src="/img/Logo_CEFET-MG.png" width="20%" /></td>
<p><strong><span style="color: #0000ff;">Automação industrial e residencial</span></strong></p>
<p><strong><span style="color: #0000ff;">Ecossistema didático com Open Software e Open Hardware</span></strong></p>
<p><strong><span style="color: #0000ff;">Prof Epaminondas Lage</span></strong></p>
<a href="http://lattes.cnpq.br/7787341723868111"> Currículo Lattes LAGE, E. S.</a> 

<td style="width: 50%;"><img src="/img/Ecossistema-Open-Automação.png" width="50%" /></td>

# Índice 

* [Introdução](#Introdução)
* [Sistema Operacional Linux](#Sistema-Operacional-Linux)
* [Kit didáticos](#Kit-didáticos)
* [Programando os microcontroladores](#Programando-os-microcontroladores)
* [ScadaBR](#ScadaBR)
* [SCILab](#SCILab)
* [MBLogic](#MBLogic)
* [Status do Projeto](#Status-do-Projeto)
* [Referências](#Referências)

# Introdução

A utilização de sistemas reais em ambiente acadêmico nem sempre é aplicável devido a fatores como a dimensão do espaço físico ou dos aquipamentos, características técnicas, requisitos elétricos, condições de segurança física e o custo e disponibilidade de recursos financeiros associado a estes tipos de montagens. Assim e para superar estas condicionantes, opta-se a kits didáticos, que são desenvolvidos de forma a terem um funcionamento semelhante aos sistemas reais.

Neste contexto kits didáticos podem ser entendidos como uma complementação acadêmica tendo como objetivo o desenvolvimento da capacidade do aluno de aplicar na prática os conhecimentos teóricos adquiridos, ampliando sua percepção da realidade e compreensão dos conceitos sobre os quais irá atuar ao longo de sua carreira profssional. Essas práticas laboratoriais incentivam o aprendizado ativo, em que pode-se ter separação de tarefas e responsabilidades entre os alunos em grupos, no qual o objetivo final é o trabalho em equipe. Tendo foco na área de controle e automação,seja ela residêncial ou industrial reconhecem-se alguns modelos de kits didáticos podem serem utilizados em laboratórios com grande sucesso.

No caso do CEFET-MG, por anos os professores e técnicos administrativos envolvidos, sempre apoiaram o ensino disponibilizando projetos hardware, código e tutoriais para que os alunos desenvolvam suas aptidões semelhante ao que acontece no ambiente industrial ou residêncial. É o caso da plataforma abordada neste trabalho, o OrangePi One, Arduino, Esp32 e Esp8266. Estes ou outras plataforma micro controlada de prototipagem tem como objetivo controlar ou automatizar alguma atividade. O termo automação pode ser defnido como um processo onde são realizadas várias operações com o auxílio de diversos dispositivos eletrônicos e/ou mecânicos que controlam os seus próprios processos. Neste contexto, a automação seja ela residencial ou industrial é a aplicação de técnicas, softwares e/ou equipamentos específcos numa determinada máquina ou processo industrial, assim como um ambiente doméstico com o objetivo de aumentar a sua efciência com o menor consumo de energia e/ou materias.

Este projeto disponibiliza aos alunos conteúdos, manuais, tutoriais e kits para laboratórios que propiciam aos alunos projetar, montar e testar seus conhecimentos visando despertar a curiosidade em aprimorar tantos os aspectos teóricos quanto práticos na área de automação residêncial, industrial e Internet das coisas, além de propor atividades laboratoriais de acionamento e controle que exploram conceitos desenvolvidos em salas de aula. Os sistemas propostos permitem modelagem, análise, projeto e teste de sistemas de controle variados em ambientes que podem ser virtuais ou reais em escalas reduzidas.

As Linguagens de programação nada mais são do que conjuntos de instruções padronizadas para que um computador entenda determinados comandos, ou seja, torne-se uma máquina capaz de processar e até armazenar dados. Elas estão cada vez mais próximas do nosso cotidiano, muitas vezes sem percebermos.

Na automação industrial, que além do hardware existe uma outra componente importante, o software. O software desenvolve tarefas de programação e controle e gerenciamento de hardware por meio de linguagens específcas. Linguagens de programação para a automação industrial foram padronizadas por meio da norma IEC 61131-3, publicada pela Comissão Eletrônica Internacional (IEC), que defne um conjunto de normas e especifcações técnicas com o objetivo de padronizar os autômatos programáveis. Desde sua primeira edição, publicada em 1993, que de forma simplificada, a norma IEC 61131-3 sugere a padronização de boas práticas para o desenvolvimento de programas de CLPs, visando qualidade e economia de tempo durante as fases de desenvolvimento e testes e é esta vertente que utilizaremos neste projeto.

Linguagem de programação em sistemas embarcados tais como Arduino, ESP8266 e ESP32  tem sua IDE escrita em Java/C++. Para a programação do OrangePi utiliza-se o C, Python, que conta com várias bibliotecas específicas, além Shell script em Linux. Cada uma é utilizada  em diversos projetos de automação conforme sua necessidade.

Nestes repositórios, serão explanados os projetos e construção de dois núcleos (shield's). O primeiro que irá converter a plataforma OrangePi One em um controlador lógico programável com funcionalidades básicas (Figura 1) e o segundo contendo microcontroladorres, tais como Arduino Uno R3, ESP 8266, Wemos D1, ESP32,(Figura 2) que serão integrados com end-point de hardware aberto ao primeiro kit ou como desenvolvimento de projetos de automação residêncial e de IoT. Esses protótipos, auxiliado por software open-source, possibilita criar um ambiente versátil para controle e automação industrial e residencial assim como o acesso a sensores amplamente utilizados no ambiente de IoT. A metodologia proposta visa explorar os principais conceitos de eletrônica básica, programação de códigos de controle, comunicação entre dispositivos e análise de dados. 

<table style="border-collapse: collapse; width: 100%;" border="1">
<tbody>
<tr>
<td style="width: 50%;"><img src="/img/kit openplc.png" alt="" width="400" height="300" /></td>
<td style="width: 50%;"><img src="/img/kit_iot.png" alt="" width="400" height="300" /></td>
</tr>
<tr>
<td style="width: 50%;">Figura 1: Kit SBC Linux</td>
<td style="width: 50%;">Figura 2: Kit IoT</td>
</tr>
</tbody>
</table>

# Sistema Operacional Linux

O Orange Pi, que é mais uma SBC (Single-Board Computers) disponibilizada no mercado, conta com um processador ARM e pode ser utilizada com varias distribuições do sistema operacional GNU/Linux. Utilizando o SO de código aberto (opensource) Linux, podemos fazer praticamente qualquer coisa com o Orange Pi. Como um computador, servidor para pequenas aplicações, servidor doméstico (automação residencial), videogame retrô, central de mídia (filmes, músicas, etc) e é claro um PLC.

<table border="0">
<tbody>
<tr>
<td><img style="display: block; margin-left: auto; margin-right: auto;" src="/img/SO.png" width="40%" /></td>
</tr>
<tr>
<td style="text-align: center;">Figura 3: SO Linux do SBC.</td>
</tr>
</tbody>
</table>

Nos nossos kits optamos em utilizar o Ubuntu para a programação em Shell Script e o Debian para a instalação do OpenPLC runtime.

## Repositórios Disponíveis

* <a href="https://github.com/Epaminondaslage/SO_Ubuntu_SBC_OrangePI">SO Ubuntu SBC OrangePI</a> 
* <a href="https://github.com/Epaminondaslage/SO-Debian-SBC-OrangePI">SO Debian SBC OrangePI</a>   

# Kit didáticos

## Kit IoT

asbdsjkdhjkshjdhjkshjkdhkjsd
sdsdsdsdsdssdsd

## Kit SBC Linux

## Repositórios Disponíveis  

* <a href="https://github.com/Epaminondaslage/Kit-IoT">Kit Internet das Coisas (IoT)</a> 
* <a href="https://github.com/Epaminondaslage/Kit-SBC-Linux">Kit SBC Linux</a> 

# Programando os microcontroladores

## Scripts em shell nas SBC's

Um script nada mais é do que um algoritmo projetado para realizar uma determinada tarefa, utilizando os comandos específicos do bash e os executáveis do sistema operacional. Um shell é um programa que permite que o usuário se comunique diretamente com o sistema operacional. Ele recebe e interpreta comandos enviados pelo operador ao Kernel — outro programa que gerencia todas as comunicações para o hardware — para que a ação desejada possa ser executada.

O Bourne Again Shell ou bash, para abreviar, é um shell do Unix, mas também é uma linguagem de programação capaz de realizar diversas tarefas que ajudam a economizar tempo e energia.

Assim como ocorre com outras linguagens de script, o bash permite que "softwares-pai" recebam aprimoramentos constantes de forma prática. Além dessa função básica, também é possível realizar diversas configurações de software e extrair dados.

Em resumo, as principais aplicações dessa linguagem são:

    * manipular arquivos;
    * monitorar o sistema operacional;
    * realizar automação de processos de compilação de código;
    * executar backups de rotina;
    * vincular programas existentes;
    * realizar lotes de conclusão;
    * criar ambientes para programas;
    * executar programas
    * Acionar GPIO's.

##  Editor OpenPLC

O Editor OpenPLC é o software que roda em seu computador (Windorws, Mac ou Linux) usado para criar programas para o PLC. É muito simples de usar e suporta todas as cinco linguagens definidas no padrão IEC 61131-3: Ladder Logic (LD), Function Block Diagram (FBD), Instruction List (IL), Structured Text (ST) e Sequential Function Chart ( SFC).

## IDE Arduino

O Arduino IDE é o software Arduino gratuito que facilita o desenvolvimento e a gravação de códigos diretamente no microcontrolador. Através deste, é possível realizar o Upload dos códigos para a placa tanto em sistemas operacionais Windows quanto Linux, demonstrando sua funcionalidade e versatilidade.

As funções da IDE do Arduino são basicamente três: permitir o desenvolvimento do software, de enviá-lo à placa para que possa ser executado e de interagir com a placa Arduino.

No Repositóriorio "PPT das Aulas de Programação Arduino" encontra-se os slides do Curso básico de programação com Arduíno ministrado na Disciplina Informática Aplicada , em caráter adicional ao programa do curso.

Um projeto no Arduino é chamado de sketch, e consiste tipicamente em duas partes (rotinas): a rotina de setup, que inicializa o sketch, e a rotina de loop, que normalmente contém o código principal do programa (é como a função main() da linguagem C). No Reposiótio "Sketch Arduino" disponibilizamos vários exemplos para sere utilizados pelos alunos.


## Repositórios Disponíveis   

* <a href="https://github.com/Epaminondaslage/Shell-Script-em-Linux">Shell Script em Linux</a>
* <a href="https://github.com/Epaminondaslage/OpenPLC">OpenPLC Editor</a>
* <a href="https://github.com/Epaminondaslage/Kit-IoT/tree/master/material_didatico/ppt_de_aulas">PPT das Aulas de Programação Arduino</a>
* <a href="https://github.com/Epaminondaslage/Arduino-Uno">Sketch Arduino</a>

# ScadaBR



# SCILab

O Scilab é um software científico para computação numérica, de codigo aberto, semelhante ao MATLAB que fornece um poderoso ambiente computacional aberto para aplicações científicas.

Possui uma linguagem de programação de alto nível, orientada à análise numérica. A linguagem provê um ambiente para interpretação, com diversas ferramentas numéricas. Algoritmos complexos podem ser criados em poucas linhas de código, em comparação com outras linguagens como C ou C++.

## Repositório Disponível  

* <a href="https://github.com/Epaminondaslage/Lab_Inf_Aplicada">Laboratório de Informática Aplicada (IoT)</a> 


# MBLogic

# Status do Projeto

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
