Aula 1
Documentação da arquitetura
Nesta aula, você aprenderá sobre os elementos que compõem a arquitetura de software, incluindo a documentação, que auxilia no processo de design e ferramentas de comunicação. Além disso, exploraremos a integridade conceitual, que é composta por modelos para análise e ferramenta de rastreabilidade.

introdução
Olá, estudante!
A arquitetura de software desempenha um papel fundamental ao definir a organização dos componentes, as relações entre eles e os princípios orientadores do desenvolvimento de sistemas. Ela proporciona uma visão global do sistema e contribui para a tomada de decisões críticas relacionadas à modularidade, reusabilidade, desempenho, segurança e outros atributos de qualidade. Além disso, a documentação da arquitetura é essencial para comunicar e compartilhar o conhecimento sobre a arquitetura, garantindo que sua visão seja compreendida por todos os membros da equipe.
Nesta aula, você aprenderá sobre os elementos que compõem a arquitetura de software, incluindo a documentação, que auxilia no processo de design e ferramentas de comunicação. Além disso, exploraremos a integridade conceitual, que é composta por modelos para análise e ferramenta de rastreabilidade. Com esse conhecimento, você estará preparado para compreender e aplicar de forma efetiva os conceitos e práticas relacionados à arquitetura de software em seus futuros projetos.
Bons estudos!

Conceitos essenciais de arquitetura de software
A arquitetura de software desempenha um papel fundamental no desenvolvimento de sistemas de software de qualidade. Ela define a estrutura e organização do sistema, incluindo os componentes principais, as interações entre eles e as decisões de design (BASS; CLEMENTS; KAZMAN, 2012). Essa documentação auxilia o fluxo de comunicação e o ciclo de vida do software. Veremos, nesta aula, a importância da arquitetura de software e discutiremos os principais documentos utilizados para documentar essa arquitetura. Uma arquitetura bem projetada permite a modularidade, a reutilização de componentes, a escalabilidade e a manutenibilidade do sistema. Além disso, ela mitiga riscos técnicos e facilita a comunicação entre a equipe de desenvolvimento (SHAW; GARLAN, 1996).
A ideia é provermos uma arquitetura que seja clara e bem definida com visão geral da estrutura do sistema, a qual ajude a identificarmos seus componentes principais e suas interações. Isso faz que os desenvolvedores observem o sistema como um todo, bem como propicia o trabalho em equipe; dessa forma, evitam-se problemas de acoplamento excessivo entre os componentes (FARLEY, 2021).
O processo de design é uma fase que pode influenciar a arquitetura de software. Farley (2021) explica que esse processo tem o foco em atuar nos requisitos do sistema e envolve a identificação e a seleção de estratégias de design apropriadas para atender aos requisitos funcionais e não funcionais do sistema. Durante esse processo, os arquitetos de software utilizam várias técnicas, métodos e ferramentas para criar uma arquitetura sólida e coerente.
A integridade conceitual é um tópico importante para o desenvolvimento de software, pois garante que o sistema seja consistente, preciso e atenda aos requisitos estabelecidos. Ela se refere à consistência das definições, conceitos e abstrações utilizadas na arquitetura e no design do software (BASS; CLEMENTS; KAZMAN, 2012). Para alcançar a integridade conceitual, é necessário estabelecer um modelo para análise e utilizar ferramentas de rastreabilidade.
De acordo com Kruchten (2004), o modelo para análise é uma representação estruturada e abrangente do software, que permite identificar e analisar os componentes, as relações entre eles e suas propriedades. Ele ajuda a compreender a estrutura global do software e a validar sua integridade conceitual. Sommerville (2011) destaca que o modelo para análise pode incluir diagramas arquiteturais, diagramas de classes, diagramas de sequência e outras representações visuais que auxiliam a análise e a validação da arquitetura. Por fim, a utilização de um modelo para análise permite verificar se os componentes estão corretamente definidos, se suas responsabilidades estão adequadamente atribuídas e se as interações entre eles são consistentes com as expectativas do sistema .
Para manter a integridade conceitual ao longo do ciclo de vida do software, é fundamental utilizar as ferramentas de rastreabilidade. Essas ferramentas permitem rastrear as relações entre diferentes artefatos do software, desde os requisitos iniciais até as decisões de design e a implementação final (SOMMERVILLE, 2011). A rastreabilidade propicia a identificação de dependências, a detecção de possíveis impactos de mudanças e a garantia de que todos os elementos do sistema estejam alinhados com os requisitos e com a arquitetura. Essa abordagem ajuda a manter a integridade conceitual do software e facilita a evolução e a manutenção do sistema ao longo do tempo.

Processos de design e arquitetura de software
Vimos anteriormente que a documentação da arquitetura de software é uma atividade essencial para comunicar e preservar as decisões de design tomadas durante o desenvolvimento do sistema. Existem diversos documentos utilizados nesse processo, cada um com sua finalidade específica. A seguir, destacamos alguns dos principais documentos da arquitetura de software:

Visão geral da arquitetura (architecture overview): esse documento descreve uma visão geral do sistema, incluindo seus componentes, suas interações e as decisões arquiteturais fundamentais.
Diagramas de arquitetura: os diagramas de arquitetura são representações gráficas da estrutura do sistema e de suas interações. O Quadro 1 a seguir mostra os principais tipos:
Quadro 1 | Modelos de diagramas de arquitetura
Diagrama de Arquitetura

Descrição

Diagrama de Blocos

Representa a arquitetura do sistema em termos de blocos ou componentes e suas interações de alto nível.

Diagrama de Componentes

Mostra a estrutura do sistema em termos de componentes, suas interfaces e dependências.

Diagrama de Sequência

Ilustra as interações entre objetos no sistema, destacando a sequência de mensagens trocadas entre eles ao longo do tempo.

Diagrama de Casos de Uso

Descreve as interações entre atores (usuários ou sistemas externos) e o sistema, mostrando os principais casos de uso e suas relações.

Diagrama de Fluxo de Dados

Representa o fluxo de dados entre processos e as entidades externas que interagem com o sistema.

Fonte: adaptado pelo autor a partir de Sommerville (2011).
Descrição da arquitetura (architecture description): esse documento detalha a arquitetura do sistema de forma mais aprofundada. Ele descreve os componentes individuais do sistema, suas responsabilidades, interfaces, restrições e requisitos não funcionais relevantes (BASS; CLEMENTS; KAZMAN, 2012).
Razões e decisões arquiteturais (architectural rationale): esse documento registra as razões e decisões por trás das escolhas arquiteturais feitas durante o desenvolvimento do sistema. Ele ajuda a justificar as decisões tomadas e a fornecer um histórico para futuras alterações e evoluções da arquitetura (KRUCHTEN, 2004).
Padrões arquiteturais (architectural patterns): os padrões arquiteturais são soluções recorrentes para problemas de arquitetura. Eles facilitam o entendimento e a comunicação entre os membros da equipe de desenvolvimento (BASS; CLEMENTS; KAZMAN, 2012).
Cervantes e Kazman (2016) destacam os diferentes estilos arquiteturais, como arquitetura em camadas, arquitetura orientada a serviços (SOA), arquitetura baseada em microsserviços, arquitetura cliente-servidor e muitos outros.
Na arquitetura em camadas, o sistema é dividido em camadas ou níveis hierárquicos, de modo que cada camada possui uma responsabilidade específica. Geralmente, a comunicação ocorre de forma unidirecional, das camadas inferiores para as superiores. Na arquitetura orientada a serviços, mais conhecida em inglês como service-oriented architecture (SOA), o sistema é composto por serviços independentes e reutilizáveis (BASS; CLEMENTS; KAZMAN, 2012). Cada serviço representa uma funcionalidade específica e é projetado para ser autônomo, com interfaces bem definidas.
Na arquitetura baseada em microsserviços, o sistema é dividido em serviços menores e independentes, que são responsáveis por funcionalidades específicas. A comunicação entre eles geralmente ocorre por meio de chamadas de application programming interface (API). Na arquitetura cliente-servidor, o sistema é dividido em duas partes principais: o cliente (que é a interface com o usuário) e o servidor (que fornece os recursos e a lógica de negócio). A comunicação entre o cliente e o servidor ocorre por meio de solicitações e respostas.
Por fim, devemos citar a arquitetura em camadas MVC (Model-View-Controller), a qual é um subconjunto do estilo arquitetural em camadas, focado em sistemas de software para interface com o usuário. Esse estilo promove a separação de responsabilidades e facilita a manutenção e a evolução da interface com o usuário.
Vale ressaltar que durante o processo de design, a comunicação efetiva entre os membros da equipe de desenvolvimento é essencial. Para isso, é importante utilizar ferramentas adequadas que permitam a colaboração e o compartilhamento de informações sobre a arquitetura do software.

Aplicando conceitos de integridade conceitual e ferramentas de rastreabilidade
Vimos anteriormente conceitos e a importância do uso de diagramas na arquitetura de software. Porém, algumas ferramentas de modelagem e design específicas podem dar suporte às implementações. Essas ferramentas oferecem recursos avançados, como a geração automática de diagramas a partir de modelos, a análise de dependências e a rastreabilidade dos requisitos (KRUCHTEN, 2004). Exemplos de ferramentas são Lucidchart, Draw.io, Microsoft Visio, StarUML, Visual Paradigm, e Astah.
No entanto, vale ressaltar que a escolha e o uso das ferramentas devem ser adaptados às necessidades e à cultura da equipe de desenvolvimento. O foco deve ser na efetividade da comunicação e na facilidade de uso das ferramentas selecionadas (MAXIM; PRESSMAN, 2021).
Por outro lado, as ferramentas de rastreabilidade são usadas para manter a integridade conceitual ao longo do ciclo de vida do software. Essas ferramentas permitem rastrear as relações entre diferentes artefatos do software, desde os requisitos iniciais até as decisões de design e a implementação final (SOMMERVILLE, 2011). A rastreabilidade auxilia a identificação de dependências, a detecção de possíveis impactos de mudanças e a garantia de que todos os elementos do sistema estejam alinhados com os requisitos e com a arquitetura.
Existem diversas ferramentas de rastreabilidade disponíveis no mercado, as quais podem ser utilizadas para registrar e acompanhar as relações entre requisitos, componentes arquiteturais, testes, código-fonte e outros artefatos do sistema.

Enterprise Architect: é uma ferramenta de modelagem abrangente que permite criar diagramas e modelos para representar a arquitetura do software. Ela oferece recursos de rastreabilidade, permitindo estabelecer links entre requisitos, componentes, testes e outras entidades do sistema (CERVANTES; KAZMAN, 2016).
Visual Paradigm: é uma plataforma de modelagem e design que suporta a criação de diversos tipos de diagramas, como diagramas de caso de uso, diagramas de classe e diagramas de sequência. Ela também oferece recursos de rastreabilidade (CERVANTES; KAZMAN, 2016; SOMMERVILLE, 2011).
Lucidchart: essa ferramenta foca na diagramação online e permite criar diagramas de arquitetura e estabelecer vínculos entre os elementos do sistema. Embora seja amplamente utilizada para criação de diagramas, também oferece recursos básicos de rastreabilidade (BASS; CLEMENTS; KAZMAN, 2012).
JIRA: embora seja conhecida principalmente como uma ferramenta de gerenciamento de projetos e rastreamento de problemas, o JIRA também pode ser usado para rastrear relacionamentos entre requisitos, componentes e outras entidades do software (DOAR, 2011). Ele oferece recursos de rastreabilidade e é amplamente utilizado em ambientes de desenvolvimento ágil.
Em conclusão, vamos imaginar um projeto de desenvolvimento de software para uma empresa. Os documentos de arquitetura descreveriam a estrutura do sistema, indicando como os componentes se relacionam, como os usuários interagem com o aplicativo, e quais tecnologias e padrões arquiteturais foram escolhidos. A equipe implementa um processo de design bem definido, que inclui a análise de requisitos, a modelagem da arquitetura, a definição de interfaces e a implementação.
Após isso, a integridade conceitual é aplicada ao garantir que todas as decisões de design estejam em conformidade com os princípios e requisitos definidos no início do projeto. A equipe pode ainda utilizar diagramas UML para modelar a estrutura do sistema. Por fim, uma ferramenta de rastreabilidade para acompanhar as mudanças nos requisitos ao longo do tempo. Quando um requisito é modificado, a ferramenta registra a alteração, permitindo que a equipe saiba exatamente quando e por que a mudança foi feita.

Video Resumo
Agora que você está familiarizado com alguns dos conceitos básicos de arquitetura de software, é hora de aprofundar seus conhecimentos assistindo à videoaula sobre este conteúdo. Teremos a oportunidade de explorar algumas fases da arquitetura de software e a importância de sua documentação. Além disso, vamos abordar o processo de design e as ferramentas de comunicação, mostrando ainda como o modelo para análise e ferramenta de rastreabilidade são úteis.

 


Saiba mais
Sugerimos uma referência para que você possa aprofundar um pouco mais seus conhecimentos sobre arquitetura de software: O que é Arquitetura orientada a serviços?