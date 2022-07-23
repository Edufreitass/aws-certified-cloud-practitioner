# Certificação Amazon AWS Cloud Practitioner

## Cloud Computing?

O que é Cloud Computing

- O que é a computação em nuvem?
  - A computação em nuvem é a entrega de recursos de TI sob demanda por meio da Internet com definição de preço de pagamento conforme o uso. Em vez de comprar, ter e manter datacenters e servidores físicos, você pode acessar serviços de tecnologia, como capacidade computacional, armazenamento e bancos de dados, conforme a necessidade, usando um provedor de nuvem como a Amazon Web Services (AWS).

- Quem usa a computação em nuvem?
  - Organizações de todos os tipos, portes e setores usam a nuvem para uma grande variedade de casos de uso, como backup de dados, recuperação de desastres, e-mail, desktops virtuais, desenvolvimento e teste de software, análises de big data e aplicativos web voltados ao cliente. Por exemplo, as empresas do setor de saúde usam a nuvem para desenvolver tratamentos mais personalizados para os pacientes. Empresas de serviços financeiros usam a nuvem como base para detectar e prevenir fraudes em tempo real. E fabricantes de videogames usam a nuvem para entregar jogos online para milhões de jogadores em todo o mundo.
 
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

## Cloud Types

Diferentes Tipos de Cloud

- Infraestrutura como serviço (IaaS)
  - O IaaS contém os componentes básicos da IT na nuvem. Normalmente, o IaaS oferece acesso a recursos de rede, computadores (virtuais ou em hardware dedicado) e espaço de armazenamento de dados. O IaaS oferece o mais alto nível de flexibilidade e controle de gerenciamento sobre os recursos de TI. Ele é o tipo de computação mais semelhante aos recursos existentes de TI, já conhecidos por vários departamentos e desenvolvedores de TI.

- Plataforma como serviço (PaaS)
  - Com o PaaS, você não precisa mais gerenciar a infraestrutura subjacente (geralmente, hardware e sistemas operacionais) e pode manter o foco na implantação e no gerenciamento de aplicativos. Dessa forma, você fica mais eficiente, pois não precisa se preocupar com aquisição de recursos, planejamento de capacidade, manutenção de software, correções ou qualquer outro tipo de trabalho genérico repetitivo necessário para a execução dos aplicativos.

- Software como serviço (SaaS)
  - O SaaS oferece um produto completo, executado e gerenciado pelo provedor de serviços. Na maioria dos casos, quando as pessoas mencionam SaaS, estão falando de aplicativos de usuários finais (como e-mail baseado na web). Com uma oferta de SaaS, você não precisa pensar sobre a manutenção do serviço ou o gerenciamento da infraestrutura subjacente. Você só precisa se preocupar sobre como utilizará esse software específico.

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

## Amazon EC2

- O que é o Amazon Elastic Compute Cloud (Amazon EC2)?
  - O Amazon Elastic Compute Cloud (Amazon EC2) é um serviço da web que fornece capacidade computacional redimensionável na nuvem. Ele foi projetado para facilitar a computação em escala na Web para os desenvolvedores.

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
