# Certificação Amazon AWS Cloud Practitioner

## Cloud Computing?

O que é Cloud Computing

- O que é a computação em nuvem?
  - A computação em nuvem é a entrega de recursos de TI sob demanda por meio da Internet com definição de preço de pagamento conforme o uso. Em vez de comprar, ter e manter datacenters e servidores físicos, você pode acessar serviços de tecnologia, como capacidade computacional, armazenamento e bancos de dados, conforme a necessidade, usando um provedor de nuvem como a Amazon Web Services (AWS).

- Que usa a computação em nuvem?
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
