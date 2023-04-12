# Certificação Amazon AWS Cloud Practitioner

## Cloud Computing?

O que é Cloud Computing

- O que é a computação em nuvem?
  - A computação em nuvem é a entrega de recursos de TI sob demanda por meio da Internet com definição de preço de pagamento conforme o uso. Em vez de comprar, ter e manter datacenters e servidores físicos, você pode acessar serviços de tecnologia, como capacidade computacional, armazenamento e bancos de dados, conforme a necessidade, usando um provedor de nuvem como a Amazon Web Services (AWS).

- Quem usa a computação em nuvem?
  - Organizações de todos os tipos, portes e setores usam a nuvem para uma grande variedade de casos de uso, como backup de dados, recuperação de desastres, e-mail, desktops virtuais, desenvolvimento e teste de software, análises de big data e aplicativos web voltados ao cliente. Por exemplo, as empresas do setor de saúde usam a nuvem para desenvolver tratamentos mais personalizados para os pacientes. Empresas de serviços financeiros usam a nuvem como base para detectar e prevenir fraudes em tempo real. E fabricantes de videogames usam a nuvem para entregar jogos online para milhões de jogadores em todo o mundo.
 
![image](https://user-images.githubusercontent.com/56324728/231313073-92a2172e-27de-4ad0-b305-6aae395681d6.png)
 
## Vantagens

Benefícios da computação em nuvem

- Agilidade
  - A nuvem oferece acesso fácil a uma grande variedade de tecnologias para que você possa inovar mais rapidamente e criar praticamente tudo o que puder imaginar. Você pode gerar rapidamente recursos conforme a necessidade, de serviços de infraestrutura, como computação, armazenamento e bancos de dados até Internet das Coisas, machine learning, data lakes, análises de dados e muito mais.
  - Você pode implantar serviços de tecnologia em questão de minutos e passar da ideia à implementação com agilidade várias ordens de grandeza maior do que antes. Assim, você tem a liberdade de experimentar, testar novas ideias para diferenciar as experiências dos clientes e transformar a sua empresa.

- Elasticidade
  - Com a computação em nuvem, você não precisa provisionar recursos em excesso para absorver picos de atividades empresariais no futuro. Em vez disso, você provisiona a quantidade de recursos realmente necessária. Você pode aumentar ou diminuir instantaneamente a escala desses recursos para ajustar a capacidade de acordo com a evolução das necessidades empresariais.

- Economia de custo
  - A nuvem permite que você troque as despesas de capital (datacenters, servidores físicos etc.) por despesas variáveis e pague apenas pela TI consumida. Além disso, as despesas variáveis são muito menores do que as que você pagaria por conta própria devido às economias de escala.

- Implantação global em questão de minutos
  - Com a nuvem, você pode ampliar as atividades para novas regiões geográficas e implantar globalmente em minutos. Por exemplo, a AWS tem infraestrutura em todo o mundo, o que permite que você implante aplicativos em vários locais físicos com apenas alguns cliques. Aproximar os aplicativos dos usuários finais reduz a latência e melhora a experiência desses usuários.

![image](https://user-images.githubusercontent.com/56324728/231313426-46f2a584-424b-4394-b45b-2e278e624773.png)

![image](https://user-images.githubusercontent.com/56324728/231313500-d6416483-44e5-464f-a0f5-b3d2095bdd0a.png)

## Cloud Types

Diferentes Tipos de Cloud

- Infraestrutura como serviço (IaaS)
  - O IaaS contém os componentes básicos da IT na nuvem. Normalmente, o IaaS oferece acesso a recursos de rede, computadores (virtuais ou em hardware dedicado) e espaço de armazenamento de dados. O IaaS oferece o mais alto nível de flexibilidade e controle de gerenciamento sobre os recursos de TI. Ele é o tipo de computação mais semelhante aos recursos existentes de TI, já conhecidos por vários departamentos e desenvolvedores de TI.

- Plataforma como serviço (PaaS)
  - Com o PaaS, você não precisa mais gerenciar a infraestrutura subjacente (geralmente, hardware e sistemas operacionais) e pode manter o foco na implantação e no gerenciamento de aplicativos. Dessa forma, você fica mais eficiente, pois não precisa se preocupar com aquisição de recursos, planejamento de capacidade, manutenção de software, correções ou qualquer outro tipo de trabalho genérico repetitivo necessário para a execução dos aplicativos.

- Software como serviço (SaaS)
  - O SaaS oferece um produto completo, executado e gerenciado pelo provedor de serviços. Na maioria dos casos, quando as pessoas mencionam SaaS, estão falando de aplicativos de usuários finais (como e-mail baseado na web). Com uma oferta de SaaS, você não precisa pensar sobre a manutenção do serviço ou o gerenciamento da infraestrutura subjacente. Você só precisa se preocupar sobre como utilizará esse software específico.

![image](https://user-images.githubusercontent.com/56324728/231312696-72ac883b-edc7-4d79-8557-f693ef3b74b7.png)

![image](https://user-images.githubusercontent.com/56324728/231313107-3008335c-82b7-469d-951f-19918b227a40.png)

## Cloud Deployments

- Public Cloud
  - Provider
    - AWS
    - Azure
    - GCP

- Hybrid
  - Public / Private

- Private Cloud (On-premise)
  - Data Center com gerenciamento local

## AWS Services

[Lista de Serviços AWS](https://aws.amazon.com/pt/products/?aws-products-all.sort-by=item.additionalFields.productNameLowercase&aws-products-all.sort-order=asc&awsf.re%3AInvent=*all&awsf.Free%20Tier%20Type=*all&awsf.tech-category=*all)

- 200+ serviços

## Global Infrastructure

Regiões e Availability Zones

- Regiões
  - A AWS tem o conceito de uma região, que é um local físico em todo o mundo onde agrupamos datacenters. Chamamos cada grupo de datacenters lógicos de zona de disponibilidade. Cada região da AWS consiste em várias AZs isoladas e separadas fisicamente em uma área geográfica. Diferentemente de outros provedores de nuvem, que geralmente definem uma região como um único datacenter, o design de múltiplas AZs de cada região da AWS oferece vantagens para os clientes. Cada AZ tem energia, refrigeração e segurança física independentes e está conectada por meio de redes redundantes de latência ultrabaixa. Os clientes da AWS, focados em alta disponibilidade, podem projetar seus aplicativos para serem executados em várias AZs, a fim de obter tolerância a falhas ainda maior. As regiões de infraestrutura da AWS atendem aos mais altos níveis de segurança, conformidade e proteção de dados.

  - A AWS fornece uma presença global mais extensa do que qualquer outro provedor de nuvem. Para oferecer suporte à sua presença global e garantir que os clientes sejam atendidos em todo o mundo, a AWS abre novas regiões rapidamente. A AWS mantém várias regiões geográficas, incluindo regiões da América do Norte, África do Sul, América do Sul, Europa, China, Ásia-Pacífico e Oriente Médio.

- Zonas de disponibilidade
  - Uma zona de disponibilidade (AZ) é um ou mais datacenters distintos com energia, rede e conectividade redundantes em uma região da AWS. As AZs proporcionam aos clientes a capacidade de operar aplicativos e bancos de dados de produção com alta disponibilidade, tolerância a falhas e escalabilidade em níveis superiores aos que um único datacenter pode oferecer. Todas as AZs em uma região da AWS estão interconectadas por redes de alta largura de banda e baixa latência, usando fibra metropolitana dedicada e totalmente redundante para proporcionar redes de alto throughput e baixa latência entre AZs. Todo o tráfego entre as AZs é criptografado. A performance da rede é suficiente para realizar a replicação síncrona entre as AZs. As AZs particionam aplicativos para facilitar a alta disponibilidade. Se um aplicativo for particionado em várias AZs, as empresas estarão melhor isoladas e protegidas contra problemas como quedas de energia, raios, tornados e terremotos, entre outros. As AZs são fisicamente separadas por uma distância significativa (vários quilômetros) das outras AZs, embora todas estejam a um raio de até 100 km entre si.

## AWS Wavelength

O AWS Wavelength permite aos desenvolvedores criar aplicativos com latências inferiores a 10 milissegundos para dispositivos móveis e usuários finais. Os desenvolvedores da AWS podem implantar seus aplicativos nas Zonas do Wavelength, implantações de infraestrutura da AWS que incorporam serviços de computação e armazenamento da AWS aos datacenters dos provedores de telecomunicações na borda das redes 5G e acessam facilmente a variedade de serviços da AWS na região. Isso permite que os desenvolvedores forneçam aplicativos que exigem latências inferiores a 10 milissegundos, como streaming de jogos e vídeos ao vivo, inferência de machine learning na borda e realidade aumentada e virtual (AR/VR). O AWS Wavelength leva os serviços da AWS até a borda da rede 5G, minimizando a latência de conexão de um dispositivo móvel a um aplicativo. O tráfego de aplicativos pode acessar servidores de aplicativos em execução nas Zonas do Wavelength sem sair da rede da operadora de celular. Isso reduz os saltos de rede extras para a Internet, que podem resultar em latências de mais de 100 milissegundos, impedindo que os clientes aproveitem ao máximo os avanços de largura de banda e latência do 5G.

## AWS Outposts

O AWS Outposts leva serviços, infraestrutura e modelos operacionais nativos da AWS a praticamente qualquer datacenter, espaço de co-location ou instalações no local. Você pode usar as mesmas APIs, ferramentas e infraestrutura da AWS no local e na Nuvem AWS para oferecer uma experiência híbrida verdadeiramente consistente. O AWS Outposts foi projetado para ambientes conectados e pode ser usado para oferecer suporte a workloads que precisam permanecer on-premises devido à baixa latência ou atender a necessidades de processamento de dados locais.

## AWS IAM

O AWS Identity and Access Management (IAM) fornece controle de acesso refinado em toda a AWS. Com o IAM, é possível especificar quem pode acessar quais serviços e recursos e em que condições. Com as políticas do IAM, você gerencia permissões para seu quadro de funcionários e sistemas para garantir permissões com privilégios mínimos.

O IAM é um serviço da AWS oferecido sem custo adicional.

- Casos de uso
  - Com o IAM, você pode gerenciar as permissões da AWS para usuários e workloads do quadro de funcionários. Para usuários do quadro de funcionários, recomendamos que você use o AWS Single Sign-On (AWS SSO) para gerenciar o acesso a contas da AWS e permissões dentro dessas contas. O SSO da AWS torna mais fácil provisionar e gerenciar funções e políticas do IAM em sua organização da AWS. Para permissões de workloads, use funções e políticas do IAM e conceda apenas o acesso necessário para suas workloads.

- Políticas e permissões no IAM
  - Você gerencia o acesso na AWS criando políticas e anexando-as às identidades do IAM (usuários, grupos de usuários ou funções) ou aos recursos da AWS. Uma política é um objeto na AWS que, quando associado a uma identidade ou um recurso, define suas permissões. A AWS avalia essas políticas quando uma entidade de segurança do IAM (usuário ou função) faz uma solicitação. As permissões nas políticas determinam se a solicitação será permitida ou negada. A maioria das políticas são armazenadas na AWS como documentos JSON. A AWS oferece suporte a seis tipos de políticas: políticas baseadas em identidade, políticas baseadas em recurso, limites de permissões, SCPs do Organizations, ACLs e políticas de sessão.
  - As políticas do IAM definem permissões para uma ação, independentemente do método usado para executar a operação. Por exemplo, se uma política permitir a ação **GetUser**, um usuário com essa política poderá obter informações de usuários no AWS Management Console, na AWS CLI ou na API da AWS. Ao criar um usuário do IAM, você pode optar por permitir acesso ao console ou programático. Se o acesso ao console for permitido, o usuário do IAM poderá fazer login no console usando um nome de usuário e senha. Ou se o acesso programático for permitido, o usuário poderá usar as chaves de acesso para trabalhar com a CLI ou a API.

Para obter mais informações, acesse a [documentação oficial](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/access_policies.html) sobre AWS Identity and Access Management.

## Amazon EC2

- O que é virtualização?
  - É uma tecnologia que permite criar serviços de TI valiosos usando recursos que estão tradicionalmente vinculados a um determinado hardware. Com a virtualização, é possível usar a capacidade total de uma máquina física, distribuindo seus recursos entre muitos usuários ou ambientes. ([Saiba mais](https://www.redhat.com/pt-br/topics/virtualization/what-is-virtualization))

- O que é o Amazon Elastic Compute Cloud (Amazon EC2)?
  - O Amazon Elastic Compute Cloud (Amazon EC2) é um serviço da web que fornece capacidade computacional redimensionável na nuvem. Ele foi projetado para facilitar a computação em escala na Web para os desenvolvedores.

- Vantagens:
  - Controle
  - _Security_
  - AWS Services
  - _Low Cost_
  - _Uncomplicated_

- Tipos de planos e valores
  - Nível gratuito
    - O nível gratuito da AWS inclui 750 horas de instâncias Linux e Windows t2.micro (t3.micro para as regiões nas quais t2.micro não está disponível) todo mês durante um ano. Para permanecer no nível gratuito, use somente microinstâncias do EC2.
  - Sob demanda
    - Com as instâncias sob demanda, você paga pela capacidade computacional por hora ou por segundo, dependendo das instâncias executadas. Não são necessários compromissos de longo prazo nem pagamentos antecipados. Você pode aumentar ou diminuir a capacidade computacional dependendo das demandas do aplicativo e pagar apenas as taxas por hora especificadas para a instância utilizada.
  - Instâncias spot
    - As instâncias spot do Amazon EC2 permitem solicitar capacidade computacional extra do Amazon EC2 com desconto de até 90% em relação ao preço das instâncias sob demanda.
  - Savings Plans
    - Os Savings Plans são um modelo de precificação flexível que oferece preços baixos no uso do EC2 e Fargate, em troca de um compromisso com uma quantidade consistente de uso (medido em USD/hora) por um período de 1 ou 3 anos.
  - Host dedicados
    - Um host dedicado é um servidor físico do EC2 dedicado exclusivamente ao seu uso. Os hosts dedicados ajudam você a reduzir custos, permitindo que você use licenças existentes de software vinculadas ao servidor, incluindo Windows Server, SQL Server e SUSE Linux Enterprise Server (sujeito aos termos das suas licenças), além de ajudar a cumprir requisitos de conformidade.

- Bônus:
  - Criando uma Instancia com User Data:
      ```bash
      #!/bin/bash
      yum update -y
      yum install -y httpd
      systemctl start httpd
      systemctl enable httpd
      EC2ID=$(curl -s http://169.254.169.254/latest/meta-data/instance-id)
      echo '<center><h1>Este WebServer está LIVE: EC2ID </h1></center>' > /var/www/html/index.txt
      sed "s/EC2ID/$EC2ID/" /var/www/html/index.txt > /var/www/html/index.html
      ```

## AWS Batch

- O que é o AWS Batch?
  - O AWS Batch é um conjunto de capacidades de gerenciamento de lote que permite a desenvolvedores, cientistas e engenheiros executar com facilidade e eficiência centenas de milhares de trabalhos de computação em lote na AWS. O AWS Batch provisiona dinamicamente a quantidade e o tipo ideais de recursos de computação (p. ex., recursos de computação otimizados para CPU ou memória) com base nos requisitos de volume e de recursos específicos dos trabalhos em lote enviados. Com o AWS Batch, não é necessário instalar e gerenciar clusters de servidores ou software de computação em lote, permitindo que você se concentre em analisar resultados e solucionar problemas. O AWS Batch planeja, programa e executa suas cargas de trabalho de computação em lote usando o Amazon EC2 (disponível com instâncias spot) e recursos de computação da AWS com o AWS Fargate ou Fargate Spot.

- O que é computação em lote?
  - A computação em lotes é a execução de uma série de programas (“trabalhos”) em um ou mais computadores sem intervenção manual. Os parâmetros de entrada são predefinidos por meio de scripts, argumentos de linha de comando, arquivos de controle ou linguagem de controle de trabalhos. Um determinado trabalho em lotes pode depender da conclusão de trabalhos anteriores ou da disponibilidade de determinadas entradas. Com isso, a sequência e a programação de vários trabalhos passam a ser importantes, inviabilizando o processamento interativo.

- Quais são os benefícios da computação em lotes?
  - Permite deslocar o período de processamento de trabalhos para horários com disponibilidade de capacidade mais ou menos cara.
  - Evita recursos de computação ociosos, com intervenção e supervisão manuais frequentes.
  - Aumenta a eficiência promovendo maior utilização dos recursos de computação.
  - Ela também permite priorizar trabalhos, alinhando a alocação de recursos aos objetivos empresariais.

## Amazon EBS

- O que é o Elastic Block Store (Amazon EBS)?
  - O Amazon Elastic Block Store (Amazon EBS) é um serviço de armazenamento em blocos fácil de usar, escalável e de alta performance projetado para o Amazon Elastic Compute Cloud (Amazon EC2).

- Tipos de volumes do Amazon EBS
  - O Amazon EBS fornece vários tipos de volume que permitem otimizar o desempenho e o custo do armazenamento para uma ampla variedade de aplicativos. Esses tipos de volume estão divididos em duas categorias principais: armazenamento baseado em **SSD** para workloads transacionais, como bancos de dados, desktops virtuais e volumes de inicialização e armazenamento baseado em **HDD** para cargas de trabalho com taxa de transferência intensa, como MapReduce e processamento de logs.

## Amazon Elastic Load Balancing

- Como funciona
  - O Elastic Load Balancing (ELB) distribui automaticamente o tráfego de aplicações de entrada entre vários destinos e dispositivos virtuais em uma ou mais Zonas de disponibilidade (AZs). Há várias maneiras para começar a usar o Elastic Load Balancing. Você pode configurar um Application Load Balancer, Network Load Balancer ou Gateway Load Balancer usando as APIs, as Command Line Interfaces (CLIs – Interfaces de linha de comando) da AWS ou o Console de Gerenciamento da AWS.

O uso do Elastic Load Balancing com Auto Scaling permite criar aplicações altamente disponíveis e tolerantes a falhas com escalabilidade automática de capacidade de acordo com as variações de demanda.

- Application Load Balancer
  - O Application Load Balancer opera no nível da solicitação (camada 7), roteando o tráfego para destinos (instâncias do EC2, contêineres, endereços IP e funções do Lambda) com base no conteúdo da solicitação. Ideal para balanceamento de carga avançado de tráfego HTTP e HTTPS, o Application Load Balancer fornece roteamento de solicitação avançado direcionado à entrega de arquiteturas de aplicativos modernos, incluindo microsserviços e aplicativos baseados em contêiner. O Application Load Balancer simplifica e melhora a segurança do seu aplicativo, garantindo que as cifras e protocolos SSL/TLS mais recentes sejam usados o tempo todo.

- Network Load Balancer
  - O Network Load Balancer opera no nível de conexão (camada 4), roteando conexões para destinos (instâncias do Amazon EC2, microsserviços e contêineres) dentro da Amazon VPC, com base nos dados do protocolo IP. Ideal para balanceamento de carga de tráfego TCP e UDP, o Network Load Balancer é capaz de lidar com milhões de solicitações por segundo, mantendo latências ultrabaixas. O Network Load Balancer é otimizado para lidar com padrões de tráfego repentinos e voláteis ao usar um único endereço IP estático por zona de disponibilidade. Ele é integrado a outros serviços populares da AWS, como Auto Scaling, Amazon EC2 Container Service (ECS), Amazon CloudFormation e AWS Certificate Manager (ACM).

- Gateway Load Balancer
  - O Gateway Load Balancer ajuda você a implantar, dimensionar e gerenciar facilmente seus dispositivos virtuais de terceiros. Ele oferece um gateway para distribuir o tráfego entre vários dispositivos virtuais enquanto os dimensiona para cima ou para baixo, com base na demanda. Isso diminui os pontos potenciais de falha em sua rede e aumenta a disponibilidade.

  - Você pode encontrar, testar e comprar dispositivos virtuais de fornecedores terceirizados diretamente no AWS Marketplace. Essa experiência integrada agiliza o processo de implantação para que você veja o valor de seus dispositivos virtuais mais rapidamente, seja para continuar trabalhando com seus fornecedores atuais ou tentar algo novo.

- Classic Load Balancer
  - O Classic Load Balancer fornece balanceamento de carga básico em várias instâncias do Amazon EC2 e opera tanto no nível de solicitação quanto no nível de conexão. O Classic Load Balancer destina-se a aplicativos criados na rede EC2-Classic. Recomendamos o Application Load Balancer para tráfego de camada 7 e o Network Load Balancer para tráfego de camada 4 ao usar a Virtual Private Cloud (VPC).

## Amazon EC2 Auto Scaling

Adicione ou remova capacidade de computação para atender às mudanças na demanda

- O que é o AWS Auto Scaling?
  - O AWS Auto Scaling é um novo serviço da AWS para ajudar a otimizar o desempenho de aplicativos e reduzir custos de infraestrutura por meio da escalabilidade fácil e segura de vários recursos da AWS. O serviço simplifica a experiência de escalabilidade, permitindo escalar coleções de recursos relacionados usados por um aplicativo com apenas alguns cliques. O AWS Auto Scaling ajuda a configurar políticas de escalabilidade consistentes e congruentes em toda a pilha de infraestrutura usada por um aplicativo. O AWS Auto Scaling escala automaticamente os recursos conforme a necessidade para cumprir a estratégia de escalabilidade selecionada. Assim, você pode manter o desempenho e pagar apenas pelos recursos realmente necessários.

- Quais os benefícios do AWS Auto Scaling?

O AWS Auto Scaling é uma forma rápida e fácil de otimizar o desempenho e os custos dos aplicativos.

  - **Configure rapidamente a escalabilidade**: o AWS Auto Scaling oferece uma experiência unificada de escalabilidade para todos os recursos escaláveis usados pelos aplicativos. É possível ver a utilização média de todos os recursos escaláveis e definir rapidamente os níveis pretendidos de utilização para cada grupo de recursos semelhantes em uma interface simples e intuitiva.
  - **Tome decisões de escalabilidade com inteligência**: o AWS Auto Scaling permite automatizar a forma como recursos diferentes respondem às alterações de demanda. Estratégias de escalabilidade fáceis de compreender permitem priorizar disponibilidade, custos ou um equilíbrio ente os dois. O AWS Auto Scaling cria automaticamente todas as políticas de escalabilidade e define objetivos de acordo com sua preferência.
  - **Mantenha automaticamente o desempenho**: o AWS Auto Scaling monitora continuamente os recursos subjacentes dos aplicativos para garantir que operem nos níveis de performance desejados. Quando ocorrem picos de demanda, o AWS Auto Scaling aumenta automaticamente a capacidade dos recursos restritos para manter uma alta qualidade de serviço.
  - **Estime os custos e evite gastos desnecessários**: o AWS Auto Scaling pode ajudar a otimizar as eficiências de utilização e custo do consumo de serviços da AWS. Assim, você paga apenas pelos recursos realmente necessários. Quando a demanda cai, o AWS Auto Scaling remove automaticamente toda a capacidade excessiva de recursos, evitando gastos desnecessários.

- Quando devo usar o AWS Auto Scaling?
  - Você deve usar o AWS Auto Scaling para aplicativos que usam um ou mais recursos escaláveis e estão sujeitos a cargas variáveis. Um bom exemplo seria um aplicativo web de comércio eletrônico que recebe tráfego variável durante o dia. O aplicativo segue uma arquitetura padrão de três camadas: o Elastic Load Balancing distribui o tráfego recebido, o Amazon EC2 é a camada de computação e o DynamoDB é a camada de dados. Neste caso, o AWS Auto Scaling escalará um ou mais grupos do EC2 Auto Scaling e tabelas do DynamoDB usados pelo aplicativo para responder à curva de demanda.

- Como posso começar a usar o AWS Auto Scaling?
  - O AWS Auto Scaling permite a seleção de aplicativos de acordo com tags de recursos ou com pilhas do AWS CloudFormation. Com apenas alguns cliques, é possível criar um plano de escalabilidade para um aplicativo. Esse plano define como cada um dos recursos usados pelo aplicativo será escalado. Para cada recurso, o AWS Auto Scaling cria uma política de escalabilidade de rastreamento direcionada com a métrica mais popular para esse tipo de recurso e mantém essa métrica em um valor direcionado para a estratégia de escalabilidade selecionada. Para definir os valores das métricas de recursos, você pode optar entre três recomendações de escalabilidade predefinidas que otimizam disponibilidade, otimizam custos ou equilibram esses dois critérios. Ou, se preferir, você pode definir seus próprios valores pretendidos. Além disso, o AWS Auto Scaling define automaticamente os valores mínimo e máximo dos recursos.

- Leitura complementar
  - [Top 5 AWS Auto Scaling Strategies](https://www.missioncloud.com/blog/top-five-aws-auto-scaling-strategies)

## Amazon Elastic Container Service (Amazon ECS)

- O que é o Amazon Elastic Container Service?
  - O Amazon Elastic Container Service (ECS) é um serviço de gerenciamento de contêineres altamente escalável e de alta performance com suporte a contêineres do Docker, o que permite executar facilmente aplicações em um cluster gerenciado de instâncias do Amazon Elastic Compute Cloud (Amazon EC2). O Amazon ECS elimina a necessidade de instalar, operar e alterar a escala de sua própria infraestrutura de gerenciamento de clusters. Com chamadas de API simples, você pode executar e interromper aplicações habilitadas para contêiner, consultar o estado completo do seu cluster e acessar muitos recursos familiares, como grupos de segurança, Elastic Load Balancing, volumes do Amazon Elastic Block Store (EBS) e funções do Identity Access Management (IAM). Utilize o Amazon ECS para programar a colocação de contêineres no cluster com base em suas necessidades de recursos e requisitos de disponibilidade. Você também pode integrar agendadores próprios ou de terceiros para atender a requisitos específicos dos negócios ou da aplicação.

- Por que devo usar o Amazon ECS?
  - O Amazon ECS facilita a utilização de contêineres como um bloco de construção para as suas aplicações, eliminando a necessidade de você instalar, operar e dimensionar sua própria infraestrutura de gerenciamento de cluster. O Amazon ECS permite programar aplicações, serviços e processos de lotes de longa duração usando contêineres Docker. O Amazon ECS mantém a disponibilidade da aplicação e permite expandir ou reduzir seus contêineres para atender aos requisitos de capacidade da aplicação. O Amazon ECS é integrado a recursos familiares como Elastic Load Balancing, volumes do EBS, Amazon Virtual Private Cloud (VPC) e IAM. APIs simples permitem integrar e usar seus próprios agendadores ou conectar o Amazon ECS a seu processo atual de distribuição de software.

- Qual é a diferença entre o Amazon ECS e o AWS Lambda?
  - O Amazon ECS é um serviço de gerenciamento de contêineres do Docker altamente escalável que permite executar e gerenciar aplicativos distribuídos em contêineres do Docker. O AWS Lambda é um serviço de computação de tarefas orientadas por eventos que executa seu código em resposta a “eventos”, como mudanças em dados, cliques em sites ou mensagens de outros Serviços da AWS sem necessidade de gerenciamento de qualquer infraestrutura de computação.

## Amazon Simple Storage Service (S3)

- O que é o Amazon S3?
  - O Amazon S3 é um armazenamento de objetos criado para armazenar e recuperar qualquer quantidade de dados de qualquer local na Internet. Ele é um serviço de armazenamento simples que oferece uma infraestrutura de armazenamento de dados com escalabilidade infinita a um custo bastante reduzido.

- O que posso fazer com o Amazon S3?
  - O Amazon S3 disponibiliza uma interface de serviço da Web simples que pode ser usada para armazenar e recuperar qualquer quantidade de dados, a qualquer momento, de qualquer lugar na Web. Com esse web service, os desenvolvedores podem criar facilmente aplicativos que usam armazenamento na Internet. Como o Amazon S3 é altamente escalável e você só paga pelo que usa, é possível começar com um porte reduzido e expandir o aplicativo da forma desejada, sem comprometer o desempenho ou a confiabilidade.
  - O Amazon S3 também foi concebido para ser altamente flexível. Armazene qualquer tipo ou volume de dados que você necessite, leia a mesma porção de dados um milhão de vezes ou apenas para a recuperação de desastres em casos de emergência, crie uma aplicação FTP simples ou um aplicativo da Web avançado semelhante ao site de vendas da Amazon.com. O Amazon S3 permite que os desenvolvedores se concentrem na inovação e não em descobrir como armazenar dados.

- Qual quantidade de dados é possível armazenar no Amazon S3?
  - O volume total de dados e o número de objetos que você pode armazenar são ilimitados. Objetos individuais do Amazon S3 podem variar em tamanho, desde um mínimo de 0 byte até um máximo de 5 terabytes. O tamanho do maior objeto que pode ser carregado em um único PUT é 5 gigabytes. Para objetos maiores do que 100 megabytes, os clientes devem considerar utilizar o recurso de multipart upload .

- Quais categorias de armazenamento o Amazon S3 oferece?
  - O Amazon S3 oferece uma ampla variedade de classes de armazenamento para diferentes casos de uso. Elas incluem S3 Standard, para armazenamento geral de dados acessados com frequência, S3 Intelligent-Tiering, para dados com padrões de acesso desconhecido ou dinâmico, S3 Standard-Infrequent Access (S3 Standard – IA) e S3 One Zone-Infrequent Access (S3 One Zone – IA) para dados de longa vida, mas acessados com menos frequência e Amazon S3 Glacier (S3 Glacier) e Amazon S3 Glacier Deep Archive (S3 Glacier Deep Archive) para preservação digital e arquivamento de dados de longo prazo. Você pode saber mais sobre essas classes de armazenamento na página Classes de armazenamento do Amazon S3.

- Qual a confiabilidade do Amazon S3?
  - O Amazon S3 concede a todos os desenvolvedores o acesso para a mesma infraestrutura de armazenamento de dados altamente escalável, disponível, rápida e econômica usada pela Amazon para operar a sua própria rede global de sites. As classes de armazenamento S3 Standard, S3 Standard – IA e S3 One Zone – IA foram projetadas para oferecer respectivamente 99,99%, 99,9% e 99,5% de disponibilidade, enquanto as classes S3 Glacier e S3 Glacier Deep Archive foram projetadas para oferecer 99,99% de disponibilidade e SLA de 99,9%. Todas essas classes de armazenamento são amparadas pelo Acordo de nível de serviço do Amazon S3.

- O que a Amazon faz com meus dados no Amazon S3?
  - A Amazon armazenará os dados e controlará o uso associado para efeitos de cobrança. A Amazon não acessará seus dados para nenhuma outra finalidade que não seja a da oferta do Amazon S3, exceto quando exigido por lei. Consulte o Acordo de licenciamento da Amazon Web Services para obter mais detalhes.

- Como os dados do Amazon S3 são organizados?
  - O Amazon S3 é um simples depósito de objetos com base em chave. Ao armazenar os dados, você atribui uma chave de objeto exclusiva que posteriormente pode ser usada para recuperar os dados. As chaves podem ser qualquer string, e podem ser construídas para imitar atributos hierárquicos. Como alternativa, você pode usar o S3 Object Tagging para organizar dados em todos os buckets e/ou prefixos do S3.

## Amazon CloudFront

O Amazon CloudFront é um serviço rápido de rede de entrega de conteúdo (CDN) que entrega dados, vídeos, aplicativos e APIs a clientes em todo o mundo com segurança, baixa latência e altas velocidades de transferência em um ambiente de uso facilitado para desenvolvedores. O CloudFront é integrado com a AWS; ambos são locais físicos conectados diretamente à infraestrutura global da AWS, bem como a outros serviços da AWS. O CloudFront funciona de forma transparente com serviços como AWS Shield para mitigação de ataques DDoS; Amazon S3, Elastic Load Balancing ou Amazon EC2 como origens para os aplicativos; e Lambda@Edge para executar código personalizado mais perto dos usuários dos clientes e personalizar a experiência dos usuários. Por fim, se você usar origens na AWS, como Amazon S3, Amazon EC2 ou Elastic Load Balancing, a transferência de dados entre esses serviços e o CloudFront não será cobrada.

Você pode começar a usar a rede de entrega de conteúdo em questão de minutos com as mesmas ferramentas da AWS que você já conhece: APIs, Console de Gerenciamento da AWS, AWS CloudFormation, ILCs e SDKs. A CDN da Amazon oferece um modelo de definição de preço simples com pagamento conforme o uso, sem taxas adiantadas ou contratos obrigatórios de longo prazo. O suporte à CDN está incluso na sua assinatura atual do AWS Support.

- Otimizações de rede para desempenho ideal
  - O Amazon CloudFront mede continuamente a conectividade com a Internet, o desempenho e a computação para encontrar a melhor maneira de encaminhar solicitações para a nossa rede, levando em conta o desempenho, a carga, o status operacional e outros fatores para oferecer a melhor experiência em tempo real. O Amazon CloudFront também está em execução no backbone da rede global da AWS, que permite a transmissão eficiente de solicitações entre os pontos de presença do CloudFront e outros serviços da AWS, entre regiões e aplicativos. As otimizações de camada de rede, como TCP de abertura rápida, solicitação de recolhimento, conexões keep-alive e muito mais, permitem que o Amazon CDN acelere o conteúdo estático e dinâmico para melhorar o desempenho do usuário.

- Conteúdo dinâmico ou estático
  - Sites e aplicativos modernos são uma rica mistura de conteúdo dinâmico, personalizado e estático. Os microsserviços também expõem números crescentes de APIs e solicitações entre componentes. O Amazon CloudFront é otimizado para ambos, fornecendo flexibilidade extensiva para otimizar o comportamento do cache, juntamente com otimizações de latência e taxa de transferência de camada de rede. O CloudFront dá suporte ao protocolo WebSocket, bem como o protocolo HTTP com os seguintes métodos HTTP: GET, HEAD, POST, PUT, DELETE, OPTIONS e PATCH. Isso significa que você pode melhorar o desempenho de sites dinâmicos com formulários da web, caixas de comentários e login, botões "adicionar ao carrinho", aplicativos baseados no WebSocket ou outros recursos que fazem upload de dados de usuários finais. Além disso, você agora pode usar um único nome de domínio para entregar todo o site por meio do CloudFront, acelerando os processos de download e carga do seu site.

- Grandes bibliotecas e ativos de mídia
  - À medida que a infraestrutura de rede global cresceu e melhorou, a retenção de cache surgiu como um contribuinte essencial para o desempenho. A rede de entrega de conteúdo (CDN) é arquitetada para manter os objetos por mais tempo no cache e para reduzir a rotatividade de cache. Técnicas como cache hierárquico e otimização de deduplicação de objetos no cache ajudam a maximizar a retenção de cache.

## AWS Billing

- Como funciona
  - A página do AWS Bills oferece uma exibição mensal de seus custos passíveis de cobrança. Para períodos de faturamento mensal que ainda não foram encerrados, a página do Bills exibirá as cobranças estimadas mais recentes com base nos serviços medidos até o momento. As faturas são geradas quando um período de cobrança mensal é encerrado ou quando assinaturas ou compras únicas são efetuadas. Para usuários do AWS Organizations, os usuários conectados à conta de gerenciamento podem visualizar cobranças consolidadas para todas as contas-membro, com detalhes em nível de conta disponíveis na guia “Charges by account” (Cobranças por conta). A página do AWS Bills fornece detalhes de serviços prestados pela AWS e compras feitas no AWS Marketplace. Para usuários do AWS Billing Conductor, a página do AWS Bills oferece dados pro forma para contas-membro e contas principais de um grupo de faturamento. As contas de gerenciamento podem alternar entre visualizações de dados faturáveis e pro forma.

Casos de uso

- Fácil acesso aos dados
  - A página do AWS Bills está disponível para todas as contas da AWS, sem necessidade de outras configurações. Você pode encontrar facilmente faturas e dados de faturamento desde o início da conta, permitindo análises ou auditorias de histórico.

- Reconcilie faturas com dados de faturamento detalhados
  - Visualize um resumo do total de cobranças por período de faturamento mensal, recupere PDFs de faturas e arquivos CSV com dados complementares e analise os detalhes para entender como suas cobranças são calculadas, se os custos são cobrados por solicitação de API, instância-hora ou GB-mês.

- Faturamento consolidado
  - Use o recurso de faturamento consolidado do AWS Organizations para combinar todas as suas contas-membro em uma conta de gerenciamento e receber uma única fatura.

- CapEx vs OpEx em Computação em Nuvem
  - O cenário de TI empresarial mudou rapidamente na última nuvem, com as organizações optando pelas vantagens da relação aos data centers locais. Com essa mudança, as empresas estão vendo um aumento no OpEx e uma redução no CapEx. O que essa mudança significa para o seu negócio? 

  - Despesas de capital (CapEx): 
    - É o gasto inicial de dinheiro (todos juntos) em infraestrutura física e, em seguida, deduzindo essa despesa inicial ao longo do tempo. O custo inicial do CapEx tem um valor que reduz ao longo do tempo. Todas as despesas incorridas para benefícios de prazos no futuro estão sob CapEx.

  - Despesas Operacionais (OpEx): 
    - É como um serviço de pagamento conforme o uso. Você pode deduzir esta despesa no mesmo ano em que a gastar. Não há custo inicial, pois você paga por um serviço ou produto à medida que o usa. É como o nome sugere, a operação diária.

## AWS Budgets - Orçamento -> alerta 80% ($ 500/mensal) (antes)

- O Orçamentos da AWS permite que você defina orçamentos personalizados para rastrear seu custo e uso, desde os casos de uso mais simples aos mais complexos. Com o Orçamentos da AWS, você pode escolher ser alertado por e-mail ou notificação SNS quando o custo real ou previsto e o uso excederem o limite do seu orçamento ou quando a utilização ou a cobertura reais de seus Savings Plans e RI cair abaixo do limite desejado.

## AWS Cost Explorer - Relatório billing (depois)

- O Explorador de Custos da AWS tem uma interface fácil de usar que permite visualizar, entender e gerenciar os custos e o uso da AWS ao longo do tempo. Comece a usar rapidamente criando relatórios personalizados que analisam dados de custos e uso. Analise dados de forma resumida (por exemplo, custos e uso totais em todas as contas) ou detalhe os dados de custos e uso para identificar tendências, determinar causadores de custos e detectar anomalias.

## AWS Plans

Na AWS, queremos que você seja bem-sucedido. Nossos planos de suporte foram criados para oferecer a combinação correta de ferramentas e acesso ao conhecimento. Dessa forma, você pode ter sucesso com a AWS e otimizar a performance, gerenciar os riscos e manter o controle sobre os custos.

O suporte básico está incluído para todos os clientes da AWS e oferece:

- **Atendimento ao cliente e comunidades**: acesso ao atendimento ao cliente, documentação, whitepapers e ao AWS re:Post 24 horas por dia, 7 dias por semana.
- **AWS Trusted Advisor**: acesso às principais verificações do Trusted Advisor e orientações para provisionar seus recursos de acordo com as práticas recomendadas para aumentar a performance e aprimorar a segurança.
- **AWS Personal Health Dashboard**: uma visualização personalizada da integridade dos serviços da AWS e envio de alertas quando seus recursos forem afetados.

## AWS Organizations

O AWS Organizations ajuda você a gerenciar e controlar seu ambiente de maneira centralizada à medida que os negócios e seus recursos da AWS expandem. Usando o AWS Organizations, você pode criar novas contas da AWS e alocar recursos, agrupar contas para organizar seus fluxos de trabalho, aplicar políticas a contas ou grupos para governança e simplificar o faturamento usando um único método de pagamento para todas as suas contas.

Além disso, o AWS Organizations é integrado a outros serviços da AWS para que você possa definir configurações centrais, mecanismos de segurança, requisitos de auditoria e compartilhamento de recursos entre contas na sua organização. O AWS Organizations está disponível para todos os clientes da AWS sem custos adicionais.

## AWS Pricing Calculator

Configure uma estimativa de custo exclusivo que atenda às suas necessidades de negócios ou pessoais com produtos e serviços da AWS.

- Como funciona?
  - Adicione o serviço que você deseja calcular
  - Configure o serviço adicionado
  - Visualize o total da estimativa

## AWS Compliance (Conformidade)

O programa de conformidade da AWS permite que nossos clientes compreendam os controles robustos estabelecidos na AWS para manter a segurança e a proteção de dados. A integração de recursos de serviços com foco em governança e de fácil auditoria a padrões de auditoria ou conformidade aplicáveis permite que os habilitadores de conformidade da AWS aproveitem os programas tradicionais, ajudando clientes a se estabelecerem e operarem em um ambiente de controle de segurança da AWS.

Os padrões de TI com os quais estamos em conformidade são divididos por certificados e declarações; leis, regulamentos e privacidade; e alinhamentos e frameworks. Certificações e declarações de conformidade avaliadas por um auditor independente terceirizado e que resultam em uma certificação, um relatório de auditoria ou uma declaração de conformidade. Os clientes da AWS permanecem responsáveis pela conformidade com os programas de privacidade e com as leis e os regulamentos de conformidade aplicáveis. Os alinhamentos e as estruturas de trabalho de conformidade incluem requisitos publicados de segurança ou conformidade para um propósito específico, como um determinado setor ou função.

## AWS Artifact

**O QUE É O AWS ARTIFACT?**

O AWS Artifact, disponível no console, é um portal de autoatendimento para recuperação de artefatos de auditoria que oferece aos clientes acesso sob demanda à documentação de conformidade e aos acordos da AWS.

Você pode usar os relatórios do AWS Artifact para fazer download de documentos de segurança e conformidade, como os relatórios de certificações ISO, Payment Card Industry (PCI – Setor de cartões de pagamento) e Organization Control (SOC – Controles de sistema e organização).

Você pode usar o AWS Artifact Agreements para examinar, aceitar e acompanhar o status de acordos da AWS como o Business Associate Addendum (BAA – Adendo de associado comercial).

**QUEM TEM ACESSO AO AWS ARTIFACT?**

Todas as contas da AWS têm acesso ao AWS Artifact. Os usuários raiz e do IAM com permissões de administrador podem fazer o download de todos os artefatos de auditoria disponíveis na conta concordando com os termos e condições associados.

Será necessário conceder aos usuários do IAM permissões de acesso não administrativas para o AWS Artifact usando as permissões do IAM. Com isso, você poderá conceder a um usuário o acesso ao AWS Artifact e restringir o acesso a outros serviços e recursos da conta da AWS. Para obter informações sobre como conceder acesso usando o IAM, consulte esse tópico de ajuda na documentação do AWS Artifact.

**COMO PERMITO QUE OUTROS USUÁRIOS ACESSEM O AWS ARTIFACT AGREEMENTS?**

Sua conta administrativa tem todas as permissões necessárias para usar o AWS Artifact. No entanto, documentos e acordos diferentes podem exigir a delegação de permissões distintas para diversos usuários. Você pode delegar permissões usando as políticas do IAM.

**O QUE É UM ARTEFATO DE AUDITORIA?**

Um artefato de auditoria é um elemento de evidência que demonstra que uma organização segue um processo documentado ou cumpre um requisito específico. Os artefatos de auditoria são coletados e arquivados ao longo do ciclo de vida de desenvolvimento de um sistema e servem como evidência em auditorias e avaliações internas e/ou externas.

No momento, o AWS Artifact oferece aos clientes relatórios e acordos que podem ser usados como artefatos de auditoria.

**COMO FAÇO PARA COMPARTILHAR ARTEFATOS DE AUDITORIA COM OS AUDITORES?**

Muitas vezes, será necessário que os auditores tenham acesso aos relatórios de conformidade da AWS. Você pode fazer isso facilmente criando credenciais de usuário do IAM específicas para cada auditor, configurando-as para limitar o acesso aos relatórios relevantes para a auditoria conduzida pelo auditor. Para obter mais informações, veja este tópico de ajuda na documentação do AWS Artifact.

**COMO POSSO USAR ESSES ARTEFATOS PARA CUMPRIR REQUISITOS DE AUDITORIA?**

Você pode fornecer os artefatos de auditoria da AWS aos auditores ou reguladores como evidência dos controles de segurança da AWS.

Além disso, é possível usar a orientação sobre responsabilidades fornecida por alguns artefatos de auditoria da AWS para projetar a arquitetura de nuvem. Essa orientação ajuda a determinar os controles de segurança adicionais que devem ser implantados para apoiar casos de uso específicos do sistema.

**EXISTE UM LIMITE PARA O NÚMERO DE ARTEFATOS QUE POSSO OBTER POR DOWNLOAD?**

Não. Você pode acessar e fazer o download de todos os artefatos a qualquer momento, tantas vezes quanto precisar.

## AWS Shared Responsibility Model

![image](https://user-images.githubusercontent.com/56324728/180885525-cddfc412-cf17-4c5b-acbe-5f001ad550bc.png)

Segurança e conformidade constituem uma responsabilidade compartilhada entre a AWS e o cliente. Esse modelo compartilhado pode auxiliar a reduzir os encargos operacionais do cliente à medida que a AWS opera, gerencia e controla os componentes do sistema operacional do host e a camada de virtualização, até a segurança física das instalações em que o serviço opera. O cliente assume a gestão e a responsabilidade pelo sistema operacional convidado (inclusive atualizações e patches de segurança), por outros softwares de aplicativos associados e pela configuração do firewall do grupo de segurança fornecido pela AWS. Os clientes devem examinar cuidadosamente os serviços que escolherem, pois suas respectivas responsabilidades variam de acordo com os serviços utilizados; a integração desses serviços ao seu ambiente de TI e as leis e regulamentos aplicáveis. A natureza dessas responsabilidades compartilhadas também oferece a flexibilidade e o controle do cliente necessários para a implantação. Como pode ser visto no gráfico abaixo, esta distinção entre responsabilidades é denominada normalmente como segurança “da” nuvem versus segurança “na” nuvem.

**Responsabilidade da AWS**: “segurança da nuvem”: a AWS é responsável por proteger a infraestrutura que executa todos os serviços oferecidos na Nuvem AWS. Essa infraestrutura é composta por hardware, software, redes e instalações que executam os Serviços de nuvem AWS.

**Responsabilidade do cliente**: “segurança na nuvem”: a responsabilidade do cliente será determinada pelos Serviços de nuvem AWS selecionados por ele. Isso determina a quantidade de operações de configuração que o cliente deverá executar como parte de suas responsabilidades de segurança. Por exemplo, um serviço como o Amazon Elastic Compute Cloud (Amazon EC2) é categorizado como Infrastructure as a Service (IaaS – Infraestrutura como serviço) e, dessa forma, exige que o cliente execute todas as tarefas necessárias de configuração e gerenciamento da segurança. Os clientes que implantam uma instância do Amazon EC2 são responsáveis pelo gerenciamento do sistema operacional convidado (o que inclui atualizações e patches de segurança), por qualquer utilitário ou software de aplicativo instalado pelo cliente nas instâncias, bem como pela configuração do firewall disponibilizado pela AWS (chamado de grupo de segurança) em cada instância. Para serviços abstraídos, como o Amazon S3 e o Amazon DynamoDB, a AWS opera a camada de infraestrutura, o sistema operacional e as plataformas, e os clientes acessam os endpoints para armazenar e recuperar dados. Os clientes são responsáveis por gerenciar os dados deles (o que inclui opções de criptografia), classificando os ativos e usando as ferramentas de IAM para aplicar as permissões apropriadas.

Esse modelo de responsabilidade compartilhada entre o cliente e a AWS também se estende aos controles de TI. Assim como a responsabilidade para operar o ambiente de TI é compartilhada entre a AWS e os seus clientes, o mesmo ocorre com o gerenciamento, a operação e a verificação de controles compartilhados de TI. A AWS pode auxiliar a reduzir os encargos operacionais de controles do cliente gerenciando os controles associados à infraestrutura física implementada no ambiente da AWS que anteriormente eram gerenciados pelo cliente. Já que cada cliente é implantado de forma diferente na AWS, os clientes podem aproveitar a transferência do gerenciamento de determinados controles de TI para a AWS, resultando em um (novo) ambiente de controle distribuído. Os clientes podem usar a documentação sobre controle e conformidade da AWS para executar seus procedimentos de avaliação e verificação de controle, conforme for necessário. Veja abaixo exemplos de controles gerenciados pela AWS, por clientes da AWS e/ou por ambos.

**Controles herdados**: controles que um cliente herda completamente da AWS.

- Controles físicos e ambientais

**Controles compartilhados**: controles que se aplicam à camada de infraestrutura e às camadas do cliente, mas em perspectivas ou contextos totalmente distintos. Em um controle compartilhado, a AWS disponibiliza os requisitos de infraestrutura e o cliente deve disponibilizar sua própria implementação de controles dentro do uso de Serviços da AWS. Os exemplos incluem:

- Gerenciamento de patches: a AWS é responsável pela aplicação de patches e pela correção de falhas na infraestrutura, mas os clientes são responsáveis pela aplicação de patches em seu SO convidado e nos seus aplicativos.
- Gerenciamento de configuração: a AWS mantém a configuração dos dispositivos de infraestrutura, mas o cliente é responsável pela configuração dos seus próprios bancos de dados, aplicativos e sistemas operacionais convidados.
- Conhecimentos e treinamento: a AWS treina funcionários da AWS, mas o cliente deve treinar seus próprios funcionários.

**Específicos do cliente**: controles que são de responsabilidade exclusiva do cliente com base no aplicativo implantado nos serviços da AWS. Os exemplos incluem:

- Proteção ou zona de segurança de serviços e comunicação, que pode exigir que o cliente roteie dados para ambientes de segurança específicos.

## AWS WAF & AWS Shield

**AWS WAF**

O **AWS WAF** é um firewall de aplicações Web que ajuda a proteger suas aplicações Web ou APIs contra bots e exploits comuns na Web que podem afetar a disponibilidade, comprometer a segurança ou consumir recursos em excesso. O AWS WAF oferece controle sobre como o tráfego atinge suas aplicações, permitindo que você crie regras de segurança que controlam o tráfego de bots e bloqueiam padrões de ataque comuns, como injeção de SQL ou cross-site scripting. Você também pode personalizar regras que filtram padrões de tráfego específicos. Você pode começar rapidamente usando regras gerenciadas para o AWS WAF, um conjunto pré-configurado de regras gerenciadas pela AWS ou por vendedores do AWS Marketplace para resolver problemas como os dez principais riscos de segurança e bots automatizados do OWASP que consomem recursos em excesso, distorcem métricas ou podem causar um tempo de inatividade. Essas regras são atualizadas regularmente conforme surgem novos problemas. O AWS WAF inclui uma API multifuncional que você pode usar para automatizar a criação, a implantação e a manutenção de regras de segurança.

Você pode implantar o AWS WAF no Amazon CloudFront como parte de uma solução de CDN, no Application Load Balancer que faz frente aos servidores Web ou de origem executados no EC2, no Amazon API Gateway para suas APIs REST ou no AWS AppSync para suas APIs GraphQL. Com o AWS WAF, você paga apenas pelo que usar e o preço é baseado em quantas regras você implanta e quantas solicitações da Web sua aplicação recebe.

**AWS SHIELD**

O **AWS Shield** é um serviço gerenciado de proteção contra DDoS (Negação de serviço distribuída) que protege os aplicativos executados na AWS. O AWS Shield oferece de detecção e mitigações em linha automáticas e sempre ativas que minimizam o tempo de inatividade e a latência dos aplicativos, fornecendo proteção contra DDoS sem necessidade de envolver o AWS Support. O AWS Shield tem dois níveis, Standard e Advanced.

Todos os clientes da AWS se beneficiam gratuitamente com as proteções automáticas do AWS Shield Standard. O AWS Shield Standard protege contra os ataques de DDoS mais comuns, que ocorrem com frequência nas camadas de rede e transporte e visam sites ou aplicativos web. Ao usar o AWS Shield Standard com o Amazon CloudFront e o Amazon Route 53, você recebe uma proteção abrangente de disponibilidade contra todos os ataques conhecidos de infraestrutura (camadas 3 e 4).

Para obter níveis mais altos de proteção contra ataques direcionados a seus aplicativos executados em recursos do Amazon Elastic Compute Cloud (EC2), Elastic Load Balancing (ELB), Amazon CloudFront, AWS Global Accelerator e Amazon Route 53, você pode inscrever-se no AWS Shield Advanced. Além das proteções nas camadas de rede e transporte fornecidas com a versão Standard, o AWS Shield Advanced fornece detecção e mitigação adicionais contra ataques grandes e sofisticados de DDoS, visibilidade praticamente em tempo real aos ataques e integração ao AWS WAF, um firewall para aplicação Web. Além disso, o AWS Shield Advanced oferece acesso 24 horas, 7 dias na semana, ao AWS Shield Response Team (SRT) e proteção contra picos relacionados a DDoS em suas taxas do Amazon Elastic Compute Cloud (EC2), Elastic Load Balancing (ELB), Amazon CloudFront, AWS Global Accelerator e Amazon Route 53.

O AWS Shield Advanced está disponível globalmente em todos os locais da borda do Amazon CloudFront, AWS Global Accelerator e Amazon Route 53. Você pode proteger suas aplicações Web hospedadas em qualquer lugar do mundo implantando o Amazon CloudFront na frente de sua aplicação. Os servidores de origem podem ser o Amazon Simple Storage Service (S3), Amazon Elastic Compute Cloud (EC2), Elastic Load Balancing (ELB) ou um servidor personalizado fora da AWS. Você também pode ativar o AWS Shield Advanced diretamente no Elastic Load Balancing ou no Amazon EC2 nas seguintes regiões da AWS: Norte da Virgínia, Ohio, Oregon, Norte da Califórnia, Montreal, São Paulo, Irlanda, Frankfurt, Londres, Paris, Estocolmo, Singapura, Tóquio, Sydney, Seul, Mumbai, Milão e Cidade do Cabo.

## AWS Security Services

**AWS INSPECTOR**

O Amazon Inspector é um serviço automatizado de gerenciamento de vulnerabilidade que verifica continuamente as workloads da AWS em busca de vulnerabilidades de software e exposição não intencional à rede.

**AWS TRUSTED ADVISOR**

O AWS Trusted Advisor faz recomendações que ajudam você a seguir as práticas recomendadas da AWS. O Trusted Advisor avalia a sua conta por meio de verificações. Essas verificações identificam formas de otimizar sua infraestrutura da AWS, aumentar a segurança e o desempenho, reduzir os custos gerais e monitorar as cotas do serviço. Depois, você pode seguir as recomendações da verificação para otimizar seus recursos e serviços.
Os clientes do AWS Basic Support e do AWS Developer Support podem acessar as principais verificações de segurança e todas verificações de cotas de serviço. Os clientes do AWS Business Support e do AWS Enterprise Support podem acessar todas as verificações, incluindo otimizações de custo, segurança, tolerâncias a falhas, desempenho e cotas de serviço. Para obter uma lista completa de verificações e descrições, consulte as Práticas recomendadas do Trusted Advisor.

**CLOUD TRAIL**

O AWS CloudTrail monitora e registra a atividade da conta por toda a infraestrutura da AWS, oferecendo controle sobre o armazenamento, análise e ações de remediação.

## Amazon Athena

**O que é o Amazon Athena?**

O Amazon Athena é um serviço de consultas interativas que facilita a análise de dados no Amazon S3 usando SQL padrão. O Athena não usa servidor, de forma que não existe uma infraestrutura para configurar ou gerenciar; é possível começar a analisar os dados imediatamente. Não é necessário nem mesmo carregar dados no Athena, ele trabalha diretamente com os dados armazenados no S3. Para começar, basta fazer login no Athena Management Console, definir seu esquema e dar início às consultas. O Amazon Athena usa o Presto, com suporte completo a SQL padrão, e funciona com diversos formatos de dados padrão, como CSV, JSON, ORC, Apache Parquet e Avro. Apesar de o Amazon Athena ser ideal para queries rápidas ad hoc e se integrar com o Amazon QuickSight para facilidade de visualização, ele também consegue lidar com análise complexa, inclusive grandes junções, funções de janela e arrays.

**O que posso fazer com o Amazon Athena?**

O Amazon Athena ajuda você analisar os dados armazenados no Amazon S3. Você pode usar o Athena para rodar queries ad hoc usando SQL padrão ANSI, sem a necessidade de agregar ou carregar os dados no Athena. O Amazon Athena pode processar datasets desestruturados, semi-estruturados e estruturados. Os exemplos incluem formatos de dados CSV, JSON e Avro, além de formatos de dados colunares como Apache Parquet e Apache ORC. O Amazon Athena se integra com o Amazon QuickSight para facilidade de visualização. Você também pode usar o Amazon Athena para gerar relatórios ou explorar dados com ferramentas de inteligência de negócios ou clientes SQL conectados por meio de um driver ODBC ou JDBC.

**Qual é a tecnologia por trás do Amazon Athena?**

O Amazon Athena usa o Presto com suporte completo a SQL padrão, e funciona com diversos formatos de dados padrão, como CSV, JSON, ORC, Avro e Parquet. O Athena consegue lidar com análises complexas, inclusive grandes associações, funções de janela e matrizes. Como o Amazon Athena usa o Amazon S3 como datastore subjacente, ele é altamente disponível e durável, com dados armazenados em redundância em vários locais e vários dispositivos em cada local.

**Como faço para começar a usar o Amazon Athena?**

Para começar a usar o Amazon Athena, basta fazer login no Console de Gerenciamento da AWS para o Athena e criar seu esquema escrevendo statements DDL no console ou usando um assistente de criação de tabelas. Então, você pode começar a consultar dados usando o editor de queries incorporado. O Athena faz queries dos dados diretamente pelo Amazon S3, para que nenhum carregamento seja necessário.

## Amazon Macie

**O que é o Amazon Macie?**

O Amazon Macie é um serviço de segurança e privacidade de dados totalmente gerenciado que usa machine learning e correspondência de padrões para descobrir e proteger seus dados confidenciais na AWS.

**Quais são os principais benefícios do Amazon Macie?**

O Amazon Macie usa machine learning e correspondência de padrões para descobrir dados confidenciais em escala com eficiência de custos. O Macie detecta automaticamente uma lista grande e crescente de tipos de dados confidenciais, incluindo informações pessoalmente identificáveis (PII), como nomes, endereços e números de cartão de crédito. Também oferece visibilidade constante da segurança e privacidade de seus dados armazenados no Amazon S3. É fácil configurar o Macie com um clique no Console de Gerenciamento da AWS ou com uma chamada de API única. O Macie fornece suporte para diversas contas usando o AWS Organizations, para que você possa habilitar o Macie em todas as suas contas com alguns cliques.

**Qual é o custo do Amazon Macie?**

Com o Amazon Macie, a cobrança é realizada em duas dimensões, os números de buckets do Amazon S3 na sua conta por mês e a quantidade de dados processados para a descoberta de dados confidenciais em determinado mês. Consulte a página de definição de preço do Amazon Macie, para obter informações de definição de preço atualizadas.

## AWS CloudFormation

- O que é o AWS CloudFormation?
  - O AWS CloudFormation é um serviço que fornece aos desenvolvedores e empresas uma forma fácil de criar um conjunto de recursos relacionados da AWS e de terceiros para provisioná-los e gerenciá-los de forma organizada e previsível.

- Como funciona?
  - O AWS CloudFormation permite modelar, provisionar e gerenciar recursos da AWS e de terceiros ao tratar a infraestrutura como código.

- Benefícios:
  - Definição de Infraestrutura como Código
  - Fácil Automação e Implantação
  - Controle de Dependências
  - Versionamento da Arquitetura
  - Reuso de Soluções Completas
  - Composição de Soluções

### Referências

[AWS Certified Cloud Practitioner](https://aws.amazon.com/pt/certification/certified-cloud-practitioner/)

[AWS Certified Cloud Practitioner (CLF-C01) Guia do exame](https://d1.awsstatic.com/pt_BR/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)

[Benefícios da AWS Cloud Computing](https://aws.amazon.com/pt/application-hosting/benefits/)

[As seis vantagens da computação em nuvem](https://docs.aws.amazon.com/pt_br/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html)
