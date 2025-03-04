# aula 2 - decompondo a definição de arquitetura de software

### **introdução**

Olá, estudante!

Nesta aula, exploraremos os conceitos fundamentais da arquitetura de software, incluindo sua definição, elementos - chave e processos essenciais de tomada de decisão. Também discutiremos o papel crítico que a qualidade arquitetônica e os atributos de visão desempenham na formação do sucesso de um projeto de software.

Ao longo desta aula, usaremos exemplos para ilustrar como diferentes decisões arquiteturais podem impactar o processo de desenvolvimento e o produto. Ao final dela, você terá uma compreensão da definição da arquitetura de software e do papel crucial que ela desempenha na criação de software eficiente e eficaz. Prepare-se para embarcar nessa jornada no mundo da arquitetura de software!

Comentários: 
- qual a função da qualidade do modelo de arquitetura e os atributos. o que tudo isso impacta no resultado final e quais são esses impactos.

- a escolha do modelo de arquitetura impacta diretamente na eficiência e eficácia do sistema de software.

-  Interdependência: sub. fem. : estado ou qualidade de duas pessoas ou coisas ligadas entre si por uma recíproca dependência, em virtude da qual realizam as mesmas finalidades pelo auxílio mútuo ou coadjuvação recíproca.

- Basicamente, para arquitetar um sistema de software é necessário fazer uso de elementos arquiteturais que são: módulos, componentes, conectores, modelo de dados e propriedades.
Após isso, devem ser tomadas decisões arquitetônicas referente aos requisitos do projeto, às restrições de recursos e às necessidades do usuário.
E por último, avaliar a qualidade desse sistema verificando as características (atributos) dele que são: desempenho, segurança, confiabilidade, usabilidade e escalabilidade, capacidade de manutenção.

- visão arquitetural:
qual é o objetivo e metas desse sistema?

R: criar uma plataforma escalável, segura e fácil de usar e que possa lidar cum grande volume de transações.

decisão arquitetural:
quais os requisitos, restrições e necessidades?

R: usar uma arquitetura baseada em micro serviços e implantar a plataforma em uma infraestrutura baseada em nuvem.

Bons estudos!

### **Revelando a arquitetura de software**

# **Elementos arquiteturais**

De acordo com Perry e Wolf (1992), os **elementos arquiteturais são os blocos de construção** da arquitetura de software. Esses elementos são os **componentes básicos** usados para criar a arquitetura de um sistema de software. Exemplos de elementos arquiteturais incluem **módulos**, **componentes**, **conectores** e **modelos de dados**. Os elementos arquiteturais fornecem a base para o projeto e desenvolvimento do sistema de software.

A relação entre os elementos arquiteturais é crucial para o sucesso de um sistema de software. Os componentes e conectores devem trabalhar juntos para garantir que o sistema funcione conforme o esperado. Portanto, os arquitetos de software devem considerar cuidadosamente o projeto e a utilização dos elementos arquiteturais para garantir que o sistema funcione conforme esperado pelo usuário final (PERRY; WOLF, 1992).

Compreender os diferentes elementos arquiteturais e seus relacionamentos é essencial para criar um sistema de software bem projetado. À medida que os sistemas de software se tornam cada vez mais complexos, é ainda mais difícil ter uma profunda compreensão dos elementos arquiteturais e suas interdependências. Ao dominar os elementos fundamentais da arquitetura de software, os arquitetos podem criar sistemas de software eficientes, confiáveis e sustentáveis ao longo do tempo.

# **Decisões arquiteturais**

Para Pressman e Maxim (2021), “as decisões sobre a arquitetura do software identificam importantes problemas do projeto e o raciocínio por trás das soluções arquiteturais escolhidas”. As decisões são realizadas por meio da organização do sistema de software, por exemplo, das escolhas de padrões arquiteturais e suas interfaces, através de suas colaborações e da composição desses elementos em subsistemas cada vez maiores.

As decisões arquiteturais nada mais são do que as escolhas realizadas por arquitetos de software no planejamento da estrutura de sistemas de software. De acordo com Perry e Wolf (1992), essas decisões envolvem:

- A seleção de quais componentes usar.
- Como serão as interações.
- Quais técnicas devem ser usadas para atingir a qualidade desejada do sistema.

As decisões tomadas no nível de arquitetura impactarão significativamente todo o sistema de software, incluindo seu desempenho, manutenibilidade e escalabilidade. Os arquitetos devem considerar uma ampla gama de fatores, como requisitos de projeto, restrições de recursos e necessidades do usuário ao tomar decisões arquiteturais. Com decisões arquiteturais conscientes e bem pensadas, os arquitetos de software poderão criar sistemas mais confiáveis, eficientes e econômicos.

# **Atributos de qualidade arquiteturais**

Atributos de qualidade de arquitetura são os critérios que os arquitetos de software usam para avaliar a qualidade de um sistema de software. Eles refletem as características do sistema que são as mais importantes para os *stakeholders*, como desempenho, segurança, confiabilidade e usabilidade.

Esses atributos são críticos para garantir que o sistema de software atenda às necessidades de seus usuários, além da manutenção e durabilidade dele. De acordo com Perry e Wolf (1992), identificar e priorizar atributos de qualidade arquiteturais é uma etapa essencial no processo de projeto de arquitetura de software. Se essa etapa for ignorada, pode resultar em sistemas de baixa qualidade, difíceis de manter e evoluir.

# **Visão arquitetural**

A visão arquitetural é uma descrição de alto nível das metas e objetivos da arquitetura de um sistema de software. Ele fornece um roteiro para a equipe de desenvolvimento e os *stakeholders* seguirem, a fim de garantir que o sistema atenda aos objetivos esperados para o usuário final (PRESSMAN; MAXIM, 2021).

### **Descodificando a arquitetura de software**

# **Exemplos de elementos arquiteturais**

Cada elemento arquitetural tem suas próprias responsabilidades específicas e interações com outros elementos, e eles determinam coletivamente o comportamento do sistema e os atributos de qualidade. De acordo com Pressman e Maxim (2021), nesse âmbito, podemos elencar três elementos fundamentais para qualquer projeto de software:

1. **Componentes:** unidades essenciais do sistema; podem ser definidos por módulos de software com responsabilidades específicas dentro do sistema, como gerenciamento de dados ou processamento de entrada do usuário.
2. **Propriedades:** elementos que são definidos pelas particularidades de cada componente, como desempenho e confiabilidade.
3. **Conectores:** são identificados como mecanismos pelos quais os componentes se comunicam entre si, por meio de chamadas de função ou de mensagens.

Para entender melhor como esses três componentes funcionam juntos, imagine um motor de carro. O próprio motor é um componente, sua potência e eficiência de combustível são suas propriedades, e os vários tubos e cabos que o conectam ao resto do carro são seus conectores. Ao entender esses elementos e como eles interagem, os arquitetos podem projetar sistemas de software confiáveis, eficientes e fáceis de manter.

# **Exemplos de decisões arquiteturais**

Escolher uma linguagem de programação, selecionar um sistema de gerenciamento de banco de dados, determinar a escalabilidade do sistema e projetar os recursos de segurança do sistema, são exemplos de decisões arquiteturais realizadas pelo arquiteto de software. Vamos entender um pouco mais?

- **Escolha de uma linguagem de programação:** selecionar uma linguagem de programação pode afetar o desempenho e a manutenção do sistema, pois algumas linguagens são mais adequadas para tarefas específicas do que outras.
- **Seleção de um sistema de gerenciamento de banco de dados:** a escolha de um sistema de gerenciamento de banco de dados pode afetar a capacidade de o sistema armazenar e recuperar dados com eficiência.
- **Determinar a escalabilidade do sistema:** decidir sobre a escalabilidade do sistema pode afetar a capacidade de o sistema lidar com um número crescente de usuários ou dados.
- **Recursos de segurança:** projetar os recursos de segurança do sistema pode afetar a capacidade do sistema de se proteger contra-ataques cibernéticos.

Portanto, os arquitetos devem considerar cuidadosamente essas decisões e seu impacto no design e na função geral do sistema. Pressman e Maxim (2021) enfatizam a importância de tomar decisões arquiteturais de forma correta, pois os arquitetos podem garantir que o sistema de software atenda aos objetivos desejados e possa ser facilmente adaptado às mudanças nos requisitos.

# **Por que devemos entender os atributos de qualidade arquiteturais e visão arquitetural?**

De acordo com Pressman e Maxim (2021), os atributos de qualidade arquiteturais referem-se às características de um sistema de software que determinam sua **eficácia e eficiência**. Exemplos incluem desempenho, segurança, confiabilidade e escalabilidade. A visão arquitetural, por outro lado, refere-se a um entendimento compartilhado das metas e objetivos de um sistema de software, que orienta seu projeto e implementação. Inclui elementos como a finalidade, o escopo e os *stakeholders* do sistema. Para obter um sistema de **software bem-sucedido, é crucial considerar os atributos de qualidade arquitetural e a visão desde o início do processo de design**. Ao fazer isso, podemos garantir que o sistema atenda aos seus requisitos funcionais e não funcionais, alinhando-se com os objetivos gerais do projeto.

### **Vamos entender arquitetura mais a fundo?**

A arquitetura de software é uma parte essencial do desenvolvimento de software. Envolve o uso de elementos arquiteturais, decisões arquitetônicas, visão arquitetural e atributos de qualidade para desenvolver um sistema de software que atenda aos requisitos do usuário. Elementos de arquitetura referem-se aos componentes, propriedades e conectores que compõem um sistema de software. As decisões de arquitetura, por outro lado, são as escolhas feitas pelos arquitetos de software para alcançar as propriedades desejadas do sistema, como confiabilidade, segurança e capacidade de manutenção (PRESSMAN; MAXIM, 2021).

A visão arquitetural refere-se aos objetivos de longo prazo de um sistema de software, enquanto os atributos de qualidade referem-se aos requisitos não funcionais do sistema, como desempenho, escalabilidade e usabilidade. Por exemplo, um sistema de software projetado para uma plataforma de comércio eletrônico deve ter alta disponibilidade, confiabilidade e segurança para garantir a satisfação do cliente.

Para aplicar esses conceitos de forma eficaz, os arquitetos de software precisam usar uma combinação de ferramentas, princípios e classificações. De acordo com Pressman e Maxim (2021) a ***Unified Modeling Language* (UML)** é uma dessas ferramentas que os arquitetos usam para projetar sistemas de software. O **modelo de visão 4+1**, desenvolvido por Kruchten (1995), é outra ferramenta que ajuda os arquitetos a projetar sistemas de múltiplas perspectivas, como visão lógica, visão de processo, visão física e visão de desenvolvimento.

**Os princípios que os arquitetos de software usam para projetar sistemas de software incluem modularidade, encapsulamento, abstração e separação de preocupações. Esses princípios garantem que os sistemas de software sejam fáceis de manter, entender e modificar**. A classificação dos estilos de arquitetura de software inclui camadas, cliente - servidor, microsserviços e arquitetura orientada a eventos.

# **Vamos para um exemplo prático?**

Vamos imaginar que uma equipe esteja construindo uma nova plataforma de comércio eletrônico. Sua **visão arquitetural** é criar uma plataforma escalável, segura e fácil de usar, e que possa lidar com um grande volume de transações. Para atingir essa **visão**, eles tomam várias **decisões arquiteturais**, como usar uma arquitetura baseada em micros serviços e implantar a plataforma em uma infraestrutura baseada em nuvem.

Para implementar essas decisões, eles identificam vários **elementos arquiteturais**, como: autenticação do usuário, processamento de pagamentos, catálogo de produtos e funcionalidade de pesquisa. Eles definem as propriedades desses elementos, como desempenho, disponibilidade e segurança. Também determinam os conectores entre esses elementos, como APIs e filas de mensagens, para garantir a comunicação e a coordenação adequadas entre eles.

Finalmente, eles definem vários **atributos de qualidade** arquiteturais que desejam que a plataforma tenha, como alto desempenho, disponibilidade, segurança e usabilidade. Eles desenvolvem e implementam casos de teste e métricas de desempenho para avaliar a conformidade da plataforma com esses atributos.

Em conclusão, a arquitetura de software desempenha um papel crítico no desenvolvimento de sistemas de software que atendam aos requisitos dos usuários. Os arquitetos devem usar uma combinação de ferramentas, princípios e classificações para projetar sistemas de software eficazes. Eles também devem tomar decisões arquiteturais corretas e manter uma visão arquitetural nítida em mente para garantir o sucesso do sistema a longo prazo. Por fim, os arquitetos devem equilibrar os atributos de qualidade arquitetural para garantir que o sistema funcione de maneira ideal enquanto atende aos requisitos do usuário (PRESSMAN; MAXIM, 2021). Seguindo essas diretrizes, os arquitetos podem desenvolver sistemas de software confiáveis, seguros e eficientes.