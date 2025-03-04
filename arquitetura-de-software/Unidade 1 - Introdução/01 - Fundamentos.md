# aula 1 - fundamentos da arquitetura de software

### **introdução**

Olá, estudante!

Boas-vindas à nossa aula sobre Fundamentos da Arquitetura de Software! Você está interessado em aprender a projetar um software de alta qualidade que atenda às necessidades de seus usuários? Quer aprender a usar a arquitetura de software para atingir esse objetivo? Junte-se a mim para uma aula que explora os conceitos e princípios essenciais da arquitetura de software e como ela pode ser usada para desenvolver o melhor software possível.

Você aprenderá sobre os conceitos fundamentais de arquitetura de software, o padrão ISO/IEEE 1471-2000 e muito mais. Ao final desta aula, você terá uma sólida compreensão dos fundamentos da arquitetura de software e do padrão ISO/IEEE 1471-2000 e estará pronto para uma visão mais afundo do tema!

Bons estudos!

### **Conceitos fundamentais de arquitetura de software**

Às vezes, quando pensamos em arquitetura de software, é comum fazer analogia com a construção civil, pois também realizamos essa comparação com a engenharia de software com as outras engenharias (ZENKER *et al.*, 2019). A arquitetura de software é a base de qualquer projeto de software bem-sucedido. Ela abrange o design de alto nível e a organização de um sistema de software, e define os relacionamentos e interações entre seus componentes.

Apesar de realizar analogias com a construção civil, para você, estudante, é importante entender que a arquitetura de software não é uma área independente. Pressman e Maxim (2021, p. 253) esclarecem que a arquitetura de software de um programa ou sistema computacional “abrange os componentes de software, as propriedades externamente visíveis desses componentes e as relações entre eles”.

Para Perry e Wolf (1992), a arquitetura de software é um conjunto de elementos arquiteturais (dados, processamento e conexão), que estão organizados de certa forma. Essa organização é definida por tomadas de decisões para contentar os objetivos e restrições. Pressman e Maxim (2021, p. 182) destacam três principais razões pelas quais a arquitetura de software é importante:


- “A arquitetura de software fornece uma representação que facilita a comunicação entre todos os envolvidos;
- A arquitetura destaca desde o início as decisões de projeto que terão profundo impacto no trabalho de engenharia de software que se segue;
- A arquitetura constitui um modelo relativamente pequeno como os componentes do sistema que estão estruturados e trabalham em conjunto.”

> 
> 

Para Pressman e Maxim (2021, p. 182) “o modelo de projeto de arquitetura e os padrões de arquitetura são transferíveis, ou seja, representam um conjunto de abstrações que permitem aos engenheiros de software descrever a arquitetura de modo previsível”.

# **Padrões de arquitetura**

Um padrão de arquitetura resulta em uma transformação do projeto de arquitetura. Segundo Pressman e Maxim (2021, p. 186), ele difere de um estilo em alguns modos fundamentais, como: o escopo de um padrão é menos abrangente; um padrão impõe uma regra sobre a arquitetura, descrevendo como o software vai tratar um aspecto de sua funcionalidade em termos de infraestrutura; os padrões de arquitetura tendem a tratar de questões comportamentais e específicas no contexto de arquitetura, por exemplo, aplicações em tempo real que tratam a sincronização ou interrupções.

Nesta aula, abordaremos o padrão ISO/IEEE 1471-2000, também conhecida como “Prática Recomendada para Descrição Arquitetural de Sistemas Intensivos em Software”. Ele fornece uma estrutura para descrever e avaliar a arquitetura de um sistema de software, e define os seguintes termos:

- **Visão arquitetural:** uma representação da arquitetura de um sistema a partir de uma perspectiva particular ou ponto de vista das partes interessadas. Por exemplo, um desenvolvedor pode usar uma visão de componente para descrever a estrutura do sistema, enquanto um *stakeholder* do negócio pode usar uma visão funcional para descrever os recursos do sistema.
- **Ponto de vista arquitetônico:** uma especificação das convenções, regras e preocupações que governam a construção, interpretação e uso de uma visão arquitetônica. Elas servem para capturar as preocupações e interesses de diferentes partes interessadas no sistema.
- **Descrição da arquitetura:** o conjunto de visualizações e pontos de vista arquitetônicos que descrevem a arquitetura de um sistema. Ela deve ser uma descrição abrangente e coerente da arquitetura do sistema.

### **Compreendendo a arquitetura de software**

A arquitetura de software é como a planta de um prédio. Assim como um projeto que ajuda arquitetos e construtores a entender como um prédio será construído, a arquitetura de software permite que os desenvolvedores de software entendam como um sistema de software será construído, o que deve ser seguido e como deve ser feito (ZENKER *et al.*, 2019).

A arquitetura de software garante que as diferentes partes de um sistema de software funcionem juntas adequadamente. É como um quebra-cabeça, com muitas peças diferentes que precisam se encaixar perfeitamente (PERRY; WOLF, 1992). Por exemplo, se você estiver construindo um sistema de software para uma loja, precisará garantir que o sistema de estoque, o sistema de *checkout* e o sistema de pagamento funcionem conjuntamente sem problemas.

Uma boa arquitetura de software é importante porque garante que o sistema de software funcione bem e seja fácil de manter. Assim como um prédio bem construído dura muito tempo, um sistema de software bem projetado será mais confiável e durará mais.

Compreendendo a arquitetura do software, os desenvolvedores podem garantir que o software que construíram funcione bem e atenda às necessidades das pessoas que o utilizam. Também os ajuda a se comunicar melhor com outras pessoas envolvidas na construção do software, como designers, analista de negócios e/ou gerentes de produto.

O padrão ISO/IEEE 1471-2000 fornece uma estrutura para descrever e avaliar a arquitetura de software. Ele define diferentes perspectivas ou “visões” do sistema de software, dependendo dos interesses e preocupações dos diferentes *stakeholders*. Por exemplo, um desenvolvedor de software pode usar uma “visão de componente” para entender como as diferentes partes do sistema serão construídas, enquanto uma parte interessada do negócio pode usar uma “visão funcional” para entender como o sistema atenderá às necessidades dos usuários (ISO/IEEE, 2000).

O padrão ISO/IEEE 1471-2000 também define princípios para uma boa arquitetura de software. Isso inclui abstração, que significa focar nas partes mais importantes do sistema;, separação de interesses, que significa dividir o sistema em partes menores que atendam a interesses específicos; modularidade, que significa organizar o sistema em módulos independentes; e hierarquia, que significa organizar o sistema em níveis de abstração.

Ao seguir o padrão ISO/IEEE 1471-2000, os desenvolvedores podem garantir que o software criado por eles atenda aos altos padrões de qualidade e confiabilidade. Também os ajuda a se comunicar melhor com outras pessoas envolvidas na construção do software. Compreendendo a arquitetura de software e o padrão ISO/IEEE 1471-2000, os desenvolvedores podem criar sistemas de software escaláveis, sustentáveis e que atendam às necessidades de seus usuários e *stakeholders*. Eles também podem se comunicar efetivamente com outros *stakeholders*, como proprietários de empresas, designers e outros desenvolvedores, usando uma linguagem e uma estrutura comuns.

### **Adotando o padrão ISO/IEEE 1471-2000**

O padrão ISO/IEEE 1471-2000 para arquitetura de software fornece uma estrutura que os desenvolvedores de software podem usar para projetar e construir sistemas de software confiáveis e de alta qualidade (IEEE ARCHITECTURE WORKING GROUP *et al.*, 2000). Seguindo o padrão, desenvolvedores podem criar softwares fáceis de manter, que atendam às necessidades de seus usuários e sejam consistentes com as melhores práticas de desenvolvimento de software.

Para aplicar o padrão ISO/IEEE 1471-2000, desenvolvedores devem seguir um conjunto de etapas que servirão de orientação no processo de projeto e construção de um sistema de software. São elas, (IEEE ARCHITECTURE WORKING GROUP *et al.*, 2000):

# **Passo 1: entenda as diferentes visões da arquitetura de software**

O padrão ISO/IEEE 1471-2000 fornece diferentes visões de arquitetura de software, que mostram diferentes aspectos do sistema de software. Essas visões incluem:

- A **visão funcional**, que mostra o que o software faz e como o faz.
- A **visão de componentes**, que mostra como as diferentes partes do sistema estão conectadas.
- A **exibição de implantação**, que mostra como o software é instalado e usado.

Para aplicar o padrão, desenvolvedores devem entender cada uma dessas visões e como elas se relacionam entre si.

# **Etapa 2: definir a arquitetura do software**

Depois que os desenvolvedores entenderem as diferentes visões da arquitetura de software, eles devem criar um plano de como o sistema de software funcionará. Isso envolve a definição dos componentes do sistema, como eles interagem entre si e como serão implementados. Os desenvolvedores podem usar as diferentes visualizações do padrão para ajudá-los a criar esse plano.

# **Passo 3: avalie a arquitetura**

Depois de criar um plano para o sistema de software, os desenvolvedores devem avaliá-lo para garantir que atenda às necessidades do software. Eles devem considerar fatores como usabilidade, desempenho e capacidade de manutenção e garantir que a arquitetura seja consistente com as melhores práticas de desenvolvimento de software. Os desenvolvedores podem usar os princípios de uma boa arquitetura de software, como: abstração, separação de preocupações, modularidade e hierarquia, para avaliar o plano e garantir que seja de alta qualidade.

# **Etapa 4: comunicar a arquitetura**

Para construir um sistema de software que atenda às necessidades de seus usuários, os desenvolvedores precisam comunicar a arquitetura de forma nítida a todas as partes interessadas no projeto. Isso inclui designers, responsáveis por negócios e outros desenvolvedores. Ao comunicar de forma clara o plano, todos podem estar na mesma página e trabalhar juntos para construir o software.

# **Etapa 5: atualizar a arquitetura**

À medida que o sistema de software é construído e testado, desenvolvedores podem precisar fazer alterações na arquitetura. Ao seguir o padrão ISO/IEEE 1471-2000, desenvolvedores podem garantir que quaisquer alterações feitas sejam consistentes com o plano geral do software. Eles podem avaliar as mudanças usando os princípios da boa arquitetura de software e certificar-se de que as mudanças não comprometam a confiabilidade, manutenibilidade ou usabilidade do sistema de software.

Em conclusão, o padrão ISO/IEEE 1471-2000 para arquitetura de software fornece um conjunto de diretrizes e princípios que os desenvolvedores de software podem usar para projetar e construir sistemas de software de alta qualidade. Seguindo as etapas descritas acima, os desenvolvedores podem criar um software fácil de manter, que atenda às necessidades de seus usuários e seja consistente com as melhores práticas de desenvolvimento de software.

### **Video Resumo**

Nesta videoaula, você aprenderá sobre os princípios fundamentais da arquitetura de software e do padrão ISO/IEEE 1471-2000 em seus projetos. Você obterá uma compreensão profunda das diferentes visões da arquitetura de software e como criar um plano de arquitetura eficaz que atenda às necessidades de seus usuários.

### **Saiba mais**

[*Arquitetura de Software*](https://www.inf.ufpr.br/andrey/ci163/IntroduzArquiteturaAl.pdf): nesse link, você poderá acessar uma aula da professora Silvia Regina Vergilio, da UFPR, sobre arquitetura de software, com definições de outros autores.

[*A importância do arquiteto de software*](https://www.devmedia.com.br/a-importancia-do-arquiteto-de-software/27794): nesse link, você terá acesso a características do papel de um profissional de arquitetura de software.

