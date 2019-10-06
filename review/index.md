# Guia de Code Review para o desenvolvedor

## Introdução {#intro}

O _code review_ é o processo em que alguém, que não o próprio autor do código, o examina.

No Google, o code review é usado para mantermos a qualidade do nosso código e dos nossos produtos.

Essa documentação é a descrição canônica dos processos e políticas de code review no Google.

Essa página dá uma visão geral do nosso processo de code review. Há outros dois grandes documentos que fazem parte desse guia:

-   **[Como realizar um code review](reviewer/)**: Um guia detalhadao para quem vai fazer a revisão.
-   **[O guia do autor de uma CL](developer/)**: Um guia detalhado para os desenvolvedores que mandam suas CLs para revisão.

## O que revisores de código avaliam? {#look_for}

Quem fará o code review deve se atentar em:

-   **Design**: O código foi bem arquitetado e é apropriado para o seu sistema?
-   **Funcionalidade**: O código se comporta da maneira que o autor pretendia? A maneira que o código se comporta é boa para os usuários?
-   **Complexidade**: O código poderia ser mais simples? Outro desenvolvedor 
    conseguiria entender e dar manutenção facilmente nesse código no futuro?
-   **Testes**: O código tem testes automatizados completos e que dão uma cobertura?
-   **Nomenclatura**: O desenvolvedor utilizou nomes claros e diretos para variáveis, classes, métodos, etc?
-   **Comentários**: Os comentários são claros e úteis?
-   **Estilo de código**: O código segue nossos [padrões de código](http://google.github.io/styleguide/)?
-   **Documentação**: O desenvolvedor atualizou as documentações necessárias?

Veja **[Como fazer o code review](reviewer/)** para mais informações.

### Selecionando os melhores revisores {#best_reviewers}

Em geral, você deve escolher os *melhores* revisores e que possam realizar o _code review_ dentro de um tempo razoável.

O melhor revisor é a pessoa que conseguirá fazer uma revisão bem detalhada e correta para o determinado código que você escreveu.

Normalmente será o autor (ou autores) do código, que pode, ou não, estar no arquivo "OWNERS".

Pode ser que às vezes seja necessário pedir para que pessoas diferentes revisem partes diferentes do CL.

Se você encontrar o revisor "ideal" mas não estiver disponível para fazer a revisão, você deve marcar a pessoa no seu CL.

### Revisões ao vivo {#in_person}

Se você fez um _pair-programming_ com uma pessoa que seria qualificada pra fazer um bom _code review_ desse código, então esse trecho de código pode ser considerado revisado.

Você também pode realizar um review ao vivo em que o revisor faz perguntas e o autor das alterações fala somente quando questionado.

## Veja também {#seealso}

-   [Como fazer um code review](reviewer/): Um guia detalhadao para quem vai fazer a revisão.
-   [O guia do autor de uma CL](developer/): Um guia detalhado para os desenvolvedores que mandam suas CLs para revisão.
