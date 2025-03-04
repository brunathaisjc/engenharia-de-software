# Aula 2

**Modelo de qualidade e atributos de negócio**

*O objetivo dessa aula é explorar a importância da validação e qualidade no contexto dos negócios e do valor agregado de um produto.*

### **introdução**

Olá, estudante!

O objetivo dessa aula é explorar a importância da validação e qualidade no contexto dos negócios e do valor agregado de um produto. Você entenderá os principais conceitos desse processo, como *time-to-market*, vida útil do sistema, agenda de lançamento e gestão da qualidade, que desempenham um papel crucial na entrega de um produto de qualidade.

Compreender esses aspectos permitirá que você aplique os conceitos aprendidos e crie um diagrama de atributos de qualidade alinhado com os requisitos do sistema. Certifique-se de ler todo o conteúdo da aula e não deixe de conferir o material da bibliografia para se aprofundar no assunto.

Bons estudos!

### **Características do controle de qualidade**

Quando se trata de qualidade de software, o foco principal é atender às necessidades dos usuários com base nas etapas de concepção e levantamento. Para um produto ser considerado de qualidade, ele não deve apenas cumprir suas funções, mas também apresentar confiabilidade e ausência de erros do sistema.

No entanto, a qualidade tem um preço, tanto para a empresa desenvolvedora quanto para os usuários, que podem ter que lidar diariamente com erros que dificultam seu trabalho. Certamente, é mais barato para a empresa reduzir custos de qualidade durante a fase de desenvolvimento e usar os clientes como “testadores” do software, corrigindo bugs à medida que surgem durante o uso do produto. No entanto, em um mercado cada vez mais competitivo, uma empresa que não seja sinônimo de qualidade tende a perder espaço (PRESSMAN; MAXIM, 2021).

Existem vários tipos de custos associados aos processos de qualidade no desenvolvimento de software. Podemos citar os custos de prevenção (como o planejamento dos testes e treinamento); os custos de avaliação (como revisões técnicas); os custos de materiais utilizados na modelagem, coleta de dados, avaliação de métricas e execução dos testes; os custos de falhas internas (quando um erro é detectado antes da entrega do produto); os custos de falhas externas (que envolvem defeitos encontrados após a entrega do produto); e custo do suporte ao cliente. Os custos de falhas internas e externas também podem aumentar os custos dos outros tipos, uma vez que o software precisará ser validado novamente após a correção dos erros.

É importante lembrar que os processos de qualidade devem estar presentes ao longo de toda a vida útil do produto, não apenas durante o processo de desenvolvimento, mas também nas etapas de operação e manutenção, desde a definição dos requisitos até o término de seu uso.

Na aula anterior, discutimos sobre os atributos de qualidades definidos na ISO/IEC 9126-1:2001. Eles são seis atributos ao total: funcionalidade, confiabilidade, usabilidade, eficiência, facilidade de manutenção e portabilidade. No caso de aplicações web, podemos acrescentar mais quatro: segurança (para evitar acesso não autorizado), disponibilidade (porcentagem de tempo em que o aplicativo está disponível para uso), escalabilidade (facilidade de redimensionar os servidores de acordo com a demanda) e *time-to-market* (tempo necessário para lançar o produto no mercado, que não é necessariamente um atributo de qualidade técnica, mas aumenta a qualidade comercial do produto) (PRESSMAN; MAXIM, 2021).

Podemos entender o *time-to-market* como o tempo decorrido entre a concepção do produto até sua disponibilização aos clientes, ou seja, o tempo total de desenvolvimento. Vale ressaltar que o produto que chegar primeiro ao mercado tende a conquistar uma maior fatia do mercado-alvo.

Nesse ponto, há um conflito entre os atributos de qualidade e os objetivos de negócio. Para os analistas de negócio, é importante ter um produto minimamente funcional para lançar rapidamente no mercado-alvo, preferencialmente à frente dos concorrentes. Aproveitar uma janela oportuna de lançamento oportuna certamente é benéfico para os negócios, mas os processos de qualidade nem sempre favorecem a rapidez, o que resulta em um maior tempo de desenvolvimento. É nesse momento que entra em cena a negociação, definindo valores de negócio para funcionalidades que vão atrair mais a atenção dos usuários e, posteriormente, incrementando o software com novas funcionalidades, que, embora não sejam tão impactantes, agregam valor ao produto.

### **Questionamento importantes no processo de qualidade**

Reduzir o *time-to-market* e aproveitar uma agenda de lançamento oportuna é, sem dúvida, um desafio para as equipes de desenvolvimento. É importante ter em mente que ter um software funcional e em conformidade com os padrões de qualidade gera valor ao produto. A questão é como conciliar os atributos de qualidade com os atributos de negócio – esse pode ser o segredo do sucesso.

Na fase de levantamento de requisitos, surgirão diversos requisitos que os stakeholders consideram importantes para o sistema. No entanto, a cada requisito adicionado, o escopo do desenvolvimento aumenta, assim como o tempo necessário, não apenas para a codificação, mas também para os processos de qualidade. É nesse ponto que a negociação desempenha um papel crucial. O responsável pelo produto deve atribuir valor aos requisitos que trarão retorno mais imediato ao negócio.

Não devemos esperar que um software chegará “pronto” para ser lançado no mercado, pois essa abordagem é inviável do ponto de vista comercial, devido ao longo tempo de desenvolvimento. Dessa forma, os responsáveis precisam avaliar o custo-benefício e priorizar funcionalidades mais relevantes.

Reconhecendo que o software é um produto em constante evolução, sob a perspectiva de um desenvolvimento iterativo, é possível focar em poucas funcionalidades e realizar o processo de controle de qualidade de maneira mais eficaz, entregando um produto de qualidade dentro do prazo de lançamento planejado.

A etapa de controle de qualidade deve seguir os princípios estabelecidos na ISO/IEC 9126-1:2001. Vamos analisar os atributos e como eles se encaixam no processo. O atributo de funcionalidade diz respeito à forma como o sistema atende os desejos dos usuários. Podemos fazer algumas perguntas para avaliar se o software atende esses requisitos:

- O software cumpre os padrões de segurança e privacidade dos dados?
- O sistema executa as operações necessárias para exibir e manipular as informações inseridas pelos usuários?
- O software atende ao problema que o originou?

O atributo de confiabilidade se refere ao tempo que o sistema está disponível ao usuário. Podemos fazer seguintes perguntas:

- O software é tolerante a falhas?
- Quando ocorrem falhas, o sistema consegue se recuperar ou fornece ajuda ao usuário?

O atributo de usabilidade está relacionado ao grau de facilidade de uso. Podemos fazer as seguintes perguntas:

- O layout é facilmente compreensível?
- As funcionalidades são fáceis de aprender e entender?

Em relação ao atributo de eficiência, que mede a otimização do produto, podemos fazer as seguintes perguntas:

- O tempo necessário entre uma ação e sua resposta é adequado?
- Os recursos de hardware (memória RAM, uso de processador) estão de acordo com as características do sistema?

Já o atributo de facilidade de manutenção ou manutenibilidade trata da facilidade de realizar manutenções no sistema. Podemos validar com as seguintes questões:

- O produto é facilmente mantido ou alterado em relação às regras de negócio?
- O software é fácil de testar?

O atributo de portabilidade trata da facilidade de mover o sistema de um ambiente para outro. Algumas perguntas podem ser feitas nesse sentido:

- O sistema pode ser adaptado a diferentes ambientes?
- O software tem facilidade de substituição e/ou atualização?
- O sistema garante a integridade dos dados em diferentes ambientes?

São perguntas simples, mas que, quando validadas adequadamente, podem garantir a qualidade do produto e seu valor no mercado.

### **Processo de qualidade na prática**

Vimos anteriormente que o *time-to-market* é o tempo decorrido desde a concepção até a entrega de um produto. Como podemos reduzir esse tempo de entrega e manter a qualidade do produto? Existem diversas estratégias que podem ser adotadas, embora não haja um padrão específico para medir o *time-to-market*, pois o ponto de partida pode variar.

Algumas empresas consideram o início do desenvolvimento a partir da etapa de codificação, enquanto outras entendem que começa na etapa de concepção. O término do processo também é variável: para alguns, é quando o produto está em produção, enquanto, para outros, é a entrega ao usuário. No entanto, podemos definir que o processo começa quando há uma definição do que será feito e a equipe é alocada para o trabalho, e o ponto final pode ser considerado quando a equipe de desenvolvimento e qualidade entrega um MVP (Produto Mínimo Viável) ou a primeira versão do software.

O grande diferencial para reduzir esse tempo está no planejamento do processo. Um conceito importante nesse contexto é o *lead time,* que mede o prazo necessário para atender às demandas dos clientes. Um *lead time* aceitável pode ser alcançado por meio da padronização do processo e da automatização.

Na etapa de concepção, o uso de técnicas como *design thinking*, *user research*, *lean inception* ou *brainstorming* podem ajudar a levantar os requisitos de maneira mais assertiva.

A aplicação de padrões de desenvolvimento, ou *design patterns*, auxilia os programadores a terem uma referência, um processo bem definido de como elaborar o sistema. O uso de um processo padronizado proporciona maior agilidade, fornecendo uma base consistente e independente das pessoas envolvidas no processo.

A adoção de testes automatizados, tanto durante o desenvolvimento quanto em incrementos ou manutenções, reduz significativamente a ocorrência de falhas do produto. Embora a criação de testes automatizados possa demandar um esforço inicial maior, a médio prazo, reduz a necessidade de execução manual de testes a cada iteração ou correção do sistema.

Portanto, com o uso de ferramentas colaborativas no levantamento de requisitos, a aplicação de padrões durante o desenvolvimento e a adoção de testes automatizados na etapa de validação, é possível reduzir o *time-to-market* e entregar um produto de qualidade.

Além da automatização de testes que validam as funcionalidades em si, a validação dos atributos de qualidade pode ser feita por meio da criação de diagramas de árvore contendo os atributos de qualidade da ISO/IEC 9126-1:2001 e características pertinentes a cada um desses atributos específicos ao sistema em questão. Veja a Figura 1, que representa os atributos de qualidade e as características que devem ser validadas, com base nos questionamentos que levantamos anteriormente:

Figura 1 | Diagrama de atributos de qualidade

![](https://conteudo.colaboraread.com.br/202302/WHITE_LABEL/ARQUITETURA_DE_SOFTWARE/LIVRO/U2/assets/img/a61.png)

Fonte: elaborada pelo autor.

A Figura 1 é apenas exemplo de como podemos abordar a validação dos atributos de qualidade ao avaliar um sistema, de modo a assegurar a qualidade do produto.

Portando, ter processos padronizados no desenvolvimento, ter requisitos priorizados e bem definidos, utilizar um processo de validação automatizado e ter um claro entendimento dos atributos de qualidade pode contribuir para a redução do tempo de produção e agregar qualidade na entrega do produto.

### **Saiba mais**

No texto desta aula, citamos algumas técnicas para levantamento de requisitos. Seguem materiais interessantes que podem ajudar a expandir seus conhecimentos sobre essa temática:

[*Lean Inception](https://caroli.org/lean-inception-saiba-como-alinhar-pessoas-e-construir-o-produto-certo/)* é uma ferramenta colaborativa com o intuito de alinhar um grupo de pessoas para a definição de objetivos e/ou escopo de um projeto.

[*Design Thinking*](https://rockcontent.com/br/blog/design-thinking) é outra ferramenta de pensamento criativo focada em gerar soluções para a resolução de problemas com foco no usuário.

[*User Research*](https://medium.com/senior/mas-afinal-o-que-%C3%A9-ux-research-de-fato-e6e490cd7ce5) é uma metodologia focada na investigação dos usuários e seus requisitos, compreendendo o contexto de uso.

[*Brainstorming*](https://rockcontent.com/br/blog/brainstorming) é uma técnica colaborativa para o surgimento de ideias criativas.

Sobre os padrões de desenvolvimento ou [*design patterns.*](https://www.hostgator.com.br/blog/design-patterns-e-seus-beneficios)