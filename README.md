# Resenha-Microservices-a-definition-of-this-new-architectural-term-Martin-Fowler-James-Lewis
O artigo de Martin Fowler e James Lewis apresenta uma definição clara e prática do estilo arquitetural conhecido como microservices, abordando também a simplicidade das aplicações monolíticas, geralmente adotadas nas fases iniciais de um sistema,definindo assim os monólitos como uma construção de unidade única.

Todo o artigo compõe uma visão prática, com ênfase no desenvolvimento de software, definindo sistemas web monolíticos como sendo divididos em apenas três partes principais: a interface do lado do cliente, o banco de dados e o servidor.Afirma-se que, mesmo sendo sistemas de difícil manutenção, esses modelos podem, por incrível que pareça, ser bem-sucedidos; contudo, quase sempre há uma grande dificuldade quando se inicia qualquer processo de adaptação ou desenvolvimento de novas versões, em alguns casos  exigindo que  até todo monolito seja reconstruído. Com tudo essas frustrações levaram à arquitetura de microserviços.

Diante de tantas dificuldades, são propostos os micro serviços para a criação de software, uma arquitetura relativamente simples e flexível que consiste na construção de aplicações compostas por um conjunto de serviços independentes, possibilitando a adoção de múltiplas linguagens de programação, distintos mecanismos de persistência de dados e alocação variável de recursos,isso evita as consequências de uma governança centralizada, fugindo da padronização rígida de tecnologias e plataformas, pois, como dito no artigo: 'Nem todo problema é um prego e nem toda solução é um martelo'.O artigo não afirma que o estilo de microservices seja novo ou inovador, mas demonstra confiança nessa abordagem, defendendo que o desenvolvimento de software tende a ser mais eficiente quando esse modelo é adotado, mesmo não existindo uma definição formal do estilo arquitetônico para micro serviços.

Como mencionado no artigo, no modelo tradicional de construção de software, existe uma equipe responsável pela criação e outra pela manutenção. Muitas vezes, o time de desenvolvimento é desfeito e redirecionado para novos projetos assim que a entrega é realizada. Os defensores dos microsserviços tendem a evitar esse modelo, optando pela ideia de que uma equipe deve ser dona do produto ao longo de sua vida útil, uma inspiração que vem da Amazon: 'Se você constrói, você o gerencia'.

Outra área beneficiada pelos microsserviços é a gestão de falhas. Empresas como a Netflix chegam a induzir falhas críticas em seus serviços, o que daria arrepios na maioria das equipes de operação para testar a resiliência do sistema. Com essa arquitetura, o monitoramento em tempo real torna-se mais eficiente e a tolerância a falhas aumenta ao maximo: como os serviços são independentes, raramente o sistema inteiro sai do ar; em vez disso, apenas uma funcionalidade(serviço) específica é afetada, mantendo o restante da aplicação operacional.


# Minha Perspectiva: A Aplicabilidade dos Microsserviços #
Particularmente, vejo a arquitetura de microsserviços como uma prática excelente que eu buscaria implementar na maioria dos meus projetos. Minha preferência se estende de pequenos a grandes projetos, o começa de um projeto ja  com uma mentalidade de serviços independentes facilita o crescimento do sistema sem que ele se torne um "monólito de difícil manutenção" no futuro.
A possibilidade de testar novas linguagens ou bancos de dados em apenas um serviço, sem colocar o restante da aplicação em risco, é o que mantém um software moderno e atualizado.
Contudo, reconheço que essa escolha exige um custo: a complexidade da comunicação entre os serviços e a necessidade de um monitoramento rigoroso. Mas, a meu ver, os benefícios de ter um sistema resiliente, onde uma falha isolada não derruba toda a operação, compensam qualquer esforço adicional de configuração inicial. Como ressaltado no artigo, os microsserviços não são uma "bala de prata", mas são, sem dúvida, o caminho para quem busca construir softwares robustos e prontos para as demandas reais do mercado.






