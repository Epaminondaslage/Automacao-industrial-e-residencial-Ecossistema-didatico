<td style="width: 20%;"><img src="/img/Logo_CEFET-MG.png" width="20%"></td>
<p><strong><span style="color: #0000ff;">Automação Industrial e Residencial</span></strong></p>
<p><strong><span style="color: #0000ff;">Ecossistema didático com Open Software e Open Hardware</span></strong></p>
<p><strong><span style="color: #0000ff;">Prof Epaminondas Lage</span></strong></p>
<a href="http://lattes.cnpq.br/7787341723868111"> Currículo Lattes LAGE, E. S.</a></p>
<p><strong><span style="color: #0000ff;">Prof Danilo Freitas Melo</span></strong></p>
<a href="http://lattes.cnpq.br/3410712703972723"> Currículo Lattes MELO, D. F.</a></p>

<td style="width: 50%;"><img src="/img/Ecossistema Open Automação.png" width="70%" /></td>

# Índice 

* [Introdução](#Introdução)
* [Kit didáticos](#Kit-didáticos)
* [Sistema Operacional Linux](#Sistema-Operacional-Linux)
* [Introdução ao Shell Script no Linux](#Introdução-ao-Shell-Script-no-Linux)
* [IDE Arduino](#IDE-Arduino)
* [Automatização com Node-RE](#Automatização-com-Node-RED)
* [Protocolo de comunicação entre Plataformas - Modbus](#Protocolo-de-comunicação-entre-Plataformas-Modbus)
* [Plataforma Home Assistant de Automação Residencial](#Plataforma-Home-Assistant-de-Automação-Residencial)
* [Plataforma Open PLC](#Plataforma-OpenPLC)
* [SCILab](#SCILab)
* [Status do Projeto](#Status-do-Projeto)

# Introdução

O projeto disponibiliza conteúdos, manuais, tutoriais e kits para laboratórios, permitindo que os alunos projetem, montem e testem seus conhecimentos na área de automação residencial, industrial e Internet das Coisas (IoT). Os sistemas propostos permitem a modelagem, análise, projeto e teste de sistemas de controle em ambientes virtuais ou reais em escalas reduzidas.

O uso de kits didáticos é uma solução viável para superar as limitações físicas, técnicas e financeiras associadas ao uso de sistemas reais em ambiente acadêmico. Esses kits proporcionam um ambiente de aprendizado semelhante aos sistemas reais, permitindo que os alunos apliquem os conhecimentos teóricos adquiridos na prática. Com uma variedade de sensores e módulos, os alunos podem realizar experimentos e projetos, ampliando sua compreensão dos conceitos teóricos e desenvolvendo suas habilidades práticas.

As linguagens de programação são essenciais na automação industrial, seguindo a norma IEC 61131-3, que padroniza boas práticas para o desenvolvimento de programas de CLPs, buscando qualidade e economia de tempo no desenvolvimento e testes. Combinando o Node-RED com os nós Modbus, os alunos podem criar soluções poderosas de IoT e automação, tornando mais fácil e eficiente a integração de dispositivos e sistemas em ambientes industriais e residenciais. A programação visual do Node-RED simplifica o desenvolvimento de aplicações complexas, permitindo que mesmo os usuários com pouca experiência em programação possam criar soluções robustas para suas necessidades específicas.

Na automação residencial, a escolha de plataformas de código aberto é fundamental para oferecer flexibilidade e personalização. O Home Assistant é uma excelente opção, atuando como um hub de automação que suporta uma ampla variedade de dispositivos e integrações. Sua interface intuitiva e flexível permite aos usuários personalizar e automatizar tarefas residenciais de acordo com suas preferências e necessidades específicas.

Essas plataformas e linguagens permitem que os alunos apliquem seus conhecimentos em projetos práticos, preparando-os para futuras carreiras na área de automação e controle. A integração de sensores comerciais MQTT, Zigbee e WiFi oferece diversas opções para comunicação e coleta de dados em sistemas de automação. Essa combinação de recursos permite criar soluções eficientes e versáteis para aplicações residenciais, industriais e de Internet das Coisas (IoT).
 
# Kit didáticos

## Kit IoT

O KIT IoT foi projetado para fornecer um aprendizado básico em microcontroladores, como Arduino, Wemos D1 e Esp32, por meio da utilização de diversos sensores e ainda para funcionar como endpoint do Kit SBC Linux. O kit reúne 37 sensores e módulos básicos que permitem a captura de diversos fenômenos físicos e químicos. Ele inclui sensores e atuadores digitais e analógicos, bem como módulos especiais como ultrassom, Bluetooth, aceleração, WIFI, entre outros.

Para cada sensor, foram desenvolvidos diagramas de conexão e códigos de exemplo. Mesmo que o aluno seja totalmente iniciante, ele pode começar facilmente, pois os códigos de exemplo são baseados no Arduino, uma plataforma de código aberto e fácil de usar. Caso o aluno já possua conhecimentos prévios, ele também pode aplicar este kit em outras plataformas de desenvolvimento de microcontroladores e sistemas embarcados.

Esse kit possibilita a experimentação e aprendizado prático, permitindo aos usuários desenvolverem projetos e soluções usando uma variedade de sensores e plataformas de microcontroladores. Com a combinação de teoria e prática, os alunos podem adquirir habilidades valiosas em eletrônica, programação e IoT.

## Kit SBC Linux

A base de sustentação para as placas do KITSBC Linux foi desenvolvida e construída utilizando impressão 3D, possuindo dimensões de 245x180x15 mm. Ela conta com um slot para a placa OrangePi One, uma protoboard para testes e experimentação, um módulo com 8 relés e outro com 5 push-buttons. O componente central do Kit SBC Linux é o OrangePi One, uma Single-Board Computer (SBC) com processador ARM, que oferece suporte a diversas distribuições do sistema operacional GNU/Linux. Foram geradas duas versões de sistemas operacionais, o Ubuntu e o Debian, para atender a diferentes aplicações e necessidades dos alunos.

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

<p><b>Repositórios Disponíveis</b></p>
<ul>
   <li> <a href="https://github.com/Epaminondaslage/Kit-IoT">Kit Internet das Coisas (IoT)</a></li>
   <li> <a href="https://github.com/Epaminondaslage/Kit-SBC-Linux">Kit SBC Linux</a></li>
</ul>  

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

<p><b>Repositórios Disponíveis</b></p>
<ul>
   <li> <a href="https://github.com/Epaminondaslage/SO_Ubuntu_SBC_OrangePI">SO Ubuntu SBC OrangePI</a>  </li>
   <li> <a href="https://github.com/Epaminondaslage/SO-Debian-SBC-OrangePI">SO Debian SBC OrangePI</a>    </li>
</ul>   

# Introdução ao Shell Script em SBC's com Linux

Um script é um algoritmo desenvolvido para executar uma tarefa específica, utilizando comandos do bash e executáveis do sistema operacional. O shell é um programa que permite a interação direta do usuário com o sistema operacional, interpretando comandos enviados ao Kernel para executar ações desejadas.

O Bash (Bourne Again Shell) é um shell do Unix e também uma linguagem de programação capaz de realizar várias tarefas, otimizando tempo e recursos. Ele permite aprimoramentos constantes em "softwares-pai" de maneira prática e também configurações de software e extração de dados.

O shell script possui vantagens, pois pode ser facilmente combinado com outros comandos e utilitários do Linux, aproveitando os recursos disponíveis no sistema operacional e suas ferramentas de linha de comando. Além disso, ele suporta recursos avançados como funções, expressões regulares, redirecionamento de entrada/saída, processamento de sinais e manipulação de arquivos, tornando-o poderoso para automação e tarefas complexas.

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

<p><b>Repositórios Disponíveis</b></p>
<ul>
   <li> <a href="https://github.com/Epaminondaslage/Shell-Script-em-Linux">Shel Script em Linux</a> </li>
</ul>   

# IDE Arduino

O Arduino IDE é um software gratuito que simplifica o desenvolvimento e a gravação de códigos em microcontroladores, permitindo o upload dos códigos para a placa Arduino e microcontroladores compatíveis em diferentes sistemas operacionais. Suas principais funções incluem o desenvolvimento de software, envio de código para a placa e interação com a mesma. O Repositório "PPT das Aulas de Programação Arduino" contém slides de um curso básico de programação com Arduino, complementando o programa da disciplina Informática Aplicada. Essa ferramenta é amplamente usada por entusiastas e profissionais para prototipagem rápida, automação, sistemas embarcados e projetos de IoT devido à sua interface intuitiva, vasta quantidade de bibliotecas e recursos disponíveis.

<p><b>Repositórios Disponíveis</b></p> 
<ul>
 <li><a href="https://github.com/Epaminondaslage/Kit-IoT/tree/master/material_didatico/ppt_de_aulas">PPT das Aulas de Programação Arduino</a></li>
  <li><a href="https://github.com/Epaminondaslage/Arduino-Uno">Sketch Arduino</a></li>
</ul>

# Automatização com Node-RED

O Node-RED é uma plataforma de desenvolvimento de fluxo de código aberto baseada em JavaScript, que oferece uma abordagem de programação visual para conectar dispositivos e serviços na Internet das Coisas (IoT) e na automação industrial. Projetado para ser executado em servidores Node.js, o Node-RED permite que os desenvolvedores criem fluxos de automação interligando "nós" pré-definidos para manipular, processar e transmitir dados de forma eficiente. Cada nó representa uma função específica, como entrada, processamento e saída de dados, e os fluxos são criados arrastando e conectando esses nós através de uma interface gráfica intuitiva. O Node-RED oferece uma biblioteca extensiva de nós prontos para uso e suporta integração com uma variedade de dispositivos e serviços, incluindo sensores, atuadores, bancos de dados, APIs da web e muito mais. Sua arquitetura flexível e extensível possibilita a criação de automações complexas e personalizadas, permitindo a rápida prototipagem e implantação de soluções IoT e de automação. Sua popularidade crescente entre a comunidade de desenvolvedores torna o Node-RED uma opção poderosa e versátil para conectar e automatizar sistemas em ambientes IoT e industriais.

<p><b>Repositórios Disponíveis</b></p>   
<ul>
 <li><a href="https://github.com/Epaminondaslage/HomeAssistant-NodeRED">Home Assistant - Node-RED</a></li>
</ul>

# Protocolo de comunicação entre Plataformas - Modbus

O Modbus é um protocolo de comunicação utilizado amplamente na automação industrial para troca de dados entre dispositivos de controle, como Controladores Lógicos Programáveis (CLPs) e dispositivos de campo, como sensores e atuadores. Ele opera em uma arquitetura mestre-escravo ou cliente-servidor, onde um dispositivo mestre (ou cliente) solicita informações de um ou mais dispositivos escravos (ou servidores). O Modbus é baseado em uma estrutura de mensagens simples, com o formato de dados organizado em "registros", que podem ser de entrada, saída, de estado ou registradores analógicos. Utiliza diferentes tipos de protocolos de comunicação, incluindo Modbus RTU (transmissão de caracteres em formato binário), Modbus ASCII (transmissão de caracteres ASCII) e Modbus TCP (transmissão através de Ethernet). Sua simplicidade e ampla adoção na indústria tornam o Modbus uma opção popular para integração de dispositivos e sistemas em ambientes industriais, permitindo a coleta de dados, controle de processos e monitoramento de equipamentos de forma confiável e eficiente.

<p><b>Repositórios Disponíveis</b></p>   
<ul>
 <li><a href="https://github.com/Epaminondaslage/openplc-modbus">Home Assistant - Modbus</a></li>
</ul>

# Plataforma Home Assistant de Automação Residencial

O Home Assistant é uma plataforma de automação residencial de código aberto e domótica baseada em Python. Projetado para ser executado em uma variedade de dispositivos, como Raspberry Pi, servidores Linux, Windows e macOS, o Home Assistant fornece uma solução flexível e escalável para controlar e monitorar dispositivos e sistemas domésticos inteligentes. Utilizando uma arquitetura modular, o Home Assistant suporta a integração com inúmeras marcas e protocolos populares, permitindo a interação com dispositivos como lâmpadas, termostatos, câmeras, entre outros. Os usuários podem personalizar suas automações e scripts utilizando a linguagem de configuração YAML e a interface gráfica do usuário, tornando possível criar cenários complexos de automação. A plataforma também oferece integração com assistentes de voz, como Amazon Alexa e Google Assistant, ampliando suas funcionalidades e tornando-o um hub centralizado para a automação inteligente de casas.

<p><b>Repositórios Disponíveis</b></p>  
    <ul>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant">Home Assistant</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-ESPHome">Home Assistant - ESPHome</a></li> 
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-Telegram">Home Assistant - Telegram</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-Tuya">*Home Assistant-Tuya</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-Tasmota-MQTT">*Home Assistant-Tasmota-MQTT</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-Sonoff">*Home Assistant-Sonoff</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-ESP32-MQTT">*Home Assistant - ESP32 - MQTT</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-ESP8266-ESPHome">*Home Assistant - ESP8266 e ESPHome</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-NodeMCU-MQTT">Home Assistant, NodeMCU com MQTT</a></li>
    </ul>

# Plataforma OpenPLC

O OpenPLC é uma plataforma de automação industrial de código aberto, projetada para implementar Controladores Lógicos Programáveis (CLPs) de forma flexível e acessível. Compatível com diversos dispositivos de hardware, como Raspberry Pi e Arduino, o OpenPLC oferece uma solução versátil para controlar processos industriais. Sua conformidade com a norma IEC 61131-3 permite a programação utilizando linguagens padronizadas, como LD, IL e FBD, facilitando o desenvolvimento e reutilização de lógicas. 

<p><b>Repositórios Disponíveis</b></p> 
    <ul>
        <li><a href="https://github.com/Epaminondaslage/OpenPLC">OpenPLC</a></li>
        <li><a href="https://github.com/Epaminondaslage/OpenPLC/tree/master/primeirodiagrama">Primeiro Diagrama OpenPLC Editor</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-OpenPLC">HomeAssistant-OpenPLC</a></li>
        <li><a href="https://github.com/Epaminondaslage/OpenPLC/tree/master/cargaruntime">OpenPLC Runtime</a></li>
        <li><a href="https://github.com/Epaminondaslage/Diagramas-de-comandos-eletricos-de-motores/">Diagramas de Comandos Elétricos de Motores</a></li>
    </ul>

# SCILab

O Scilab é uma ferramenta científica de código aberto para computação numérica, que se assemelha ao MATLAB, fornecendo um ambiente computacional poderoso e aberto para aplicações científicas. Sua linguagem de programação de alto nível é voltada para análise numérica, oferecendo um ambiente de interpretação com diversas ferramentas numéricas. Com o Scilab, é possível criar algoritmos complexos em poucas linhas de código, o que o torna uma opção mais eficiente em comparação com outras linguagens como C ou C++. Essa característica torna o Scilab uma escolha popular para cientistas, engenheiros e pesquisadores que buscam uma solução eficaz para suas necessidades de computação numérica. O Scilab fornece suporte para a comunicação com dispositivos Modbus por meio de bibliotecas de comunicação ou scripts personalizados.

A aquisição de dados entre o Scilab e dispositivos Modbus pode ser realizada por meio de bibliotecas e pacotes específicos de código aberto, que permitem a comunicação Modbus no Scilab. Bibliotecas como o "ScilabModbus" e o "ScilabModbusMaster", permitem a interação com dispositivos Modbus TCP/IP. Essas bibliotecas permitem que o Scilab atue como mestre ou cliente Modbus, solicitando dados de dispositivos escravos ou servidores Modbus. Isto facilita a comunicação entre as duas tecnologias. 

<p><b>Repositórios Disponíveis</b></p>   
<ul>
 <li><a href="https://github.com/Epaminondaslage/Lab_Inf_Aplicada">Laboratório de Informática Aplicada (IoT)</a> </li>
</ul>

# Status do Projeto

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
