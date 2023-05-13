# GOMS (Goals, Operators, Methods and Selection Rules)

## Introdução

O método GOMS (Goals, Operators, Methods, Selection Rules) é uma abordagem de análise de tarefas que visa descrever as etapas que um usuário segue para realizar uma tarefa em um sistema. O GOMS é baseado em um conjunto de regras que descrevem como as metas do usuário são alcançadas por meio da seleção de operadores, métodos e regras de seleção. O método é útil para avaliar a eficiência e usabilidade de interfaces de usuário e sistemas, além de ajudar na identificação de possíveis problemas e áreas de melhoria. As tarefas são descritas em:

* Objetivos: representam as metas que o usuário deseja alcançar por meio do uso do sistema.
* Operadores: são as ações cognitivas ou físicas que o sistema permite que o usuário execute, como inserir dados via teclado, selecionar opções em menus ou clicar em botões.
* Métodos: são sequências estabelecidas de sub-objetivos e operadores que permitem que o usuário atinja um objetivo maior.
* Regras de seleção: são utilizadas para decidir qual método usar em uma determinada situação.


## Motivo da escolha

Dentre os modelos de análise de tarefas ofertados na disciplina, escolhemos o CNM-GOMS porque é frequentemente usado para prever o desempenho de várias tarefas. O que significa que podemos identificar ponto específicos em que os usuários podem se confundir ou cometer erros, desta forma podemos trabaçhar para corrigi-los. Além de ser uma compreensão sólida da cognição humana, é detalhado e permite a identificação de problemas específicos e é uma técnica comprovada e estabelecida na área de design de interação.

## Análise de tarefas:

### Comprar Ingresso

```
GOAL 0: Adquirir um ingressos
    GOAL 1: Acessar o site de venda de ingresso
        OP 1.1: Guiar o mouse ao navegador
        OP 1.2: Guiar o mouse para a barra de busca
        OP 1.3: Digitar o endereço do site
        OP 1.4: Pressionar o enter e ir ao site
    GOAL 2: Selecionar o evento
        OP 2.1: Perceber a informação visual do evento
        OP 2.2: Selecionar o evento desejado
    GOAL 3: Selecionar o tipo de ingresso
        (Sel. Rule: O evento não disponibiliza asssento)
            OP 3.1: Selecionar o tipo de ingresso
            OP 3.2: Passar o mouse no botão de compra
            OP 3.3: Clicar no botão de compra
    GOAL 4: Realizar pagamento
        OP 4.1: Preencher as informações de pagamento
        OP 4.2: Clicar na confirmação de compra
    GOAL 5: Receber confirmação de compra
        (Sel. Rule: O sistema deve confirmar a compra e fornecer um recibo ou comprovante para o usuário.)
            OP 5.1: Receber a confirmação no e-mail de cadastro

```

### Busca de ingresso

```
GOAL 0: Encontrar um evento
    GOAL 1: Acessar o site de venda de ingresso
        OP 1.1: Guiar o mouse ao navegador
        OP 1.2: Guiar o mouse para a barra de busca
        OP 1.3: Digitar o endereço do site
        OP 1.4: Pressionar o enter e ir ao site
    GOAL 2: Procurar o evento desejado
        OP 2.1: Guiar o mouse para a caixa de busca
        OP 2.2: Clicar na caixa de busca
        OP 2.3: Digitar o nome do evento
    GOAL 3: Acessar o evento pesquisado
        (Sel. Rule: O evento pesquisado está disponível.)
            OP 3.1: Guiar o mouse ao evento
            OP 3.2: Clicar no evento pesquisado

```
### Acessar aba Central de Ajuda

```
GOAL 0: Encontrar a aba de suporte ao cliente
    GOAL 1: Acessar o site da palataforma
        OP 1.1: Guiar o mouse ao navegador
        OP 1.2: Guiar o mouse para a barra de busca
        OP 1.3: Digitar o endereço do site
        OP 1.4: Pressionar o enter e ir ao site
    GOAL 2: Acessa a área de Central de Ajuda
        OP 2.1: Guiar o mouse para a aba de suporte
        OP 2.2: Pressionar a tecla
    GOAL 3: Acessar a aba Central de Ajuda
        OP 3.1: Guiar o mouse para a opção de ajuda desejada
        OP 3.2: Clicar na opção

```

### Cancelar compra

```
GOAL 0: Fazer login na página
    GOAL 1: Acessar aba meu painel
        OP 1.1: Guiar o mouse para a aba meu painel
        0P 1.2: Pressionar o botão
    GOAL 2: Selecionar a opção minhas compras 
        OP 2.1: Guiar o mouse para a opção 'mostrar'
        OP 2.2: Clicar no botão de seleção
    GOAL 3: Selecionar a opção de cancelamento de compras
        OP 3.1: Guiar o mouse para a opção de cancelamento de compras
        OP 3.2: Selecionar a compra que deseja cnacelar
        OP 3.3: Clicar no botão de cancelamento

```

## Bibliografia
>BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

>Análise de tarefas. Disponível em: <<https://interacao-humano-computador.github.io/2022.2-Lichess/>>. Acesso em 06 de abril de 2023.


## Histórico de Versão

| Versão |    Data    |                Descrição                 |                    Autor(es)                     |                 Revisor(es)                  |
| ------ | ---------- | ------------------------------------------- | ------------------------------------------------ | ------------------------------------------- |
| `1.0`  | 06/05/2023 | Criação da página de Processo de Design. | [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny) | [Arthur de Melo](https://github.com/arthurmlv) |
| `1.1` | 07/05/2023 | Adição do modelo GOMS. | [Geovanna Maciel](https://github.com/manuziny) | [Arthur de Melo](https://github.com/arthurmlv)
| `1.2` | 13/05/2023 | Adição da opção de cancelar compra no modelo GOMS. | [Gabriel Campello](https://github.com/G16C) | [Rafael Ferreira](https://github.com/RafaelCLG0)
