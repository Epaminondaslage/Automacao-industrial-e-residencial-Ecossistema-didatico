<td style="width: 20%;"><img src="/img/Logo_CEFET-MG.png" width="20%" /></td>
<p><strong><span style="color: #0000ff;">Automação industrial e residencial</span></strong></p>
<p><strong><span style="color: #0000ff;">Ecossistema didático com Open Software e Open Hardware</span></strong></p>
<p><strong><span style="color: #0000ff;">Prof Epaminondas Lage</span></strong>
<a href="http://lattes.cnpq.br/7787341723868111"> Currículo Lattes LAGE, E. S.</a></p>

<p><strong><span style="color: #0000ff;">Prof Danilo Freitas Melo</span></strong>
<a href="http://lattes.cnpq.br/3410712703972723"> Currículo Lattes MELO, D. F.</a> </p>

<td style="width: 50%;"><img src="/img/Ecossistema_Open_Automacao.png" width="60%" /></td>

# Índice 

* [Introdução](#Introdução)
* [Kit didáticos](#Kit-didáticos)
* [Sistema Operacional Linux](#Sistema-Operacional-Linux)
* [Introdução ao Shell Script no Linux](#Introdução-ao-Shell-Script-no-Linux)
* [Automação Industrial](#Automação-Industrial)
* [Automação Residencial](#Automação-Residencial)
* [IDE Arduino](#IDE-Arduino)
* [SCILab](#SCILab)
* [Status do Projeto](#Status-do-Projeto)
* [Referências](#Referências)

# Introdução

A utilização de sistemas reais em ambiente acadêmico nem sempre é aplicável devido a fatores como a dimensão do espaço físico ou dos aquipamentos, características técnicas, requisitos elétricos, condições de segurança física e o custo e disponibilidade de recursos financeiros associado a estes tipos de montagens. Assim e para superar estas condicionantes, opta-se a kits didáticos, que são desenvolvidos de forma a terem um funcionamento semelhante aos sistemas reais.

Neste contexto kits didáticos podem ser entendidos como uma complementação acadêmica tendo como objetivo o desenvolvimento da capacidade do aluno de aplicar na prática os conhecimentos teóricos adquiridos, ampliando sua percepção da realidade e compreensão dos conceitos sobre os quais irá atuar ao longo de sua carreira profssional. Essas práticas laboratoriais incentivam o aprendizado ativo, em que pode-se ter separação de tarefas e responsabilidades entre os alunos em grupos, no qual o objetivo final é o trabalho em equipe. Tendo foco na área de controle e automação,seja ela residêncial ou industrial reconhecem-se alguns modelos de kits didáticos podem serem utilizados em laboratórios com grande sucesso.

No caso do CEFET-MG, por anos os professores e técnicos administrativos envolvidos, sempre apoiaram o ensino disponibilizando projetos hardware, código e tutoriais para que os alunos desenvolvam suas aptidões semelhante ao que acontece no ambiente industrial ou residêncial. É o caso da plataforma abordada neste trabalho, o OrangePi One, Arduino, Esp32 e Esp8266. Estes ou outras plataforma micro controlada de prototipagem tem como objetivo controlar ou automatizar alguma atividade. O termo automação pode ser defnido como um processo onde são realizadas várias operações com o auxílio de diversos dispositivos eletrônicos e/ou mecânicos que controlam os seus próprios processos. Neste contexto, a automação seja ela residencial ou industrial é a aplicação de técnicas, softwares e/ou equipamentos específcos numa determinada máquina ou processo industrial, assim como um ambiente doméstico com o objetivo de aumentar a sua efciência com o menor consumo de energia e/ou materias.

Este projeto disponibiliza aos alunos conteúdos, manuais, tutoriais e kits para laboratórios que propiciam aos alunos projetar, montar e testar seus conhecimentos visando despertar a curiosidade em aprimorar tantos os aspectos teóricos quanto práticos na área de automação residêncial, industrial e Internet das coisas, além de propor atividades laboratoriais de acionamento e controle que exploram conceitos desenvolvidos em salas de aula. Os sistemas propostos permitem modelagem, análise, projeto e teste de sistemas de controle variados em ambientes que podem ser virtuais ou reais em escalas reduzidas.

As Linguagens de programação nada mais são do que conjuntos de instruções padronizadas para que um computador entenda determinados comandos, ou seja, torne-se uma máquina capaz de processar e até armazenar dados. Elas estão cada vez mais próximas do nosso cotidiano, muitas vezes sem percebermos.

Na automação industrial, que além do hardware existe uma outra componente importante, o software. O software desenvolve tarefas de programação e controle e gerenciamento de hardware por meio de linguagens específcas. Linguagens de programação para a automação industrial foram padronizadas por meio da norma IEC 61131-3, publicada pela Comissão Eletrônica Internacional (IEC), que defne um conjunto de normas e especifcações técnicas com o objetivo de padronizar os autômatos programáveis. Desde sua primeira edição, publicada em 1993, que de forma simplificada, a norma IEC 61131-3 sugere a padronização de boas práticas para o desenvolvimento de programas de CLPs, visando qualidade e economia de tempo durante as fases de desenvolvimento e testes e é esta vertente que utilizaremos neste projeto.

Na  automação residencial um fator relevante é a escolha de plataformas de código aberto. Elas capacitam os usuários a controlar e monitorar dispositivos e serviços em suas residências. Neste projeto optou-se pelo Home Assistant sendo que este atua como um hub de automação, fornecendo suporte para uma ampla variedade de dispositivos e integrações.

Ao adotar plataformas os usuários podem integrar e gerenciar dispositivos populares, como lâmpadas inteligentes, termostatos, câmeras de segurança, fechaduras de portas e sensores de movimento. Através de uma interface web intuitiva ou de aplicativos móveis dedicados, eles têm o controle completo sobre esses dispositivos sejam elas locais ou em serviços de nuvem.

Essa plataforma permite personalizar e automatizar tarefas residenciais, proporcionando conveniência e eficiência aos usuários. Por exemplo, é possível programar as luzes da casa para ligar automaticamente ao anoitecer, ajustar a temperatura do termostato quando a família estiver chegando em casa ou receber notificações em tempo real sobre eventos de segurança.

No ítem Linguagem de programação em sistemas embarcados tais como Arduino, ESP8266 e ESP32  tem sua IDE escrita em Java/C++. Para a programação do OrangePi utiliza-se o C, Python, que conta com várias bibliotecas específicas, além Shell script em Linux. Cada uma é utilizada  em diversos projetos de automação conforme sua necessidade.
 
# Kit didáticos

## Kit IoT

O KIT IoT foi concebido para o aprendizado básico do microcontrolador Arduino, Wemos D1 e Esp32 utilizando sensores diversos. Reuniu-se 37 sensores e módulos básicos para que estes consigam captar inumeros fenômenos físicos e químicos. Neste kit, existem sensores/atuadores digitais e analógicos e também alguns módulos especiais, como ultrassom, Bluetooth, módulo de aceleração, WIFI, entre outros.

Para cada sensor, desenvolveu-se um diagrama de conexão e um código de exemplo. Portanto, mesmo o aluno seja totalmente novo, ele pode começar facilmente. Os códigos de exemplo para este kit de sensores são baseados no ARDUINO, porque é de código aberto e fácil de usar. Caso o aluno tenha conhecimentos prévios, também pode aplicar este kit a outras plataformas de desenvolvimento de outros MCU e embarcados.

Este Kit foi concebido para funcionar como endpoint do Kit SBC Linux.

## Kit SBC Linux

A base de sustentação para as placas do KITSBC Linux foi desenvovolvida construida em uma impressora 3D. Possui dimensões de 245x180x15 mm. Possui um slot para o OrangePi One, uma placa de ensaios tipo protoboard, um módulo de 8 relés e um módulo de 5 push-botons. O coração do Kit SBC Linux é o OrangePi One. O Orange Pi, que é mais uma SBC (Single-Board Computers) disponibilizada no mercado, conta com um processador ARM e pode ser utilizada com varias distribuições do sistema operacional GNU/Linux. Foi gerado duas versões de sistemas operacionais Linux (Ubuntu e o Debian)para serem utilizados conforme a aplicação. 

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

## Repositórios Disponíveis  

* <a href="https://github.com/Epaminondaslage/Kit-IoT">Kit Internet das Coisas (IoT)</a> 
* <a href="https://github.com/Epaminondaslage/Kit-SBC-Linux">Kit SBC Linux</a>

# Sistema Operacional Linux

O Orange Pi é uma Single-Board Computer (SBC), disponível no mercado, que possui um processador ARM e é compatível com várias distribuições do sistema operacional GNU/Linux. Com o uso do sistema operacional de código aberto Linux, o Orange Pi oferece uma ampla gama de possibilidades de uso. Ele pode ser utilizado como um computador completo, servidor para aplicações de pequeno porte, servidor doméstico para automação residencial, videogame retrô e central de mídia para filmes, músicas, entre outros.

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

Nos nossos kits optamos em utilizar o Ubuntu para a programação em Shell Script e o Debian.

## Repositórios Disponíveis

* <a href="https://github.com/Epaminondaslage/SO_Ubuntu_SBC_OrangePI">SO Ubuntu SBC OrangePI</a> 
* <a href="https://github.com/Epaminondaslage/SO-Debian-SBC-OrangePI">SO Debian SBC OrangePI</a>  

# Introdução ao Shell Script no Linux

## Scripts em shell nas SBC's

Um script nada mais é do que um algoritmo projetado para realizar uma determinada tarefa, utilizando os comandos específicos do bash e os executáveis do sistema operacional. Um shell é um programa que permite que o usuário se comunique diretamente com o sistema operacional. Ele recebe e interpreta comandos enviados pelo operador ao Kernel — outro programa que gerencia todas as comunicações para o hardware — para que a ação desejada possa ser executada.

O Bourne Again Shell ou bash, para abreviar, é um shell do Unix, mas também é uma linguagem de programação capaz de realizar diversas tarefas que ajudam a economizar tempo e energia. Assim como ocorre com outras linguagens de script, o bash permite que "softwares-pai" recebam aprimoramentos constantes de forma prática. Além dessa função básica, também é possível realizar diversas configurações de software e extrair dados.

Uma vantagem do shell script é que ele pode ser facilmente combinado com outros comandos e utilitários do Linux. Isso permite que os usuários aproveitem a vasta gama de recursos disponíveis no sistema operacional e em suas ferramentas de linha de comando.

Além disso, o shell script também oferece suporte a recursos avançados, como funções, expressões regulares, redirecionamento de entrada/saída, processamento de sinais e manipulação de arquivos. Isso torna a programação shell script uma opção poderosa para automação e tarefas mais complexas.

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

## Repositórios Disponíveis  

* <a href="https://github.com/Epaminondaslage/Shell-Script-em-Linux">Shel Script em Linux</a> 
    

# Automação Industrial

A automação industrial refere-se à aplicação de tecnologia e sistemas para controlar e operar máquinas e processos industriais de forma automatizada. Ela utiliza sensores, atuadores, controladores e software para substituir ou complementar a intervenção humana, visando melhorar a eficiência, a precisão, a segurança e a produtividade nas indústrias.

Um projeto notável nesse contexto é o OpenPLC. O OpenPLC é um projeto de código aberto que oferece uma plataforma flexível e acessível para a implementação de automação industrial baseada em software e hardware abertos. Ele permite a criação e personalização de controladores lógicos programáveis (PLCs) de acordo com requisitos específicos.

O OpenPLC emprega o conceito de software PLC, em que o software é executado em um computador ou dispositivo em vez de um hardware dedicado. Ele é compatível com várias plataformas, incluindo Linux, Windows e Raspberry Pi, oferecendo flexibilidade na escolha do ambiente de execução.

O Editor OpenPLC é o software que roda em seu computador (Windorws, Mac ou Linux) usado para criar programas para o PLC. É muito simples de usar e suporta todas as cinco linguagens definidas no padrão IEC 61131-3: Ladder Logic (LD), Function Block Diagram (FBD), Instruction List (IL), Structured Text (ST) e Sequential Function Chart ( SFC).

## Repositórios Disponíveis  

* <a href="https://github.com/Epaminondaslage/OpenPLC">Open PLC</a>
* <a href="https://github.com/Epaminondaslage/Diagramas-de-comandos-eletricos-de-motores">Diagramas de Comandos Elétricos</a>

# Automação Residencial

A escolha de plataforma de automação residencial de código aberto que permite aos usuários controlar e monitorar dispositivos e serviços em suas casas é o mote deste projeto. Construído em torno de um núcleo central, optou-se pelo Home Assistant sendo que este atua como um hub de automação, oferecendo suporte a uma ampla gama de dispositivos e integrações.

Uma das sua principais características é a capacidade de integração com várias marcas e protocolos. Ele suporta a integração com marcas conhecidas, como Philips Hue, Nest, Sonos, Amazon Echo, Google Home, Z-Wave, Zigbee, entre outras. Isso permite que os usuários reúnam todos os dispositivos e serviços em uma única plataforma, simplificando o controle e a automação residencial.

Com este software, os usuários podem integrar e controlar dispositivos populares, como lâmpadas inteligentes, termostatos, câmeras de segurança, fechaduras de portas, sensores de movimento e muito mais. Através de uma interface web ou de aplicativos móveis, é possível gerenciar esses dispositivos de forma conveniente. Também oferece recursos avançados de automação, permitindo aos usuários criar rotinas e cenários personalizados. Por exemplo, é possível configurar uma automação para ligar as luzes da sala de estar, ajustar a temperatura do termostato e reproduzir música ambiente quando alguém chegar em casa.

Esta plataforma possui recursos de monitoramento e notificação. Os usuários podem receber alertas quando sensores detectarem movimento, quando a temperatura estiver fora dos limites desejados ou quando uma porta for aberta. Essa funcionalidade garante que os usuários estejam sempre cientes do que está acontecendo em suas residências, mesmo quando estiverem ausentes.

## Repositórios Disponíveis

* <a href="https://github.com/Epaminondaslage/homeassistant">Home Assistant</a> 
* <a href="https://github.com/Epaminondaslage/homeassistant-ESPHome">Home Assistant - ESPHome</a> 
* <a href="https://github.com/Epaminondaslage/homeassistant-MQTT">Home Assistant - MQTT</a>
 <a href="https://github.com/Epaminondaslage/homeassistant-nodered">Home Assistant - NodeRED</a>
* <a href="https://github.com/Epaminondaslage/NodeMCU">Home Assistant - NodeMCU e MQTT>
* <a href="https://github.com/Epaminondaslage/ESP8266-e-ESPHome">Home Assistant - ESP8266 e ESPHome>
* <a href="https://github.com/Epaminondaslage/Node32-e-MQTT">Home Assistant - Node32 e MQTT>
  
## IDE Arduino

O Arduino IDE é o software Arduino gratuito que facilita o desenvolvimento e a gravação de códigos diretamente no microcontrolador. Através deste, é possível realizar o Upload dos códigos para a placa tanto em sistemas operacionais Windows quanto Linux, demonstrando sua funcionalidade e versatilidade.

As funções da IDE do Arduino são basicamente três: permitir o desenvolvimento do software, de enviá-lo à placa para que possa ser executado e de interagir com a placa Arduino.

No Repositóriorio "PPT das Aulas de Programação Arduino" encontra-se os slides do Curso básico de programação com Arduíno ministrado na Disciplina Informática Aplicada , em caráter adicional ao programa do curso.

Um projeto no Arduino é chamado de sketch, e consiste tipicamente em duas partes (rotinas): a rotina de setup, que inicializa o sketch, e a rotina de loop, que normalmente contém o código principal do programa (é como a função main() da linguagem C). No Reposiótio "Sketch Arduino" disponibilizamos vários exemplos para sere utilizados pelos alunos.

## Repositórios Disponíveis   

* <a href="https://github.com/Epaminondaslage/Kit-IoT/tree/master/material_didatico/ppt_de_aulas">PPT das Aulas de Programação Arduino</a>
* <a href="https://github.com/Epaminondaslage/Arduino-Uno">Sketch Arduino</a>

# SCILab

O Scilab é um software científico para computação numérica, de codigo aberto, semelhante ao MATLAB que fornece um poderoso ambiente computacional aberto para aplicações científicas.

Possui uma linguagem de programação de alto nível, orientada à análise numérica. A linguagem provê um ambiente para interpretação, com diversas ferramentas numéricas. Algoritmos complexos podem ser criados em poucas linhas de código, em comparação com outras linguagens como C ou C++.

## Repositório Disponível  

* <a href="https://github.com/Epaminondaslage/Lab_Inf_Aplicada">Laboratório de Informática Aplicada (IoT)</a> 

# Status do Projeto

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
