# Trabalho ADD - Attribute-driven design

> Attribute Driven Design (ADD) foi desenvolvido pelo Software Engineering Institute (SEI) na Carnegie Mellon University.
> Foi criado como uma abordagem ao design de software que se concentra em identificar e modelar atributos (características) de um sistema que são importantes para seus usuários e partes interessadas,
> com o objetivo de criar sistemas que sejam altamente adaptáveis, fáceis de manter e escaláveis, e que atendam às necessidades de usuários e partes interessadas.

> Trata-se de um método sistemático e passo a passo para projetar a arquitetura de software. Ele segue um processo de decomposição recursiva onde, em cada estágio da decomposição,
> táticas e padrões arquitetônicos são escolhidos para satisfazer um conjunto de cenários de atributos de qualidade.

> O input do ADD inclui requisitos funcionais conhecidos, requisitos de atributos de qualidade e restrições.
>   1. Requisitos funcionais: Especificados com uma lista de recursos ou casos de uso.
>   2. Requisitos de atributos de qualidade: Especificados usando cenários de atributos de qualidade.
>   3. Restrições: Decisões de design que são definidas por fatores externos/regras de negócio.

> O método ADD é um método de decomposição recursiva. O sistema geral é dividido em uma coleção de "subsistemas conceituais", que por sua vez são decompostos em "componentes conceituais".
> Como o método é recursivo, os mesmos passos são aplicados tanto para a decomposição do sistema quanto dos subsistemas conceituais. A cada etapa principal do método ADD, os drivers arquiteturais
> (fatores que influenciam a arquitetura) do elemento que está sendo decomposto são identificados. Em seguida, o elemento é decomposto, e essa decomposição é verificada de acordo com os requisitos
> de atributos de qualidade e os casos de uso que representam as funcionalidades essenciais.

> O ADD segue essencialmente uma estratégia de “Planejar, Fazer e Verificar”:
>   1. Planejar: atributos de qualidade e restrições de projeto são considerados para selecionar quais tipos de elementos serão usados ​​na arquitetura;
>   2. Do: Os elementos são instanciados para satisfazer os requisitos dos atributos de qualidade assim como requisitos funcionais;
>   3. Verificação: O projeto resultante é analisado para determinar se os requisitos foram atentidos.

> Este processo é repetido até que todos os requisitos arquitetônicos significativos sejam atendidos.
> De acordo com o livro “Quality Attribute Design Primitives”, o método ADD é baseado no entendimento da relação entre qualidades de um software e os mecanismos arquisteturais usados para atingir tais
> qualidades. Esse método tem como foco atingir duas metas principais:
>   1. Dar suporte aos estágios iniciais do processo de design, nos quais a capacidade de atingir os atributos de qualidade desejados é determinada;
>   2. Permitir que o projeto comece cedo o suficiente no ciclo de vida para apoiar as modernas necessidades time-to-market.

> O processo começa com a revisão de entradas, garantindo que as etapas de finalidade do projeto, requisitos funcionais e preocupações anteriores estejam claras. Em seguida, escolhe-se um elemento do sistema
> para ser o foco da iteração. Esse elemento é refinado, priorizando os requisitos dos stakeholders. Após isso, define-se o conceito de design, identificando os principais tipos de elementos e seus
> relacionamentos. Os elementos de software são então atribuídos responsabilidades baseadas nos requisitos funcionais. A seguir, as interfaces são detalhadas, incluindo sintaxe, semântica, dados e atributos
> de qualidade. Finalmente, é feita uma análise de performance para verificar se é necessário voltar às etapas anteriores ou seguir para a próxima iteração.
