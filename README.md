<td style="width: 20%;"><img src="/img/Logo_CEFET-MG.png" width="20%" /></td>
<p><strong><span style="color: #0000ff;">Automação industrial e residencial</span></strong></p>
<p><strong><span style="color: #0000ff;">Ecossistema didático com Open Software e Open Hardware</span></strong></p>
<p><strong><span style="color: #0000ff;">Prof Epaminondas Lage</span></strong></p>
<a href="http://lattes.cnpq.br/7787341723868111"> Currículo Lattes LAGE, E. S.</a> 

<td style="width: 50%;"><img src="/img/Ecossistema-Open-Automação.png" width="50%" /></td>

## Índice deste Repositório

* [Introdução](#Introdução)
* [Sistema Operacional Linux](Sistema-Operacional-Linux)
* [OpenPLC](OpenPLC)
* [ScadaBR](ScadaBR)
* [OpenHardware](OpenHardware)
* [SCILab](SCILab)
* [MBLogic](MBLogic)
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
<td style="width: 50%;"><img src="/img/kit_iot.png" alt="" width="300" height="300" /></td>
</tr>
<tr>
<td style="width: 50%;">Figura 1: Kit Open PLC</td>
<td style="width: 50%;">Figura 2: Kit IoT</td>
</tr>
</tbody>
</table>

# Sistema Operacional Linux
* <a href="../SO_Ubuntu_SBC_OrangePI">/SO Ubuntu SBC OrangePI</a> 
* <a href="../SO_Debian_SBC_OrangePI">/SO Debian SBC OrangePI</a>   
*      
# OpenPLC

# ScadaBR

# Kit de IoT

asbdsjkdhjkshjdhjkshjkdhkjsd
sdsdsdsdsdssdsd

* <a href="../Epaminondaslage/Kit_IoT">Kits IoT</a> 

# SCILab

# MBLogic

# Status do Projeto

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
