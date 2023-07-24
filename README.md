<td style="width: 20%;"><img src="/img/topo.png" width="100%"></td>

# Índice 

* [Introdução](#Introdução)
* [Plataforma de Divulgação: GitHub](#Plataforma-de-Divulgação:-GitHub)
* [Plataforma de Automação Residencial](#Plataforma-de-Automação-Residencial)
* [Plataforma Automação Industrial](#Plataforma-Automação-Industrial)
* [Kit didáticos](#Kit-didáticos)
* [Protocolo de comunicação entre Plataformas - Modbus](#Protocolo-de-comunicação-entre-Plataformas-Modbus)
* [Sistema Operacional Linux](#Sistema-Operacional-Linux)
* [IDE Arduino](#IDE-Arduino)
* [Automatização com Node-RED](#Automatização-com-Node-RED)
* [Ambiente de Simulação - SCILab](#Ambiente-de-Simulação-Scilab)
* [Status do Projeto](#Status-do-Projeto)

# Introdução

O objetivo principal do ecossistema de automação industrial e residencial didático é capacitar os alunos a desenvolverem competências para projetar, implementar e solucionar problemas em sistemas de automação, preparando-os para o mercado de trabalho e para futuras pesquisas na área. Além disso, essa abordagem prática e participativa tende a despertar o interesse dos estudantes, tornando o aprendizado mais envolvente e efetivo.

A criação de um ecossistema de automação industrial e residencial didático é uma iniciativa muito valiosa para promover o aprendizado e o desenvolvimento de habilidades na área de automação e Internet das Coisas (IoT). Esse tipo de projeto visa fornecer aos alunos uma experiência prática e hands-on, permitindo que eles adquiram conhecimentos teóricos e apliquem-nos na prática por meio de atividades de modelagem, montagem e teste de sistemas de controle.

O ecossistema de automação industrial e residencial didático proposto apresenta as seguntes caracteristicas:

* Conteúdos teóricos: Disponibilizar materiais de ensino, tais como vídeos, apresentações, e-books e artigos, que explicam os conceitos fundamentais de automação industrial, residencial e IoT. Esses materiais podem abordar tópicos como sensores, atuadores, redes de comunicação, protocolos de comunicação, programação de sistemas embarcados e arquiteturas de automação.

* Manuais e tutoriais: Oferecer guias detalhados que orientem passo a passo os alunos na construção de sistemas de automação. Esses manuais podem incluir listas de materiais, instruções de montagem, códigos de programação e dicas para a solução de problemas comuns.

* Kits para laboratórios: Disponibilizar kits físicos contendo os componentes necessários para a construção dos sistemas de automação. Esses kits podem incluir sensores, atuadores, microcontroladores, placas de desenvolvimento e outros microcontoladores.

* Ambientes fisicos e virtuais: Além dos kits físicos, é interessante fornecer ambientes virtuais de simulação nos quais os alunos possam modelar e testar seus sistemas de automação. A integração com Programas como o Scilab  permite que os alunos experimentem e cometam erros sem riscos associados a sistemas reais.

* Plataforma de divulgação: Utilizar a plataforma do Github que centralize todos os recursos, como links de vídeos, manuais, tutoriais e acesso aos ambientes de simulação. Essa plataforma pode incluir fóruns de discussão, onde os alunos podem interagir, trocar experiências e esclarecer dúvidas aplicadas a cada repositório.

* Projetos práticos: Proporcionar aos alunos projetos práticos desafiadores, que incentivem a aplicação dos conhecimentos adquiridos. Os projetos podem variar em complexidade, permitindo que os alunos avancem gradualmente em suas habilidades utilizando os Kits apresentados e suas evoluçoes com o desenvolver do projeto.

* Avaliação e feedback: Implementar mecanismos de avaliação para acompanhar o progresso dos alunos e fornecer feedback construtivo sobre suas realizações.

<td style="width: 50%;"><img src="/img/Ecossistema Open Automação.png" width="70%" /></td>

A utilização dessas plataformas, protocolos de comunicação e linguagens de programação permitem que os alunos apliquem seus conhecimentos em projetos práticos, preparando-os para futuras carreiras na área de automação e controle. A integração de sensores comerciais MQTT, Zigbee, ESPHome e WiFi oferece diversas opções para comunicação e coleta de dados em sistemas de automação. Essa combinação de recursos permite criar soluções eficientes e versáteis para aplicações residenciais, industriais e de Internet das Coisas (IoT).

# Plataforma de Divulgação: GitHub

A plataforma de divulgação do ecossistema de automação industrial e residencial será o GitHub. Todos os recursos, como vídeos, manuais, tutoriais e acesso aos ambientes de simulação, serão centralizados em repositórios separados. Os alunos poderão interagir, trocar experiências e esclarecer dúvidas associados a cada repositório. Podemos enumerar algumas vantagens em usar este ambiente: 

* Centralização de Recursos: Vídeos, manuais, tutoriais e acesso aos ambientes de simulação em repositórios separados.
* Interatividade: Fóruns de discussão em cada repositório para interação, troca de experiências e esclarecimento de dúvidas.
* Controle de Versão: Possibilidade de acompanhar mudanças e colaborar de forma coletiva.
* Integração com Ferramentas: Facilidade para integrar-se a outras ferramentas de desenvolvimento.
* Colaboração: Permite que os alunos contribuam com novos recursos e melhorias.
* Acesso e Privacidade: Definição de permissões de acesso aos repositórios conforme a política do projeto.

Um dos principais benefícios do GitHub é permitir que os alunos criem "forks" dos repositórios, o que significa que eles podem fazer uma cópia do projeto original em suas contas pessoais. Ao criar um "fork", os alunos têm total liberdade para fazer modificações, melhorias e experimentar novas ideias sem afetar o repositório original. Após realizar suas modificações no "fork", eles podem propor que suas alterações sejam incorporadas ao repositório original por meio de um processo conhecido como "pull request".

# Plataforma de Automação Residencial

Na automação residencial, a escolha de plataformas de código aberto é fundamental para oferecer flexibilidade e personalização. O Home Assistant é uma excelente opção, atuando como um hub de automação que suporta uma ampla variedade de dispositivos e integrações. Sua interface intuitiva e flexível permite aos usuários personalizar e automatizar tarefas residenciais de acordo com suas preferências e necessidades específicas.

O Home Assistant é uma plataforma de automação residencial de código aberto e domótica baseada em Python. Projetado para ser executado em uma variedade de dispositivos, como Raspberry Pi, servidores Linux, Windows e macOS, o Home Assistant fornece uma solução flexível e escalável para controlar e monitorar dispositivos e sistemas domésticos inteligentes. Utilizando uma arquitetura modular, o Home Assistant suporta a integração com inúmeras marcas e protocolos populares, permitindo a interação com dispositivos como lâmpadas, termostatos, câmeras, entre outros. Os usuários podem personalizar suas automações e scripts utilizando a linguagem de configuração YAML e a interface gráfica do usuário, tornando possível criar cenários complexos de automação. A plataforma também oferece integração com assistentes de voz, como Amazon Alexa e Google Assistant, ampliando suas funcionalidades e tornando-o um hub centralizado para a automação inteligente de casas.

<p><b>Repositórios Disponíveis</b></p>  
    <ul>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant">Home Assistant</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-ESPHome">Home Assistant - ESPHome</a></li> 
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-Telegram">Home Assistant - Telegram</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-NodeMCU-MQTT">Home Assistant - NodeMCU/MQTT</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-Tuya">Home Assistant - Tuya</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-Sonoff">Home Assistant - Sonoff</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-ESP32-ESP8266-ESPHome">Home Assistant - ESP32-ESP8266-ESPHome</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-Tasmota-MQTT">*Home Assistant - Tasmota/MQTT</a></li>
    </ul>

# Plataforma Automação Industrial

As linguagens de programação são essenciais na automação industrial, seguindo a norma IEC 61131-3, que padroniza boas práticas para o desenvolvimento de programas de CLPs, buscando qualidade e economia de tempo no desenvolvimento e testes. Combinando o Node-RED com os nós Modbus, os alunos podem criar soluções poderosas de IoT e automação, tornando mais fácil e eficiente a integração de dispositivos e sistemas em ambientes industriais e residenciais. A programação visual do Node-RED simplifica o desenvolvimento de aplicações complexas, permitindo que mesmo os usuários com pouca experiência em programação possam criar soluções robustas para suas necessidades específicas.

O OpenPLC é uma plataforma de automação industrial de código aberto, projetada para implementar Controladores Lógicos Programáveis (CLPs) de forma flexível e acessível. Compatível com diversos dispositivos de hardware, como Raspberry Pi e Arduino, o OpenPLC oferece uma solução versátil para controlar processos industriais. Sua conformidade com a norma IEC 61131-3 permite a programação utilizando linguagens padronizadas, como LD, IL e FBD, facilitando o desenvolvimento e reutilização de lógicas. 

<p><b>Repositórios Disponíveis</b></p> 
    <ul>
        <li><a href="https://github.com/Epaminondaslage/OpenPLC">OpenPLC</a></li>
        <li><a href="https://github.com/Epaminondaslage/OpenPLC/tree/master/primeirodiagrama">Primeiro Diagrama OpenPLC Editor</a></li>
        <li><a href="https://github.com/Epaminondaslage/HomeAssistant-OpenPLC">HomeAssistant-OpenPLC</a></li>
        <li><a href="https://github.com/Epaminondaslage/OpenPLC/tree/master/cargaruntime">OpenPLC Runtime</a></li>
        <li><a href="https://github.com/Epaminondaslage/Diagramas-de-comandos-eletricos-de-motores/">Diagramas de Comandos Elétricos de Motores</a></li>
    </ul>
 
# Kit didáticos

O uso de kits didáticos é uma solução viável para superar as limitações físicas, técnicas e financeiras associadas ao uso de sistemas reais em ambiente acadêmico. Esses kits proporcionam um ambiente de aprendizado semelhante aos sistemas reais, permitindo que os alunos apliquem os conhecimentos teóricos adquiridos na prática. Com uma variedade de sensores e módulos, os alunos podem realizar experimentos e projetos, ampliando sua compreensão dos conceitos teóricos e desenvolvendo suas habilidades práticas.

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

# Protocolo de comunicação entre Plataformas 

Existem diversos protocolos de comunicação utilizados em sistemas industriais e residenciais para permitir a troca de informações entre dispositivos, sensores, atuadores e sistemas de controle. Iremos utilizar alguns dos protocolos mais comuns:

Modbus: Um protocolo de comunicação serial amplamente utilizado em ambientes industriais para troca de dados entre dispositivos, como controladores lógicos programáveis (PLCs) e dispositivos de campo, como sensores e atuadores.

Ethernet/IP: Um protocolo baseado em Ethernet que permite a comunicação entre dispositivos industriais. Ele é comumente usado em ambientes de automação que requerem comunicação em tempo real.

Z-Wave e Zigbee: São protocolos de comunicação sem fio utilizados em automação residencial para conectar dispositivos como sensores, atuadores e dispositivos de controle, permitindo a criação de redes de sensores e atuadores inteligentes.

Wi-Fi e Bluetooth: Embora amplamente utilizados em dispositivos de consumo, também são aplicados em automação residencial, permitindo a conectividade de dispositivos inteligentes à rede local e ao controle por meio de aplicativos móveis.

É importante escolher o protocolo de comunicação adequado de acordo com a aplicação específica, levando em consideração a distância de comunicação, a velocidade necessária, os requisitos de segurança e a compatibilidade com os dispositivos e sistemas envolvidos. Além disso, com a evolução contínua da tecnologia, novos protocolos podem surgir para atender às necessidades emergentes de automação industrial e residencial.

<p><b>Repositórios Disponíveis</b></p>   
<ul>
 <li><a href="https://github.com/Epaminondaslage/openplc-modbus">Home Assistant - Modbus</a></li>
</ul>


# Sistema Operacional Linux

o Linux é amplamente utilizado em sistemas de automação, tanto em aplicações industriais quanto residenciais. O Linux é um sistema operacional de código aberto e baseado em Unix, conhecido por sua confiabilidade, segurança e flexibilidade, o que o torna uma escolha popular para diferentes cenários de automação.

Existem várias razões pelas quais o Linux é uma opção atraente para sistemas de automação:

* Código Aberto: O fato de o Linux ser um sistema operacional de código aberto significa que ele pode ser modificado e personalizado de acordo com as necessidades específicas do projeto de automação.
* Estabilidade e Confiabilidade: O Linux é conhecido por sua estabilidade e confiabilidade, o que é essencial em ambientes de automação onde a consistência e o funcionamento ininterrupto são cruciais.
* Suporte a Diversos Dispositivos: O Linux possui um amplo suporte a drivers, permitindo que ele funcione em uma variedade de dispositivos e plataformas de hardware, desde computadores industriais até sistemas embarcados.
* Baixo Custo: O Linux é uma opção econômica, pois é um sistema operacional de código aberto, e muitas distribuições são gratuitas.
* Flexibilidade: O Linux oferece flexibilidade para adaptar-se às necessidades específicas de automação, permitindo que os desenvolvedores escolham as ferramentas e componentes adequados para cada projeto.
* Comunidade Ativa: O Linux possui uma comunidade de desenvolvedores e entusiastas ativa, o que significa que há um vasto conjunto de recursos, tutoriais e suporte disponível.
* Segurança: O Linux é amplamente reconhecido por sua segurança robusta, o que é crucial em sistemas de automação, onde a proteção contra ameaças é essencial.

Integração com Tecnologias de Código Aberto: O Linux pode ser facilmente integrado a outras tecnologias de código aberto amplamente usadas na automação, como o OpenPLC para automação industrial e o Home Assistant para automação residencial.

Com o uso do sistema operacional de código aberto Linux, o Orange Pi, colocado no Kit , o Raspberry PI como servidor para o OpenPLC e Home Assistant oferece uma ampla gama de possibilidades de uso. Ele pode ser utilizado como um computador completo, servidor para aplicações de pequeno porte, servidor doméstico para automação residencial, videogame retrô e central de mídia para filmes, músicas, entre outros.

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

* Introdução ao Shell Script em SBC's com Linux

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

# Ambiente de Simulação - SCILab

O Scilab é uma ferramenta científica de código aberto para computação numérica, que se assemelha ao MATLAB, fornecendo um ambiente computacional poderoso e aberto para aplicações científicas. Sua linguagem de programação de alto nível é voltada para análise numérica, oferecendo um ambiente de interpretação com diversas ferramentas numéricas. Com o Scilab, é possível criar algoritmos complexos em poucas linhas de código, o que o torna uma opção mais eficiente em comparação com outras linguagens como C ou C++. Essa característica torna o Scilab uma escolha popular para cientistas, engenheiros e pesquisadores que buscam uma solução eficaz para suas necessidades de computação numérica. O Scilab fornece suporte para a comunicação com dispositivos Modbus por meio de bibliotecas de comunicação ou scripts personalizados.

A aquisição de dados entre o Scilab e dispositivos Modbus pode ser realizada por meio de bibliotecas e pacotes específicos de código aberto, que permitem a comunicação Modbus no Scilab. Bibliotecas como o "ScilabModbus" e o "ScilabModbusMaster", permitem a interação com dispositivos Modbus TCP/IP. Essas bibliotecas permitem que o Scilab atue como mestre ou cliente Modbus, solicitando dados de dispositivos escravos ou servidores Modbus. Isto facilita a comunicação entre as duas tecnologias. 

<p><b>Repositórios Disponíveis</b></p>   
<ul>
 <li><a href="https://github.com/Epaminondaslage/Lab_Inf_Aplicada">Laboratório de Informática Aplicada (IoT)</a> </li>
</ul>

# Status do Projeto

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
