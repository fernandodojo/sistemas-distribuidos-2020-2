# Definição de Sistemas Distribuídos

O conceito de sistema distribuído é de um sistema que possui a capacidade de permitir a comunicaçõo e o compartilhamento de recursos conputacionais ou serviços através de troca de mensagens entre os diversos componentes do sistema que são independes e dependem da comunicação através de rede. Outra característica é que embora os composntesntes desse sistemas sejam independentes, este sistema pode ser observado como um único componente. Inicialmente esses sistema propunham-se a compartilhar recursos como impressoras e arquivos, mas com o tempo, estes se propõe a compartilhar serviços em geral, componentes, processamento, comunicação, tratamento de falhas, escalabilidade, segurança, transparencia, concorrência, interoperabilidade, portabilidade, extensibilidade e muitas outras caracteríticas de tranparência de distribuição, sendo elas um completo desafio para se atingir.
Umas das características mais importântes está o conceito de escalabilidade, sendo estes divividos em dois tipos: Escalabilidade em relação ao tamanho e geográfica, na primeira, são considerados a centralização de serviços, dados, ou algoritmos, já na escalabilidade geográfica são utilizado redes WAN e LAN, pontunando que em LAN os sistemas são mais confiáveis. Vale pontuar que o principal objetivo da escalabilidade é evitar um único ponto de falha, que cause a interrupção dos serviços, assim como manter-se disponível e capaz de balancear suas tarefas de forma a apresentar um bom desempenho.

## I) Sistema de Computação Distribuídos de Alto Desempenho

Este sistemas geralmente são utilizados para para tarefas de alto desempenho, sua base está na computação paralela. Sendo este divididos em Cluster e Computação em grade.
Os cluster se tornaram bem conhecidos e bastante utilizados pela facilidade e baixo custo para se montar e obter um ganho significativo de desempenho, geralmente é utilizado um programa, com os mesmo SO em todas as estações com a intenção de ser executado em paralelo para a realização de uma tarefa, neste tipo de sistema existe o nó mestre para gerencimanto que tem como função principal manipular a alocação dos nós a determinadas tarefas, manter fila de tarefas, assim como fornecer uma interface. Além do nó  mestre existes os vários outros nós de computação responsáveis por executar as tarefas.
Já a computação em grade, é compostas por recursos que são geralmente bem diferentes, com diferentes capacidades, utlizando sistemas diversos, geralmente em grandes distâncias, e tudo somente pela rede. Entre suas principais diferenças com os clustes estão a heterogenedade dos componentes, a dispersão geográfica, os múltiplos domínios administrativos, e o controle totalmente distribuído, ou seja, não centralizado.

## II) Sistemas de Informação Distribuídos

São classificados como sistema que processão transações, e grandes volumes de informação de forma esquematizada. Este tem como objetivo garantir uma série de objetivos sendo eles: Atomidicidade, Concistência, Isolamento e Durabilidade. Ou seja, as transações devem ser todas bem sucedidas ou falhar, não deve violar invariancias do sistema, devem ser independentes, e serem capaz de reter informações após a finalização do processamento.

## III) Sistemas Distribuídos Pervasivos

Fruto da computação móvel, entre suas principais caracteríticas está a utilização de baterias, a interface com o usuário, assim com a heterogeneadade de rede e dispositivos, mesmo que em sua maioria seja feita a comunicação por redes sem fio. Além disso é conhecida também pela utilização e aplicação de sensores para monitoramente dos mais diversos tipos de aplicaçõe. Sendo este um tipo de sistema distribuídos extremamente utilizado que produza uma quantidade massiva de dados para as ciências de contexto.

# Middlewares

Middleware funcionada como uma camada, uma abstração, onde diversos software podem trabalhar em conjunto independente as tecnologias de software que o compontente utiliza, ou da forma como o componente compartilha informação, diferenças de protocolo, plataforma, arquitetura, SO, ambientes físicos, ou seja, os middleware agem como uma camada intermediária sendo geralmente construídos de forma a disponibilizar APIs de alto nível que proporcionem a integração.

# Lista de Middlewares

> Exemplos de Middlewares e suas aplicações. 

## JBoss Enterprise Application Platform (https://www.redhat.com/en/technologies/jboss-middleware/application-platform)

O Red Hat JBoss Enterprise Application Platform (EAP) uma solução flexível e compatível com a nuvem para empresas que buscam aumentar sua agilidade. A aplicação é baseada no JAVA EE possuindo entre os seus principais benefícios a base sólida em JAVA, baixo tempo de inicialização e uso de memória, integração com ferramentas DevOps, como Maven, Jenkins e Arquillian, além de um centro de suporte para suporte usual assim como para migração de aplicações. Sua principal função é deploy de aplicaçãoes, oferecer ambiente para aplicações java e web serviços.

## IBM WebSphere (http://www-03.ibm.com/software/products/en/appserv-was)

Sua base de desenvolvimento é composta JAVA, oferecendo serviços como framework OpenLiberty, Kubernetes Cloud, MicroProfile, Java EE, Java SE entre outros. Quando ao seus recursos e funções, são composto por diversos outros serviços, que vão desde ao gerenciamento de microserviços, serviços para deploy, sistema de distribuídos de grade, servidor web, entre outros.

## Oracle WebLogic (http://www.oracle.com/technetwork/middleware/weblogic/overview/index.html)

Pode ser devido por um middleware que baseado em JAVA, desenvolvido pela Oracle, tem como principal função oferecer uma JVM do JAVA EE, com funções para deploy de aplicações e serviços, além de recursos para bases de dados, gerenciamentos de sistemas empresariais, e serviços de mensagem, além de oferecer conectividades com vários serviços de terceiros baseados em .NET.






	
	
