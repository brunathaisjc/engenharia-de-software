Aula 3
Técnicas de design arquitetural
A arquitetura de software é uma das etapas mais importantes de todo o processo de desenvolvimento. Ela abrange desde a concepção até o desenvolvimento e validação da qualidade do software.

introdução
Olá, estudante!
A arquitetura de software é uma das etapas mais importantes de todo o processo de desenvolvimento. Ela abrange desde a concepção até o desenvolvimento e validação da qualidade do software. O papel do arquiteto de software é considerar uma infinidade de características e princípios, e tomar decisões que se adequem ao contexto específico do projeto.
Nesta aula, vamos estudar as técnicas e os princípios que norteiam a arquitetura de um sistema. Vamos elencar os diferentes padrões e estilos arquitetônicos utilizados atualmente e exemplificar como a teoria se aplica na prática, elaborando um documento. O objetivo é entender como uma arquitetura bem projetada é essencial para o sucesso do desenvolvimento de sistemas de alta qualidade. Aplique esses conceitos na prática para criar soluções eficientes e robustas que atendam às necessidades dos projetos e dos clientes.
Bons estudos!

Principais conceitos da arquitetura de software
Podemos dizer que arquitetura de software tem a sua importância definida por três motivos principais, de acordo com Zenker et al. (2019):

Permite a comunicação de todos os envolvidos no processo.
As decisões tomadas na etapa de arquitetura impactarão a forma como o sistema será desenvolvido, podendo levar a limitações ou problemas se essa etapa for mal executada.
Fornece a ideia essencial de como o sistema deve ser estruturado e como todos os componentes ou camadas se integrarão para se comunicar.
Além disso, através da arquitetura, é possível analisar a efetividade do desenvolvimento no entendimento e aplicação dos requisitos levantados. Para a arquitetura ou design de um software, três elementos são imprescindíveis em qualquer sistema:

Componentes: pequenas partes do software, cada uma com uma função específica.
Propriedades: características relativas a cada componente do sistema.
Conectores: descrevem como os componentes se comunicam entre si, promovendo a integração do sistema por meio de requisições, mensagens, etc.
A separação de preocupações é um conceito importante relacionado aos componentes. Basicamente, ele preconiza que o sistema deve ser dividido em componentes, de modo que cada um executa uma tarefa específica, sendo responsável por resolver um problema específico, ou fornecer um serviço a outro componente.
Outro ponto importante são os estilos arquitetônicos. O estilo define a construção dos componentes, a forma como eles interagem e as propriedades do sistema. O Quadro 1 descreve os estilos arquiteturais mais utilizados e suas características.

Quadro 1 | Estilos arquiteturais
Arquiteturas centralizadas em dados

O banco de dados é uma parte central, sendo acessado por outros componentes para leitura e escrita de dados (PRESSMAN, 2016).

Arquiteturas de fluxo de dados

Os dados de entrada são transformados por outros componentes. antes de prosseguirem para o próximo componente (PRESSMAN, 2016).

Arquiteturas de chamadas e retornos

É uma estrutura utilizada em projetos mais antigos. Há uma divisão entre programas, de forma que o principal invoca outros subprogramas (PRESSMAN, 2016).

Arquiteturas orientadas a objetos

Os dados e operações são encapsulados, permitindo que apenas componentes específicos tenham acesso para a manipulação. Demais componentes acessam o componente de manipulação para lidar com os dados (PRESSMAN, 2016).

Arquiteturas em camadas

O sistema é dividido em camadas, cada uma realizando operações distintas, com funcionalidades de interface na camada central e operações externas atendidas pelas camadas externas (PRESSMAN, 2016).

Arquiteturas cliente-servidor

Uma das mais utilizadas atualmente, com a presença do servidor (backend) responsável por processar e realizar operações conforme recebe requisições do cliente (frontend). Nesse estilo, um servidor pode atender a um número variado de clientes (ZENKER et al., 2019).

Fonte: adaptado pelo autor a partir de Pressman (2016) e de Zenker et al. (2019).
Outro tema importante são os padrões arquiteturais. Os padrões tratam de aspectos mais gerais, orientando como o sistema se comportará em alguma funcionalidade; ou seja, envolvem questões de comportamento. Os principais padrões arquiteturais utilizados atualmente são o MVC, o MVP e o MVVM. O Quadro 2 apresenta os padrões e suas características:

Quadro 2 | Padrões arquiteturais
MVC: Model-View-Controller

Separa partes do sistema atribuindo tarefas distintas. O Model trata dos dados; a View, da exibição e interação com o usuário; e a Controller faz a ligação entre a View e o Model.

MVP: Model-View-Presenter

A tela é disponibilizada pela View, com as requisições capturadas pela Presenter, que se conecta ao Model. Este devolve os dados à Presenter, que os transfere à View para exibição em tela.

MVVM: Model-View-ViewModel

A camada View define a estrutura exibida ao usuário, enquanto a ViewModel estabelece os atributos e métodos para que a View exiba dados e solicite sua manipulação. O Model contém as regras de negócio e o acesso aos dados.

Fonte: Zenker et al. (2019).
No início do trabalho de arquitetura, é importante definir o contexto, descrevendo as entidades externas (pessoas, outros sistemas, dispositivos) que podem interagir com o sistema, com base no levantamento de requisitos. Após a definição do contexto, é possível mapear os arquétipos arquiteturais, que representam abstrações dos elementos do sistema, ou seja, funcionalidades. A totalidade desses arquétipos constitui a arquitetura do sistema.
Para representar visualmente este trabalho, é construído o diagrama de contexto arquitetural, que demonstra como o sistema vai interagir com as entidades externas. O sistema em desenvolvimento é o centro do processo, enquanto as relações podem ser divididas em:

Sistemas superiores: sistemas que utilizam o sistema principal.
Sistemas subordinados: sistemas que são utilizados pelo sistema principal.
Sistemas do mesmo nível: sistemas que compartilham informações com o principal.
Atores: entidades, pessoas ou dispositivos que utilizarão o sistema principal.
Técnicas utilizadas no processo de arquitetura
A arquitetura de software é a responsável por garantir que o sistema a ser desenvolvido esteja alinhado com os requisitos e atributos de qualidade. Durante a etapa de arquitetura, são traçados os estilos e padrões arquiteturais usados no projeto.
No bloco anterior, vimos os principais estilos, padrões e técnicas que podem ser utilizados pelo arquiteto de software ao elaborar o diagrama arquitetural e outros documentos úteis para o processo. Agora, veremos como esses conceitos se relacionam com o objetivo de construir um software de qualidade.
Ao planejar a arquitetura de um sistema, é preciso levar em conta o contexto, compreendendo quem são os envolvidos e quais dispositivos serão utilizados. Entender o contexto de uso é algo imprescindível para definir o melhor estilo e padrão para o software a ser desenvolvido.
Um sistema deve ser dividido em pequenos sistemas (componentes), de forma que cada um tenha suas características e responsabilidades (propriedades). Estas são integradas por meio de comunicação por mensagens internas, fluxo de dados ou requisições web (conectores).
Um componente pode ser definido por suas interfaces, ou seja, o que o componente requer para funcionar e o que ele fornece para o sistema. A Figura 1 ilustra o conceito de um componente:

Figura 1 | Interfaces de um componente

Fonte: Zenker et al. (2019).
Os estilos arquiteturais definem de forma específica como o sistema se comportará de acordo com esses princípios fundamentais, incluindo os componentes, as conexões entre eles e as restrições no fluxo de informações entre os diferentes componentes. Dessa forma, após a definição do estilo, o arquiteto de software pode compreender o sistema de maneira mais geral.
A separação de preocupações ou responsabilidades, outro conceito abordado anteriormente, é encarada de diferentes formas no sistema de acordo com o estilo arquitetural escolhido. Por exemplo, um estilo orientado a objetos (Figura 2) terá a separação de preocupações em suas classes, enquanto um sistema de camadas (Figura 3) dividirá suas funcionalidades de acordo com as camadas. Um estilo centralizado em dados (Figura 4) vai concentrar as funcionalidades em outros componentes, deixando para a camada de dados apenas as funções de leitura e escrita dos dados. Na arquitetura de fluxo de dados (Figura 5), há a transformação dos dados a cada filtro.

Figura 2 | Diagrama de comunicação – arquitetura orientada a objetos

Fonte: Pressman e Maxim (2021).
Figura 3 | Arquitetura em camadas

Fonte: Pressman e Maxim (2021).
Figura 4 | Arquitetura centralizada em dados

Fonte: Pressman e Maxim (2021).
Figura 5 | Arquitetura de fluxo de dados

Fonte: Pressman e Maxim (2021).
Por sua vez, os padrões arquiteturais, diferente dos estilos, tem foco na estruturação do código em si, definindo as funções das diferentes funcionalidades e principalmente, como as partes devem interagir. Os padrões tratam de questões comportamentais específicas no contexto da arquitetura (PRESSMAN; MAXIM, 2016). Padrões MVC (Figura 6) ou o MVP focam em componentes que exibem os dados em tela, controlam as regras de negócio e realizam as ações de leitura, processamento e escrita dos dados.

Figura 6 | Padrão MVC

Fonte: Pressman e Maxim (2021).
Portanto, a definição do estilo e padrão, o respeito aos princípios da arquitetura e a separação de preocupações entre as partes do sistema, escolhidos pelo arquiteto, são cruciais para que os programadores possam se orientar e desenvolver o sistema de acordo com as necessidades dos usuários, considerando a qualidade e a estrutura criada pela pessoa arquiteta.
É importante lembrar também que a construção de um diagrama de contexto arquitetural é parte importante do trabalho da arquitetura. A Figura 7 representa, de maneira genérica, um diagrama de contexto arquitetural, no qual podemos ver as representações do contexto envolvido:

Figura 7 | Diagrama de contexto arquitetural

Fonte: Zenker et al. (2019).
Artefatos gerados pelo arquiteto de software
O arquiteto de software deve elaborar diversos artefatos relacionados às definições da arquitetura. Nesses artefatos, devem constar os conceitos apresentados anteriormente, tais como componentes, diagrama de contexto, diagrama de arquétipos e de instância, para documentar a etapa de arquitetura de um software.
É importante ressaltar que os estilos e padrões arquitetônicos não estarão diretamente representados nos diagramas, mas são eles que definirão a forma como os componentes, arquétipos, instâncias e contexto serão organizados.
Na Figura 8, vemos a representação de um diagrama de contexto arquitetural de um sistema de vigilância residencial. Esse diagrama engloba todos os componentes, atores e sistemas que interagem com o sistema.

Figura 8 | Diagrama de contexto arquitetural de um sistema de vigilância

Fonte: Pressman e Maxim (2021).
Nesse exemplo, a função de vigilância é um sistema de mesmo nível e utiliza a função de segurança (sistema principal). Os sistemas superiores são representados pelo produto em si e por qualquer outro sistema acessado via internet que disponibilize as funções do exemplo. Os painéis de controle e o proprietário são os atores, enquanto os sensores são sistemas subordinados, ou seja, componentes utilizados pelo sistema principal.
A Figura 9 apresenta os arquétipos, que são classes ou padrões abstraídos que representam funcionalidades específicas do sistema. Nesse contexto, o nó representa os elementos de entrada e saída, que podem ser os sensores e os alarmes. O detector é uma abstração que engloba todos os equipamentos que geram informações de entrada para o sistema. O indicador representa os mecanismos que indicam alguma mensagem do sistema, por exemplo, uma sirene. Já o controlador pode ser entendido como a função de ativar/desativar o sistema.

Figura 9 | Relacionamentos em UML de arquétipos

Fonte: Pressman e Maxim (2021).
Todo e qualquer requisito levantado deve ser descrito pela arquitetura, visando a obter uma visão geral dos componentes do sistema. Cabe lembrar que um componente reflete um comportamento do sistema. Podemos representar graficamente um componente, conforme a Figura 10, que define um componente que coleta e compara dados de um sensor de segurança residencial:

Figura 10 | Exemplo de diagrama de componente

Fonte: Zenker et al. (2019).
Na interface “Requer”, há a entrada de dados que serão processados de acordo com os métodos da interface “Fornece”. Quanto mais detalhado for o diagrama, mais fácil será a tarefa dos programadores na hora da codificação.
Além de representar cada componente isolado, é preciso ter uma visão geral de como esses componentes se relacionam. A Figura 11 representa graficamente a estrutura de componentes gerais de um sistema de monitoramento residencial.

Figura 11 | Componentes de alto nível

Fonte: Pressman e Maxim (2021).
O diagrama deve representar os principais comportamentos descritos na análise de requisitos. Na imagem, a função de gerenciamento da comunicação externa, por exemplo, é responsável por coordenar a comunicação com entidades externas, como um app ou um painel de controle. Note que cada retângulo representa um componente do sistema. É importante frisar que aqui podemos notar um conceito básico da arquitetura, que é a separação de preocupações. No diagrama, podemos perceber que cada componente do sistema tem uma função única e separada dos demais.
Até este ponto, já definimos o contexto, os arquétipos, os componentes e a estrutura global do sistema. Sem embargo, ainda precisamos refinar um pouco mais. Para isso, é preciso expandir o diagrama anterior com as instâncias das funcionalidades. A Figura 12 expande a visão dos componentes.

Figura 12 | Instância da função de segurança

Fonte: Pressman e Maxim (2021).
Neste diagrama, temos o comportamento real de uma funcionalidade do sistema. O componente “Gerenciamento de detectores”, por exemplo, interage com o componente “Agendador”, que, por sua vez, se conecta com cada um dos sensores existentes.
Ao aplicar os princípios e técnicas de design de arquitetura explorados ao longo da aula, o arquiteto terá em mãos um material completo e bem elaborado para que se possa iniciar a fase de desenvolvimento do sistema.

Video Resumo
Neste vídeo, explanaremos um pouco sobre as responsabilidades do arquiteto de software e as técnicas e princípios envolvidos no processo de designs arquitetural de um software. Abordaremos os principais estilos e padrões utilizados atualmente e veremos como transformar esses conceitos em artefatos que contemplarão uma visão bem elaborada do sistema.

 


Saiba mais
Além dos padrões discutidos nesta aula, há muitos outros, como microsserviços. Você pode conhecer um pouco mais no artigo “Padrões arquiteturais, quais e como usar?”, de Patrick Francis Gomes Rocha.