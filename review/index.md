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

In general, you want to find the *best* reviewers you can who are capable of
responding to your review within a reasonable period of time.

The best reviewer is the person who will be able to give you the most thorough
and correct review for the piece of code you are writing. This usually means the
owner(s) of the code, who may or may not be the people in the OWNERS file.
Sometimes this means asking different people to review different parts of the
CL.

If you find an ideal reviewer but they are not available, you should at least CC
them on your change.

### In-Person Reviews {#in_person}

If you pair-programmed a piece of code with somebody who was qualified to do a
good code review on it, then that code is considered reviewed.

You can also do in-person code reviews where the reviewer asks questions and the
developer of the change speaks only when spoken to.

## See Also {#seealso}

-   [How To Do A Code Review](reviewer/): A detailed guide for code reviewers.
-   [The CL Author's Guide](developer/): A detailed guide for developers whose
    CLs are going through review.
