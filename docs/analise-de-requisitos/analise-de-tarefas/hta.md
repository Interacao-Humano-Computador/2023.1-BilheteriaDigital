# Análise Hierárquica de Tarefas

## Introdução

A Análise Hierárquica de Tarefas (HTA) é um método de análise de tarefas que visa representar e decompor uma tarefa complexa em uma hierarquia de objetivos, subobjetivos e operações, a fim de facilitar a compreensão de como um usuário realiza uma tarefa e permitir que sejam identificados pontos problemáticos e de melhoria. A HTA é amplamente utilizada em diversos contextos, como no desenvolvimento de produtos, serviços e na melhoria de processos. Ela pode ser representada por uma tabela, ou por um diagrama, com a notação conforme a figura 1.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 1</b> - Notação diagrama HTA.</p></font>

![Notação diagrama HTA](../../assets/analise-de-tarefas/elementos-hta.png#only-light){width: 300}
![Notação diagrama HTA](../../assets/analise-de-tarefas/elementos-htae.png#only-dark){width: 300}

<font size="3"><p style="text-align: center">_Fonte: BARBOSA e SILVA, 2011._<a id=anchor_1 href="#REF1"><sup>1</sup></a></p></font>

</figure>

## Análise de Tarefas

No que diz respeito às tarefas para análise com o método HTA, foram escolhidas o acesso ao meu painel e o compartilhamento de eventos, conforme explicitado nas figuras de 2 a 7 e nas tabelas de 1 a 7.

### Visualizar meus Pedidos

Nessa tarefa, o usuário possui o objetivo de visualizar um pedido dentro dos pedidos realizados. A figura 2 apresenta o diagrama HTA relativa a tarefa, já a tabela 1 representa o mesmo HTA em tabela.

<center>

<figure markdown>
<font size="3"><b>Figura 2</b> - Diagrama HTA de visualização de pedidos.</font>

![Notação diagrama HTA](../../assets/analise-de-tarefas/hta1.png#only-light){width: 300}
![Notação diagrama HTA](../../assets/analise-de-tarefas/hta1e.png#only-dark){width: 300}

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - HTA de visualização de pedidos.</p></font>

|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                                                               |
| :--------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  0.Visualizar meus pedidos   |                                                                                                                                                                                                         |
|      1.Cadastrar perfil      | **input**: dados de cadastro.<br>**feedback**: usuário redirecionado para a página de confirmação de email.<br> **plano**: confirmar conta e depois fazer login.                                        |
|     1.1.Confirmar conta      | **feedback**: após confirmar o email o usuário é liberado para fazer login.                                                                                                                             |
|       1.2.Fazer login        | **input**: dados de login.<br>**feedback**: usuário redirecionado para a página de meu painel.<br> **plano**: abrir área de meus pedidos. <br> **recomendação**: realizar a verificação em duas etapas. |
| 2.Abrir área de meus pedidos | **input**: apertar no botão "meus pedidos".<br>**feedback**: usuário redirecionado para a página de meus pedidos.<br>                                                                                   |

<font size="3">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</font>

</center>

### Compartilhar Evento nas Redes Sociais

Nessa tarefa, o usuário possui o objetivo de na página do evento o compartilhar nas redes sociais. A figura 3 apresenta o diagrama HTA relativa a tarefa, já a tabela 2 representa o mesmo HTA em tabela.

<center>

<figure markdown>

<font size="3"><b>Figura 3</b> - Diagrama HTA de compartilhamento de eventos.</font>

![Notação diagrama HTA](../../assets/analise-de-tarefas/hta2.png#only-light){width: 300}
![Notação diagrama HTA](../../assets/analise-de-tarefas/hta2e.png#only-dark){width: 300}

<font size="3">_Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny)._</font>

</figure>
                                 
<font size="3"><b>Tabela 2</b> - HTA de compartilhamento de eventos.</font>

|              Objetivos/Operações              | Problemas e recomendações                                                                                                                                                    |
| :-------------------------------------------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   0. Compartilhar evento nas redes sociais    |                                                                                                                                                                              |
|               1. Buscar evento                | **input**: entrar na página inicial do site .<br>**feedback**: lista de eventos disponíveis.<br> **plano**: encontrar evento na tela inicial ou bsucar na barra de pesquisas |
|     1.1 Encontrar evento na tela inicial      | **feedback**: após rolagem da tela há a visualização do evento.                                                                                                              |
|    1.2 Buscar evento na barra de pesquisas    | **input**: nome do evento.<br>**feedback**: abertura de tela com resultados.<br>                                                                                             |
|               2. Acessar evento               | **input**: clique no ícone do evento.<br>**feedback**: usuário redirecionado para a página da compra de ingresso do evento selecionado.<br>                                  |
|        2.1 Apertar no evento escolhido        |                                                                                                                                                                              |
|            3. Compartilhar evento             | **input**: apertar no botão da rede social em que o evento será compartilhado".<br>**feedback**: usuário redirecionado para a página da rede social escolhida.<br>           |
| 3.1 Selecionar a rede social para compartilha |                                                                                                                                                                              |

<font size="3">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</font>

</center>

### Cancelar Compra

Nessa tarefa, o usuário possui o objetivo de acessar a página de pedidos realizados e cancelar um desses pedidos. A figura 4 apresenta o diagrama HTA relativa a tarefa, já a tabela 3 representa o mesmo HTA em tabela.

<center>

<figure markdown>

<font size="3"><p style="text-align: center"><b>Figura 4</b> - Diagrama HTA de cancelamento de compra.</p></font>

![Notação diagrama HTA](../../assets/analise-de-tarefas/hta3.png#only-light){width: 300}
![Notação diagrama HTA](../../assets/analise-de-tarefas/hta3e.png#only-dark){width: 300}

<font size="3">_Fonte: [Gabriel Campello](https://github.com/G16C)._</font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - HTA de cancelamento de compra.</p></font>

|             Objetivos/Operações              | Problemas e recomendações                                                                                                                                                                                                    |
| :------------------------------------------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|              0.Cancelar compra               |                                                                                                                                                                                                                              |
|                1.Fazer login                 | **input**: dados de login.<br>**feedback**: usuário redirecionado para a página de meu painel.<br> **plano**: abrir área de meus pedidos.                                                                                    |
|           2.Acessar minhas compras           | **input**: apertar no botão "meus pedidos".<br>**feedback**: após o usuário ser redirecionado para a página de meu painel ele terá acesso às suas compras efetuadas. <br> **plano**: abrir página de detalhes sobre a compra |
|  3.Selecionar opção de ações sobre a compra  | **input**: apertar no botão "mostrar".<br>**feedback**: usuário terá acesso à ações que podem ser realizadas sobre a compra.<br> **plano**: selecionar opção de cancelar compra.                                             |
| 4.Selcionar opção de cancelamento de compras | **input**: apertar no botão "cancelar pedido".<br>**feedback**: compra será cancelada.<br>                                                                                                                                   |

<font size="3">_Fonte: [Gabriel Campello](https://github.com/G16C)._</font>

</center>

### Busca de Evento

Nessa tarefa, o usuário possui o objetivo de encontrar um evento disponível. A figura 5 apresenta o diagrama HTA relativa a tarefa, já a tabela 4 representa o mesmo HTA em tabela.

<center>

**Figura 5** - Diagrama HTA da Busca de Evento.

![Diagrama HTA da Busca de Ingressso no Modo Claro](../../assets/analise-de-tarefas/hta4.png#only-light){width: 300}
![Diagrama HTA da Busca de Ingressso no Modo Escuro](../../assets/analise-de-tarefas/hta4e.png#only-dark){width: 300}

<font size="3">_Fonte: [Matheus Henrique](https://github.com/mathonaut)._</font>

<font size="3"><b>Tabela 4</b> - HTA da Busca de Evento.</font>

|                 Objetivos/Operações                 | Problemas e recomendações                                                                                                                                                                                                                |
| :-------------------------------------------------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|               0. Busca de evento 1/2                | **input**: nome, data e loclização do evento.<br>**feedback**: a página do evento aparece na tela do usuário. <br>**plano**: encontrar evento na tela inicial ou pesquisar pelo evento na barra de pesquisa.                             |
|      1. Encontrar o evento na tela inicial 1>2      | **feedback**: usuário é redirecionado para a página do evento.<br> **plano**: clicar no evento na tela inicial e entrar na página do evento.                                                                                             |
|       1.1 Selecionar o evento na tela inicial       | **input**: clicar na imagem do evento. <br>**feedback**: a página é carregada.                                                                                                                                                           |
|           1.2 Entrar na página do evento            | **feedback**: o usuario é redirecionado para a página do evento.                                                                                                                                                                         |
| 2. Pesquisar pelo o evento na barra de pesquisa 1>2 | **input**: clique na caixa de pesquisa.<br>**feedback**: a caixa de pesquisa fica com as bordas avermelhadas.<br> **plano**: digitar o nome do evento na caixa de pesquisa, clicar no evento e entrar na página do evento.               |
| 2.1 Informar o nome do evento na caixa de pesquisa  | **input**: dados do evento.<br>**feedback**: o site atualiza a página com os eventos<br>**problema**: pesquisa não é realizada com palavras chaves levando a situações onde o evento não é encontrando mesmo ele existindo. encontrados. |
|           2.2 Entrar na página do evento            | **feedback**: o usuario é redirecionado para a página do evento.                                                                                                                                                                         |

<font size="3"><p style="text-align: center">Fonte: [Matheus Henrique](https://github.com/mathonaut).</p></font>

</center>

### Acessar a Central de Ajuda

Nessa tarefa, o usuário possui o objetivo de acessar a central de ajuda do sistema. A figura 6 apresenta o diagrama HTA relativa a tarefa, já a tabela 5 representa o mesmo HTA em tabela.

<center>

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 6</b> - Diagrama HTA de Acessar a Central de Ajuda.</p></font>

![Diagrama HTA da Acessar a Central de Ajuda no Modo Claro](../../assets/analise-de-tarefas/hta5.png#only-light){width: 300}
![Diagrama HTA da Acessar a Central de Ajuda no Modo Escuro](../../assets/analise-de-tarefas/hta5e.png#only-dark){width: 300}

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Arthur de Melo](https://github.com/arthurmlv).</p></font>

</figure>

<font size="3"><b>Tabela 6</b> - HTA de Acessar a Central de Ajuda.</font>

|                     Objetivos/Operações                      | Problemas e recomendações                                                                                                                                                                                                 |
| :----------------------------------------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|             0. Acessar aba Central de Ajuda 1>2              |                                                                                                                                                                                                                           |
| 1. Acessar área de Central de Ajuda a partir da tela inicial | **feedback**: usuário é redirecionado para a página de Central de Ajuda.<br> **plano**: clicar no botão da aba de suporte.                                                                                                |
|           1.1 Selecionar o botão da aba de suporte           | **input**: clicar no botão "Central de Ajuda". <br>**feedback**: a página é carregada.                                                                                                                                    |
|        2. Acessar a aba desejada Central de Ajuda 1/2        | **feedback**: usuário é redirecionado para o tópico desejado.<br> **plano**: escolher o tópico em destaque, caso esteja visível, ou pesquisar o tópico desejado, escolhê-lo e acessar a página que detalha a vicissitude. |
|             2.1 Selecionar o tópico em destaque              | **input**: clicar no tópico em destaque.<br>**feedback**: o site atualiza a página os resultados dentro daquele tópico.                                                                                                   |
|              2.2 Pesquisar o tópico em destaque              | **input**: clique na caixa de pesquisa e insira o que deseja pesquisar. <br> **feedback**: a página é atualizada com os resultados.                                                                                       |
|                3. Selecionar a opção desejada                | **feedback**: o usuario é redirecionado para a página detalhando o tópico escolhido.<br>**problema**: existem algumas redundâncias com tópicos diferentes levando para o mesmo texto.                                     |

<font size="3">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Arthur de Melo](https://github.com/arthurmlv).</font>

</center>

### Comprar Ingresso

<center>

<figure markdown>
<font size="3"><b>Figura 7</b> - Diagrama HTA da Compra de ingressos.</font>

![Diagrama HTA da Comprar Ingresso no Modo Claro](../../assets/analise-de-tarefas/hta6.png#only-light){width: 300}
![Diagrama HTA da Comprar Ingresso no Modo Escuro](../../assets/analise-de-tarefas/hta6e.png#only-dark){width: 300}

<font size="3">_Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Arthur de Melo](https://github.com/arthurmlv)._</font>

</figure>

<font size="3"><b>Tabela 7</b> - HTA de Compra de ingressos.</font>

|          Objetivos/Operações           | Problemas e recomendações                                                                                                                         |
| :------------------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------- |
|        0. Comprar ingresso 1>2         |                                                                                                                                                   |
|          1.1 Pesquisar evento          | **input**: clicar na caixa de pesquisa e inserir o que deseja pesquisar. <br> **feedback**: o site atualiza a página com os eventos relacionados. |
|  1.2 Selecionar o evento desejado 1+2  | **input**: clicar na imagem do evento desejado. <br>**feedback**: a página é carregada.<br>**problema**: o evento não possui mais ingressos.      |
|   2.1 Selecionar o tipo de ingresso    | **input**: clicar no botão de selecionar quantidade de ingresso. <br> **feedback**: o tipo escolhido aumenta a quantidade.                        |
|        2.2 Selecionar o assento        | **input**: selecionar o assento no mapa.<br>**feedback**: o site avisa que foi escolhida uma poltrona.                                            |
|       1.3 Realizar pagamento 1>2       | **input**: selecionar a opção de pagamento.<br>**feedback**: o site dá os detalhes para aquela opção de pagamento.                                |
| 2.3 Preencher informações de pagamento | **input**: passar os dados necessários nas caixas específicas. <br> **feedback**: as informações são confirmadas após finalizar a compra.         |
|   2.4 Receber confirmação de compra    | **feedback**: o usuario é redirecionado para a página confirmando a compra e recebe um e-mail.                                                    |

<font size="3">_Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Arthur de Melo](https://github.com/arthurmlv)._</font>

</center>

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> BARBOSA, S. D. J.; SILVA, B. S. **Interação Humano-Computador.** Rio de Janeiro: Elsevier, 2011.

## Bibliografia

> LUCAS, João. **Análise de Tarefas.** Repositório do Grupo Simples Nacional da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <<https://interacao-humano-computador.github.io/2022.2-SimplesNacional/Tarefas/Analise/>>. Acesso em: 06 de abril 2023.

## Histórico de Versão

| Versão | Data       | Descrição                                                                                               | Autor(es)                                                                                     | Revisor(es)                                    |
| ------ | ---------- | ------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| `1.0`  | 06/05/2023 | Criação da página de Processo de Design.                                                                | [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny) | [Arthur de Melo](https://github.com/arthurmlv) |
| `1.1`  | 07/05/2023 | Adição da análise de duas tarefas.                                                                      | [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny) | [Arthur de Melo](https://github.com/arthurmlv) |
| `1.2`  | 12/05/2023 | Adição da avaliação do cancelamento de compra.                                                          | [Gabriel Campello](https://github.com/G16C)                                                   | [Arthur de Melo](https://github.com/arthurmlv) |
| `1.3`  | 13/05/2023 | Adição da avaliação da Busca de Ingresso.                                                               | [Matheus Henrique](https://github.com/mathonaut)                                              | [Arthur de Melo](https://github.com/arthurmlv) |
| `1.4`  | 20/05/2023 | Adição da avaliação de Central de Ajuda e de Compra.                                                    | [Douglas Alves](https://github.com/dougAlvs) e [Arthur de Melo](https://github.com/arthurmlv) | [Geovanna Maciel](https://github.com/manuziny) |
| `2.0`  | 02/07/2023 | Correção do artefato de acordo com a [verificação realizada](../../verificacao/grupo/etapa2/at-hta.md). | [Matheus Henrique](https://github.com/mathonaut)                                              | [Arthur de Melo](https://github.com/arthurmlv) |
