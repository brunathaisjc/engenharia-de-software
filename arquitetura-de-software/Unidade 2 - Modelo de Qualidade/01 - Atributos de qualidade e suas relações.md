Aula 1
Atributos de qualidade e suas relações
O objetivo principal desta aula é ajudá-lo a entender como os desejos dos clientes são transformados em um documento que servirá de base para os programadores.

introdução
Olá, estudante!
O objetivo principal desta aula é ajudá-lo a entender como os desejos dos clientes são transformados em um documento que servirá de base para os programadores. Vamos explorar o processo de levantamento de requisitos, suas etapas, os artefatos gerados e, principalmente, os padrões de qualidade que definem o sucesso de um produto.
Ao final desta aula, você estará apto a aplicar os principais conceitos e criar um artefato que englobe o levantamento de requisitos e os padrões de qualidade. Leia atentamente o conteúdo da aula e não deixe de conferir o material da bibliografia para se aprofundar no assunto.
Bons estudos!

Levantamento de requisitos e atributos de qualidade
A etapa de levantamento de requisitos é, sem dúvidas, uma das mais importantes do processo de desenvolvimento de sistemas. Nessa fase, definimos o escopo do produto, ou seja, o que o sistema deve ter e como deve se comportar. O levantamento de requisitos é uma atividade que começa durante a comunicação e continua na fase de modelagem. É importante adaptar essa etapa às necessidades do processo, projeto, produto e pessoas envolvidas no trabalho (PRESSMAN; MAXIM, 2021, p. 132). Portanto, é natural que os requisitos possam sofrer alterações ao longo do desenvolvimento.
Requisitos podem ser entendidos como as características que o sistema deve possuir, desde as tarefas que deve desempenhar até o ambiente em que o sistema será executado. Nesse contexto, os requisitos podem ser divididos em requisitos funcionais e não funcionais (NFR, sigla do inglês: nonfunctional requirement).
Os requisitos funcionais estão diretamente ligados ao funcionamento do sistema, ou seja, são as funcionalidades que o software deve oferecer. Por exemplo, o sistema deve permitir o cadastro de usuários, o envio de e-mail de confirmação de conta, redefinição de senha, entre outras funcionalidades. O levantamento de requisitos tem três objetivos primordiais: expressar as necessidades do cliente, fornecer a base para a etapa de desenvolvimento e estabelecer uma base de funções que poderão ser validadas quando o sistema estiver pronto (PRESSMAN; MAXIM, 2021).
Já os requisitos não funcionais são aqueles que não se relacionam diretamente com o que o sistema deve fazer, mas sim com como ele deve fazer. Podemos dizer que que os NFRs expressam premissas ou restrições do software. Eles podem estar relacionados a atributos de qualidade, desempenho, segurança ou restrições diversas. Alguns exemplos de requisitos não funcionais são:

O sistema deve estar adaptado para uso em dispositivos móveis.
É necessário que o software possibilite a navegação na interface sem o uso do mouse.
Deve oferecer suporte para modo offline.
Precisa ter uma resposta rápida para cada ação do usuário.
Esses são apenas alguns exemplos que destacam como os NFRs vão além das funcionalidades básicas do sistema.
A medição da qualidade do software é um dos principais desafios no processo de desenvolvimento. É nesse contexto que se consideram os atributos de qualidade, os quais podem ser definidos como um conjunto de características que precisam ser atendidas ao final do processo de desenvolvimento para o produto satisfazer as necessidades dos usuários finais. Esses atributos estão diretamente relacionados à lista de requisitos do sistema. Os padrões de qualidade de software estão definidos pela norma internacional ISO/IEC 9126, corroborados pela norma nacional NBR 13596, e incluem um modelo com seis atributos de qualidade de software, conforme apresentado no Quadro 1.

Quadro 1 | Atributos de qualidade do software
ATRIBUTO

DESCRIÇÃO

Funcionalidade

O grau com que o software satisfaz as necessidades declaradas, incluindo: adequabilidade, exatidão, interoperabilidade, conformidade e segurança.

Confiabilidade

A disponibilidade do software ao longo do tempo, incluindo: maturidade, tolerância a falhas e facilidade de recuperação.

Usabilidade

O grau de facilidade de uso do software, incluindo: compreensibilidade, facilidade de aprendizado e operabilidade.

Eficiência

O grau de otimização do uso de recursos pelo software, incluindo: desempenho em relação ao tempo e aos recursos.

Facilidade de manutenção

A facilidade com que correções e modificações podem ser realizadas no software, incluindo: análise, realização de mudanças, estabilidade, testabilidade.

Portabilidade

A facilidade com que o software pode ser transferido de um ambiente para outro, incluindo: adaptabilidade, facilidade de instalação, conformidade, substituição.

Fonte: adaptado de Pressman e Maxim (2021, p. 418).
O atendimento dos atributos de qualidade interessa a todos os stakeholders, tanto os envolvidos no processo de desenvolvimento quanto no uso final. Ao mesmo tempo que esses atributos satisfazem as necessidades do usuário, agregam valor ao produto da empresa.
Os atributos de qualidade estão diretamente ligados às funcionalidades do sistema. São os atributos que validam se uma funcionalidade está de acordo com o que foi apurado durante a fase do levantamento de requisitos. Em diversos sistemas, as funcionalidades podem ter limites conforme o perfil de usuário que o está acessando. Um perfil de usuário pode ter acesso a determinadas funcionalidades que não estarão disponíveis para outro perfil. Portanto, os atributos de qualidade também estão relacionados a limitações nas funcionalidades.

Etapas para a modelagem de requisitos e atributos de qualidade
Ao desenvolver um software, é crucial ter um escopo bem definido, ou seja, os requisitos necessários para atender às necessidades das partes interessadas (stakeholders). Nem sempre os usuários têm uma compreensão clara do que desejam que o software faça e, muitas vezes, essas necessidades podem mudar ao longo do processo de desenvolvimento.
Por isso, estudante, o levantamento de requisitos desempenha um papel fundamental nesse processo. É nessa etapa que entendemos o contexto do software a ser desenvolvido, as necessidades que ele deve atender, as prioridades e os comportamentos esperados. O levantamento de requisitos pode ser dividido em sete fases, que podem ocorrer simultaneamente e devem ser adaptadas às necessidades do projeto: concepção, levantamento, elaboração, negociação, especificação, validação e gestão de requisitos. Cada uma dessas fases desempenha um papel importante no processo, como descrito no Quadro 2.

Quadro 2 | Fases do Levantamento de Requisitos
ETAPA

DESCRIÇÃO

Concepção

Compreender o problema de forma preliminar, identificar os interessados e o problema que deve ser solucionado.

Levantamento

Estabelecer as metas de negócio, envolver os interessados para expor suas necessidades e definir as prioridades, também conhecidas como valor de negócio.

Elaboração

Criar e refinar os cenários que descrevem como os usuários vão interagir com o software, podendo incluir a criação de casos de uso.

Negociação

Lidar com solicitações conflitantes dos clientes e usuários, avaliar custos e riscos, eliminar ou modificar requisitos e definir as prioridades para atingir a satisfação de todos os envolvidos.

Especificação

Apresentar os requisitos levantados de forma clara e compreensível, seja por meio de documentos escritos, gráficos, cenários de uso ou protótipo.

Validação

Avaliar a qualidade do levantamento de requisitos, verificar se os requisitos foram declarados corretamente, sem inconsistências, sem erros, informações ausentes ou requisitos em conflito.

Gestão de requisitos

Identificar, controlar e acompanhar as mudanças nos requisitos ao longo do projeto.

Fonte: adaptado de Pressman e Maxim (2021, p. 133-138).
Na etapa de concepção, é importante identificar os envolvidos, os interessados no sistema e em sua qualidade. Inicialmente, podemos criar uma lista das pessoas envolvidas, que pode ser ampliada à medida que o processo avança.
Em seguida, iniciamos o levantamento, que geralmente é realizado de forma colaborativa com os envolvidos. Cada stakeholder contribui com sua visão sobre o que é necessário para o sistema. A ideia é reunir todos os interessados em um ambiente propício para a discussão de ideias.
Nesta etapa, diversas ferramentas podem ser utilizadas, como planilhas, flip charts, notas adesivas, quadro branco, bate-papo online, fóruns virtuais, entre outras. O importante é que todos tenham condições de participar e expressar suas necessidades, com a mediação de um facilitador.
O objetivo é identificar problemas, propor soluções, negociar diferentes perspectivas e estabelecer um conjunto preliminar de requisitos. Vale ressaltar que essa fase pode abranger etapas posteriores, como elaboração, negociação e especificação.
Ao final dessas etapas, temos uma visão geral das funções e características do sistema, mas ainda não temos uma forma de visualizar como essas funções e características serão usadas pelos diferentes perfis de usuários. É nesse momento que podemos construir os cenários de uso (ou casos de uso), que são diagramas com descrições de como o sistema será utilizado.
Na etapa de validação, as funcionalidades e suas limitações ou permissões são testadas de acordo com o levantamento de requisitos. Ao final da etapa, pode-se certificar de que o software atende aos interesses de todos os envolvidos.

Requisitos e atributos de qualidade na prática
Agora que conhecemos as etapas do processo de levantamento de requisitos e as definições de qualidade de software, vamos expandir nossos estudos com exemplos práticos. Após levantar requisitos e atributos de qualidade, precisamos criar cenários de uso, também conhecidos como casos de uso, para tornar mais clara a interação do usuário com o sistema. É preciso lembrar que o atendimento dos atributos de qualidade interessa a todos os envolvidos, tanto usuários quanto empresa desenvolvedora.
O primeiro passo é definir os atores envolvidos, que são todos que interagem com o sistema      em diferentes papéis. De acordo com Pressman e Maxim (2021) um ator não é necessariamente apenas um usuário, é qualquer coisa que se comunica com o sistema e que é externa ao sistema. Por exemplo, um usuário pode ter um perfil “padrão” e ao mesmo tempo ser administrador do sistema.
Os atores primários são aqueles que interagem diretamente com o sistema, enquanto os atores secundários têm papel de suporte para os primários. É importante destacar que a construção de diagramas de casos de uso utilizando a Linguagem de Modelagem Unificada (UML) é um passo importante nesse contexto.

Figura 1 | Diagrama de casos de uso

Fonte: Pressman e Maxim (2021, p. 135).
Na Figura 1, que representa os casos de uso para um sistema de segurança residencial, podemos perceber a presença de um ator primário: o proprietário. Os atores secundários são as câmeras, que fornecem os pré-requisitos para as ações dos atores primários.

Figura 2 | Diagrama de classe

Fonte: Pressman e Maxim (2021, p. 140).
Na Figura 2, vemos a classe Sistema, que inclui os atributos (idSistema, statusSistema, etc.)  e as operações de responsabilidade da classe (programar, exibir, etc.). Essa forma de representação pode auxiliar os programadores durante o processo de codificação, visto que é mais próximo da linguagem utilizada por eles.
Já os atributos de qualidade podem ser elaborados com base em um diagrama de árvore, como exemplificado no caso de um sistema web, na Figura 3. Nele, temos o objetivo mais à esquerda, alguns atributos de qualidade estabelecidos pela ISO/IEC 9126 ao centro e, à direita, as ramificações correspondentes à cada um dos atributos. Por exemplo, o processamento correto dos links web é um comportamento esperado quando falamos de um atributo de Confiabilidade.

Figura 3 | Diagrama de árvore dos atributos de qualidade

Fonte: Pressman e Maxim (2021, p. 284).
Esses exemplos práticos nos ajudam a visualizar como o processo de levantamento de requisitos e as características de qualidade são aplicados na prática, satisfazendo as aspirações de todos os interessados no produto. É importante salientar que o diagrama de atributos de qualidade deve representar as funcionalidades e suas limitações e permissões, contemplando os diversos níveis de acesso, caso levantados nos requisitos.

### **Saiba mais**

Sobre os atributos de qualidade, um artigo interessante para expandir os seus estudos é [*Qualidade de Software - Engenharia de Software 29*](https://www.devmedia.com.br/qualidade-de-software-engenharia-de-software-29/18209).

Para criar os diagramas de casos de uso, você pode optar por inúmeras ferramentas disponíveis no mercado. Entre as ferramentas gratuitas, indicamos a [Draw.io](https://app.diagrams.net/).