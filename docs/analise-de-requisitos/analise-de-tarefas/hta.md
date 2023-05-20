# Análise Hierárquica de Tarefas

## Introdução

A Análise Hierárquica de Tarefas (HTA) é um método de análise de tarefas que visa representar e decompor uma tarefa complexa em uma hierarquia de objetivos, subobjetivos e operações, a fim de facilitar a compreensão de como um usuário realiza uma tarefa e permitir que sejam identificados pontos problemáticos e de melhoria. A HTA é amplamente utilizada em diversos contextos, como no desenvolvimento de produtos, serviços e na melhoria de processos. Ela pode ser representada por uma tabela, ou por um diagrama, com a notação conforme a figura 1.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 1</b> - Notação diagrama HTA.</p></font>

![Notação diagrama HTA](../../assets/analise-de-tarefas/elementos-hta.png#only-light){width: 300}
![Notação diagrama HTA](../../assets/analise-de-tarefas/elementos-htae.png#only-dark){width: 300}

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

</figure>

## Análise de tarefas:

No que diz respeito as tarefas para análise com o método HTA, foram escolhidas o acesso ao meu painel e o compartilhamento de eventos, conforme explicitado nas figuras de 2 a 5 e nas tabelas de 1 a 4.

### Visualizar meus pedidos

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 2</b> - Diagrama HTA de visualização de pedidos.</p></font>

![Notação diagrama HTA](../../assets/analise-de-tarefas/hta1.png#only-light){width: 300}
![Notação diagrama HTA](../../assets/analise-de-tarefas/hta1e.png#only-dark){width: 300}

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Tabela HTA de visualização de pedidos.</p></font>

|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                        |
| :--------------------------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  0.Visualizar meus pedidos   |                                                                                                                                                                  |
|      1.Cadastrar perfil      | **input**: dados de cadastro.<br>**feedback**: usuário redirecionado para a página de confirmação de email.<br> **plano**: confirmar conta e depois fazer login. |
|     1.1.Confirmar conta      | **feedback**: após confirmar o email o usuário é liberado para fazer login.                                                                                      |
|       1.2.Fazer login        | **input**: dados de login.<br>**feedback**: usuário redirecionado para a página de meu painel.<br> **plano**: abrir área de meus pedidos.                        |
| 2.Abrir área de meus pedidos | **input**: apertar no botão "meus pedidos".<br>**feedback**: usuário redirecionado para a página de meus pedidos.<br>                                            |

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

</figure>

### Compartilhar evento nas redes sociais

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 3</b> - Diagrama HTA de compartilhamento de eventos.</p></font>

![Notação diagrama HTA](../../assets/analise-de-tarefas/hta2.png#only-light){width: 300}
![Notação diagrama HTA](../../assets/analise-de-tarefas/hta2e.png#only-dark){width: 300}

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

</figure>
                                 
<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Tabela HTA de compartilhamento de eventos.</p></font>

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

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

### Cancelar compra

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 4</b> - Diagrama HTA de cancelamento de compra.</p></font>

![Notação diagrama HTA](../../assets/analise-de-tarefas/hta3.png#only-light){width: 300}
![Notação diagrama HTA](../../assets/analise-de-tarefas/hta3e.png#only-dark){width: 300}


<font size="3"><p style="text-align: center">Fonte: [Gabriel Campello](https://github.com/G16C).</p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Tabela HTA de visualização de pedidos.</p></font>

|             Objetivos/Operações              | Problemas e recomendações                                                                                                                                                                                                    |
| :------------------------------------------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|              0.Cancelar compra               |                                                                                                                                                                                                                              |
|                1.Fazer login                 | **input**: dados de login.<br>**feedback**: usuário redirecionado para a página de meu painel.<br> **plano**: abrir área de meus pedidos.                                                                                    |
|           2.Acessar minhas compras           | **input**: apertar no botão "meus pedidos".<br>**feedback**: após o usuário ser redirecionado para a página de meu painel ele terá acesso às suas compras efetuadas. <br> **plano**: abrir página de detalhes sobre a compra |
|  3.Selecionar opção de ações sobre a compra  | **input**: apertar no botão "mostrar".<br>**feedback**: usuário terá acesso à ações que podem ser realizadas sobre a compra.<br> **plano**: selecionar opção de cancelar compra.                                             |
| 4.Selcionar opção de cancelamento de compras | **input**: apertar no botão "cancelar pedido".<br>**feedback**: compra será cancelada.<br>                                                                                                                                   |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Campello](https://github.com/G16C).</p></font>

### Busca de Ingresso

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 5</b> - Diagrama HTA da Busca de Ingresso.</p></font>

![Diagrama HTA da Busca de Ingressso no Modo Claro](../../assets/analise-de-tarefas/hta4.png#only-light){width: 300}
![Diagrama HTA da Busca de Ingressso no Modo Escuro](../../assets/analise-de-tarefas/hta4e.png#only-dark){width: 300}

<font size="3"><p style="text-align: center">Fonte: [Matheus Henrique](https://github.com/mathonaut).</p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 4</b> - Tabela HTA da Busca de Ingresso.</p></font>

|                 Objetivos/Operações                 | Problemas e recomendações                                                                                                                                                                                                  |
| :-------------------------------------------------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|              0. Busca de ingresso 1/2               | **input**: nome, data e loclização do evento.<br>**feedback**: a página do evento aparece na tela do usuário. <br>**plano**: encontrar evento na tela inicial ou pesquisar pelo evento na barra de pesquisa.               |
|      1. Encontrar o evento na tela inicial 1>2      | **feedback**: usuário é redirecionado para a página do evento.<br> **plano**: clicar no evento na tela inicial e entrar na página do evento.                                                                               |
|        1.1 Clicar no evento na tela inicial         | **input**: clicar na imagem do evento. <br>**feedback**: a página é carregada.                                                                                                                                             |
|           1.2 Entrar na página do evento            | **feedback**: o usuario é redirecionado para a página do evento.                                                                                                                                                           |
| 2. Pesquisar pelo o evento na barra de pesquisa 1>2 | **input**: clique na caixa de pesquisa.<br>**feedback**: a caixa de pesquisa fica com as bordas avermelhadas.<br> **plano**: digitar o nome do evento na caixa de pesquisa, clicar no evento e entrar na página do evento. |
|  2.1 Digitar o nome do evento na caixa de pesquisa  | **input**: dados do evento.<br>**feedback**: o site atualiza a página com os eventos encontrados.                                                                                                                          |
|                2.2 Clicar no evento                 | **input**: clique na imagens do evento. <br> **feedback**: a página é carregada.                                                                                                                                           |
|           2.3 Entrar na página do evento            | **feedback**: o usuario é redirecionado para a página do evento.                                                                                                                                                           |

<font size="3"><p style="text-align: center">Fonte: [Matheus Henrique](https://github.com/mathonaut).</p></font>

### Acessar a Central de Ajuda

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 6</b> - Diagrama HTA de Acessar a Central de Ajuda.</p></font>

![Diagrama HTA da Busca de Ingressso no Modo Claro](../../assets/analise-de-tarefas/hta5.png#only-light){width: 300}
![Diagrama HTA da Busca de Ingressso no Modo Escuro](../../assets/analise-de-tarefas/hta5e.png#only-dark){width: 300}

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves dos Santos](https://github.com/dougAlvs).</p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 6</b> - Diagrama HTA de Acessar a Central de Ajuda.</p></font>

## Bibliografia

> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

> Análise de tarefas. Disponível em: <<https://interacao-humano-computador.github.io/2022.2-SimplesNacional/>>. Acesso em 06 de abril de 2023.

## Histórico de Versão

| Versão | Data       | Descrição                                      | Autor(es)                                                                                     | Revisor(es)                                    |
| ------ | ---------- | ---------------------------------------------- | --------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| `1.0`  | 06/05/2023 | Criação da página de Processo de Design.       | [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny) | [Arthur de Melo](https://github.com/arthurmlv) |
| `1.1`  | 07/05/2023 | Adição da análise de duas tarefas.             | [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny) | [Arthur de Melo](https://github.com/arthurmlv) |
| `1.2`  | 12/05/2023 | Adição da avaliação do cancelamento de compra. | [Gabriel Campello](https://github.com/G16C)                                                   | [Arthur de Melo](https://github.com/arthurmlv) |
| `1.3`  | 13/05/2023 | Adição da avaliação da Busca de Ingresso.      | [Matheus Henrique](https://github.com/mathonaut)                                              | [Arthur de Melo](https://github.com/arthurmlv) |
