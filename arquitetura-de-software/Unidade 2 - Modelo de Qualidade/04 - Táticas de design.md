Aula 4
Táticas de design
Nesta aula, exploraremos táticas essenciais de design. Abordaremos aspectos importantes da qualidade na arquitetura de software, como desempenho e escalabilidade; segurança e tolerância a falhas; e compreensibilidade, modificabilidade e operabilidade.


introdução
Olá, estudante!
Nesta aula, exploraremos táticas essenciais de design. Abordaremos aspectos importantes da qualidade na arquitetura de software, como desempenho e escalabilidade; segurança e tolerância a falhas; e compreensibilidade, modificabilidade e operabilidade.
Ao desenvolver um software, é crucial considerar o desempenho e a escalabilidade, garantindo que ele execute tarefas de forma ágil e possa lidar com um aumento na demanda sem comprometer sua eficiência. A segurança é um aspecto primordial para proteger o sistema e as informações contra ameaças maliciosas, enquanto a tolerância a falhas assegura que o sistema continue funcionando adequadamente mesmo diante de problemas em componentes individuais.
Além disso, veremos como tornar um software compreensível, facilitando sua manutenção e evolução, e como torná-lo altamente modificável para se adaptar a novos requisitos. Por fim, abordaremos a operabilidade, que torna o software fácil de operar e manter em ambiente de produção.

Táticas essenciais para a arquitetura de software
Ao desenvolver um software, é essencial levar em conta uma série de aspectos para assegurar que ele atenda às necessidades dos usuários e possa evoluir com o passar do tempo. Nesse contexto, algumas táticas de design são fundamentais, tais como o desempenho, a escalabilidade, a segurança, a tolerância a falhas, a compreensibilidade, a modificabilidade e a operabilidade (ZENKER et al., 2019).
O desempenho de um software diz respeito à sua capacidade de executar tarefas e processos de forma eficiente e com boa velocidade. Isso significa que o software deve ser rápido e responsivo em relação às solicitações dos usuários e às operações que precisa realizar. As métricas de desempenho incluem tempo de resposta, tempo de processamento e utilização de recursos como CPU, memória e rede (ZENKER et al., 2019).
Por outro lado, a escalabilidade do software está relacionada à sua capacidade de lidar com um aumento na demanda sem comprometer o desempenho. Existem duas abordagens principais para escalabilidade: a vertical, que envolve adicionar mais recursos a um único servidor, e a horizontal, que distribui o sistema em vários servidores para atender às demandas crescentes de forma mais eficiente (ZENKER et al., 2019). A escalabilidade é especialmente importante em sistemas que precisam lidar com muitos usuários simultâneos, como redes sociais, serviços de streaming e sites de comércio eletrônico durante eventos de alto tráfego.
Além disso, a segurança do software é um aspecto crucial que visa a proteger o sistema e as informações contra ameaças e ataques maliciosos. Isso envolve autenticação, autorização, criptografia, controle de acesso e resiliência contra ameaças como vírus, malware e invasões (ZENKER et al., 2019).
Outro aspecto importante é a tolerância a falhas, que permite ao sistema continuar funcionando adequadamente mesmo diante de falhas em alguns de seus componentes. O objetivo é evitar que uma falha isolada cause a interrupção total do sistema (ZENKER et al., 2019).
Para garantir que um software seja compreensível, ele deve ser facilmente entendido e interpretado por humanos, especialmente pelos desenvolvedores e mantenedores do sistema. Um software compreensível possui uma estrutura clara, organização lógica e é bem documentado, o que facilita a manutenção, a correção de erros e a implementação de novas funcionalidades (PRESSMAN; MAXIM, 2016).
A modificabilidade é a capacidade de um software ser facilmente modificado, adaptado ou estendido para atender a novos requisitos e melhorias. Isso é essencial em um cenário de desenvolvimento contínuo, em que mudanças frequentes são necessárias para acompanhar as demandas do mercado. Um software altamente modificável possui uma arquitetura bem definida, componentes bem encapsulados, baixo acoplamento entre módulos e uma clara separação de interesses (PRESSMAN; MAXIM, 2016).
Por fim, a operabilidade refere-se à facilidade de operar e manter o software em ambiente de produção. Um software operável permite que os operadores, administradores e usuários finais utilizem-no de forma eficiente, realizem tarefas sem dificuldades e solucionem problemas de maneira ágil. A operabilidade está relacionada à facilidade de configuração, instalação, monitoramento, gerenciamento de logs e relatórios de erros (PRESSMAN; MAXIM, 2016).
É importante ressaltar que esses aspectos não são independentes e estão frequentemente interligados. Um software compreensível tende a ser mais modificável e operável, e um software altamente modificável facilita a operação e manutenção eficiente do sistema. Portanto, ao projetar e manter sistemas de software, é essencial considerar esses aspectos para garantir um produto de qualidade, capaz de atender às necessidades em constante evolução do mercado ao longo do tempo.

Principais técnicas para uma aplicação de qualidade
A arquitetura de software é uma etapa crucial no desenvolvimento de sistemas eficientes e escaláveis, capazes de crescer conforme as necessidades. Para alcançar esse objetivo, é fundamental estabelecer requisitos específicos de desempenho e escalabilidade, definindo metas claras para tempo de resposta, taxa de transferência e utilização de recursos. Uma análise detalhada da carga esperada no sistema é essencial para dimensionar a arquitetura adequadamente.
Além disso, a escolha das tecnologias apropriadas desempenha um papel fundamental, pois diferentes tecnologias podem ter um impacto direto no desempenho e na escalabilidade do sistema. Aspectos como um projeto de banco de dados escalável, monitoramento contínuo, testes de carga e desempenho, bem como uma estratégia de escalabilidade bem definida, são elementos essenciais para garantir o sucesso do sistema em cenários reais de uso (ZENKER et al., 2019).
As decisões arquiteturais não podem negligenciar a segurança em nenhum nível. Técnicas como redundância e isolamento de componentes críticos são fundamentais para enfrentar falhas e garantir a integridade do sistema. Medidas como controle de acesso, autenticação e criptografia são imprescindíveis para proteger dados sensíveis. Além disso, testes de segurança e de falhas, juntamente com um monitoramento e registros detalhados de eventos, desempenham um papel importante para assegurar a eficácia das medidas de segurança implementadas.
Os conceitos de compreensibilidade, modificabilidade e operabilidade são elementos-chave para um desenvolvimento bem-sucedido. Para alcançar esses objetivos, várias práticas podem ser adotadas (PRESSMAN; MAXIM, 2016):

Abstração e modularização: dividir o sistema em módulos bem definidos, tornando a compreensão e a manutenção mais fáceis.
Documentação: criar documentação clara sobre a arquitetura e os padrões de design, facilitando a compreensão dos diferentes aspectos do sistema.
Padrões de nomenclatura: utilizar nomes significativos para facilitar a compreensão e a comunicação entre os membros da equipe de desenvolvimento.
Desenhar diagramas e modelos: representar a arquitetura por meio de diagramas e modelos visuais, proporcionando uma visão mais clara do sistema como um todo.
Uso de padrões de projeto: aplicar padrões de projeto que promovam a modularidade e flexibilidade, facilitando futuras alterações no sistema.
Automatização de implantação: automatizar o processo de implantação do software, reduzindo erros humanos e garantindo uma implantação mais rápida e consistente.
Gerenciamento de configuração: ter controle adequado das configurações do sistema, garantindo que as mudanças sejam gerenciadas de forma controlada e rastreável.
Logs e monitoramento: implementar registro e monitoramento do sistema em produção, permitindo uma análise detalhada do desempenho e possíveis problemas.
Projeto para confiabilidade: projetar o sistema com redundância e tolerância a falhas, aumentando a disponibilidade e confiabilidade do sistema.
Testes de operação: realizar testes para garantir o desempenho e a operabilidade do sistema em diferentes cenários.
Ao adotar esses conceitos e práticas, é possível criar um sistema mais compreensível, modificável e operável, facilitando a manutenção e evolução do software ao longo do tempo. Além disso, uma arquitetura bem planejada, segura e escalável é a base para um sistema de sucesso, capaz de atender às necessidades presentes e futuras dos usuários. Portanto, investir tempo e esforço na etapa de arquitetura é fundamental para o desenvolvimento de sistemas eficientes, confiáveis e adaptáveis.

Aplicação das táticas de design
A aplicação efetiva dos conceitos apresentados anteriormente garantirá não apenas a entrega de um produto funcional, mas também a construção de um sistema confiável, seguro e de fácil manutenção. Ao considerar cuidadosamente esses fatores desde o início do processo de desenvolvimento, o arquiteto de software poderá criar soluções sólidas que atendam às necessidades dos usuários e se adaptem às mudanças futuras.
Abaixo estão alguns exemplos práticos da aplicação dos conceitos de desempenho, escalabilidade, segurança, tolerância a falhas, compreensibilidade, modificabilidade e operabilidade na etapa de arquitetura de software (PRESSMAN; MAXIM, 2016; ZENKER et al., 2019):

Desempenho e escalabilidade
Exemplo: Uma aplicação de comércio eletrônico.

Desempenho: utilizar cache para armazenar dados frequentemente acessados, minimizando o tempo de resposta para os usuários. Quando um usuário faz uma solicitação à aplicação, o servidor de aplicação verifica se os dados necessários estão armazenados em um cache. Se os dados estiverem no cache, o servidor os recupera diretamente do cache, o que é muito mais rápido do que acessar o banco de dados.
Escalabilidade: projetar a arquitetura de forma que a aplicação possa ser facilmente distribuída em múltiplos servidores, a fim de lidar com um aumento substancial de tráfego durante picos de demanda, como vendas sazonais. Dessa forma, a aplicação é capaz de lidar com um maior número de requisições simultâneas, pois a carga é distribuída entre os servidores disponíveis. Além disso, os servidores de aplicação podem ser facilmente adicionados ou removidos da arquitetura conforme a necessidade, permitindo que a aplicação seja dimensionada de forma dinâmica para atender às demandas flutuantes de tráfego.
Segurança e tolerância a falhas
Exemplo: Sistema de gerenciamento de dados confidenciais em uma instituição financeira.

Segurança: implementar autenticação e autorização robustas, criptografar dados sensíveis em repouso e em trânsito, e realizar auditorias regulares para detectar atividades suspeitas.
Tolerância a falhas: utilizar técnicas como replicação de servidores e balanceamento de carga para garantir a disponibilidade contínua do sistema, mesmo em caso de falhas em componentes individuais. A replicação dos servidores de aplicação permite que múltiplas cópias da aplicação sejam executadas em servidores separados. Isso garante que, se um servidor falhar, outros possam assumir o processamento das requisições.
Compreensibilidade, modificabilidade e operabilidade
Exemplo: Sistema de gerenciamento de tarefas em uma equipe de desenvolvimento de software.

Compreensibilidade: organizar o código-fonte em módulos bem definidos e utilizar padrões de projeto claros para facilitar a compreensão do funcionamento do sistema.
Modificabilidade: seguir princípios de design, como o da separação de responsabilidades, a fim de tornar o código facilmente modificável sem afetar outras partes do sistema.
Operabilidade: incluir recursos, como logs detalhados e métricas para monitorar o desempenho do sistema em tempo real, facilitando a identificação e correção de problemas operacionais.
Esses exemplos ilustram como os conceitos de arquitetura de software podem ser aplicados para garantir que o sistema atenda a requisitos importantes, como desempenho, segurança e facilidade de manutenção. É essencial considerar esses fatores desde o início do processo de arquitetura, para evitar problemas futuros e tornar o software robusto e confiável.

Video Resumo
Neste vídeo, exploraremos os princípios essenciais de desempenho e escalabilidade, segurança e tolerância a falhas, bem como compreensibilidade, modificabilidade e operabilidade. Descobriremos como esses elementos fundamentais se entrelaçam para moldar sistemas complexos e aplicações inovadoras. Ao desvendar os segredos por trás dessas áreas-chave, o vídeo oferecerá uma visão panorâmica dos pilares que sustentam a uma aplicação de qualidade. Assista e amplie seu conhecimento nesse importante mundo da arquitetura de software!

 


Saiba mais
A seguir, estão algumas ferramentas e recursos que podem fornecer exemplos e auxiliar o aprendizado sobre os temas abordados nesta aula:
Desempenho e escalabilidade
Apache JMeter: uma ferramenta de teste de carga de código aberto amplamente utilizada para medir o desempenho e a escalabilidade de aplicações web, serviços e servidores.
Segurança e tolerância a falhas
OWASP WebGoat: uma aplicação web de código aberto propositalmente insegura, desenvolvida para fins educacionais, que ensina sobre vulnerabilidades de segurança em aplicações web.
Chaos Monkey: uma ferramenta de engenharia de caos desenvolvida pela Netflix, que introduz aleatoriamente falhas em componentes de sistemas distribuídos para testar a tolerância a falhas.
Compreensibilidade, modificabilidade e operabilidade
SonarQube: uma plataforma de análise de código-fonte que identifica problemas de qualidade, segurança e compreensibilidade do código, auxiliando na sua modificação e operabilidade.
Docker: uma plataforma de virtualização de contêineres que permite empacotar, distribuir e executar aplicações em ambientes isolados, melhorando a operabilidade e a portabilidade do software.
(Observação: os sites indicados estão originalmente em língua inglesa, mas você pode utilizar a opção de tradução automática do seu navegador, se preferir.)