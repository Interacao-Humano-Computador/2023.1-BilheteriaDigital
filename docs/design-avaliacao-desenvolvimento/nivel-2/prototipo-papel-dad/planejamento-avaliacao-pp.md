# Planejamento da Avaliação do Protótipo de Papel

## Introdução

O método de prototipação em papel permite avaliar a usabilidade de um design de IHC por meio de simulações de uso com potenciais usuários. É uma opção rápida e econômica para identificar problemas de usabilidade antes de construir uma solução executável. É útil para avaliar soluções parciais e de baixa a média fidelidade, antes de definir todos os detalhes da interface.

## Objetivo 

Esta avaliação tem como objetivo, por meio do método de prototipação em papel, identificar eventuais problemas de usabilidade nas interfaces elaboradas para as tarefas escolhidas. Já este artefato tem por objetivo planejar como será realizada essa avaliação, detalhando a metodologia, cronograma, quais telas serão criadas e como será feita a avaliação com o usuário.

## Metodologia 

A avaliação do protótipo seguirá as seguintes atividades definidas por Barbosa e Silva<a id="anchor_1" href="#REF1">^1^</a>:

* Preparação:
    * Definir tarefas para os participantes executarem.
    * Definir o perfil dos participantes e recrutá-los.
    * Criar protótipos em papel da interface para executar as tarefas.
    * Executar um teste-piloto.

* Coleta de Dados:
    * Cada usuário deve executar as tarefas propostas interagindo com os
protótipos em papel, mediado pelo avaliador.


## Preparação 

### Definir tarefas para os participantes executarem

As tarefas abordadas na avaliação serão as seguintes:

* Buscar um evento
* Comprar um ingresso
* Visualizar meus pedidos
* Cancelar Compra

**Observação** : Para os próximos passos de como as tarefas devem ser seguidas, vale ressaltar a responsabilidade do entrevistador de verificar se o zoom do protótipo de papel na ferramenta Marvel App está adequadamente configurado de acordo com a tela do participante, solicitando ajustes para aumentar ou diminuir, se necessário, de modo a facilitar a execução da tarefa e permitir uma análise mais precisa por parte do entrevistador.

#### Buscar um evento

<a id="met1"></a>
Essa tarefa tem o intuito do participante realizar uma busca de um determinado evento selecionado pelo entrevistador.

O objetivo da tarefa consiste em verificar se o participante consegue realizar uma busca de um determinado evento sem problemas.

Para a realização dessa tarefa o entrevistador fará uma apresentação da imagem da tela inicial e solicitará que o participante realize uma busca de um evento descrito pelo entrevistador. Nessa busca se o participante precisará utilizar o campo de pesquisa no qual o nome do evento será preenchido automaticamente, bastando selecionar o ícone de pesquisa para ser direcionado a uma nova tela do evento encontrado, no qual será indicado que selecione o evento com a localidade passada pelo entrevistador.  Durante a execução dessa tarefa o participante será analisada sua execução e caso o participante não consiga realizar essa tarefa identificar os problemas que o impossibilitaram.

#### Comprar um ingresso
Nessa tarefa o participante tem que realizar a compra de um ingresso de um evento selecionado na etapa anterior de [buscar um evento](#met1).

O objetivo dessa tarefa consiste em determinar se o participante consegue comprar um ingresso seguindo os passos apresentados pelo protótipo.

Para execução dessa tarefa, após o participante ter selecionado um evento com a tarefa de busca anteriormente, será orientado que realize a ação de comprar um ingresso. Para essa ação ela terá a possibilidade de selecionar 1 ingresso na área “Pista” e dar continuidade na ação Comprar Ingresso. Dando procedimento em uma nova tela precisará escolher a forma de pagamento “Pix” e concordar com os Termos de Uso e por fim finalizar a compra.  Durante a execução dessa tarefa o participante será analisada sua execução e caso o participante não consiga realizar essa tarefa identificar os problemas que o impossibilitaram.

#### Visualizar meus pedidos
Nessa tarefa o participante tem que acessar a parte de visualizar meus pedidos e encontrar pedidos já selecionados nas etapas anteriores.

O objetivo dessa tarefa é analisar se o participante por meio do protótipo consegue se localizar no sistema acessando a parte de visualizar meus pedidos.

Após a conclusão das duas tarefas anteriores, será pedido que o participante visualize seu pedido comprado anteriormente, para isso o participante deverá selecionar a opção “Meu Perfil” sendo direcionado a uma nova tela com as informações do ingresso selecionado. Durante a execução dessa tarefa o participante será analisada sua execução e caso o participante não consiga realizar essa tarefa identificar os problemas que o impossibilitaram.

#### Cancelar Compra
Essa tarefa tem o intuito do participante realizar a tarefa de cancelar uma compra no protótipo de papel apresentado pelo entrevistador.

O objetivo dessa tarefa é verificar se o participante e capaz de executar a ação de cancelar uma compra, observando se possui algum problema no protótipo que impossibilite de executá-la.

Na última tarefa será solicitada a partir da tela de “Meu Perfil” solicitando ao participante que realize a ação de Cancelar uma Compra. Para essa tarefa o participante precisará acessar a opção de “Ver Detalhes” sendo direcionado a uma nova tela com os detalhes do ingresso e com a opção de “Cancelar Comprar”, que selecionada aparecerá com modal para confirmar o cancelamento da compra. Durante a execução dessa tarefa o participante será analisada sua execução e caso o participante não consiga realizar essa tarefa identificar os problemas que o impossibilitaram.

### Definir o perfil dos participantes e recrutá-los

Para avaliação foram convidadas 5 pessoas que se encaixem no [perfil de usuário](/analise-de-requisitos/perfil-usuario). Recomenda-se ter entre 5 a 8 participantes para obter resultados significativos e identificar problemas recorrentes, selecionar um número suficiente de convidados permite obter uma amostra representativa e identificar insights relevantes. Além disso, foi considerado o cronograma e a disponibilidade de tempo para execução das entrevistas. Em cada entrevista será apresentado a eles um [termo de consentimento](https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/aspectos-eticos/#introducao) baseado no seguinte [modelo](/analise-de-requisitos/aspectos-eticos#termo-de-consentimento), e a avaliação continuará somente caso haja o consentimento destes.

### Criar protótipos em papel da interface para executar as tarefas

Deverão ser elaboradas as principais telas do sistema no protótipo de papel, de forma que elas ilustrem as [tarefas definidas anteriormente](#definir-tarefas-para-os-participantes-executarem). É importante citar que nessa etapa o foco não é estético, mas sim destacar as funcionalidades e principais elementos com os quais o usuário irá interagir. Os protótipos serão elaborados com o uso da ferramenta de prototipação [Marvel App](https://marvelapp.com), conforme exemplo apresentado pelo professor no Aprender3.

### Executar um teste-piloto

O objetivo desse teste piloto é em primeiro momento é avaliar a viabilidade e identificar problemas, ajustando o projeto antes da implementação em larga escala. Os resultados obtidos durante o teste piloto são utilizados para aprimorar o projeto e aumentar as chances de sucesso na implementação completa. Dessa forma, ele tem oportunidade de verificar se a linguagem nas explicações e nos materiais fornecidos é clara e objetiva, e se esses materiais contêm informações adequadas e suficientes para orientar o participante durante a avaliação.

O teste piloto foi feito no dia 10/06/2023 às 12:20 e com a presença dos integrantes [Douglas Alves](https://github.com/dougAlvs) e [Rafael Ferreira](https://github.com/RafaelCLG0).

Abaixo segue o vídeo feito do teste piloto de acordo com o cronograma citado anteriormente em que nele foi  verificacadas as condições codizentes para se realizar uma entrevista e como ela deve ser realiazada.

<p style="text-align: center"><a href="https://www.youtube.com/embed/s-kX0kSuv5Q" target="blanket">Clique aqui</a></p>


<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/s-kX0kSuv5Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>

## Coleta de Dados

A avaliação propriamente dita será feita de forma online pela plataforma Discord, com a presença dos usuários selecionados e do(s) avaliador(es). É papel dos avaliador apresentar o termo de consentimento e explicar aos usuários como funcionará a avaliação e quais os pontos abordados. É importante que todo o processo seja gravado. A Tabela 1 exemplifica o provável cronograma de realização da avaliação.

<center>
**Tabela 1** - Cronograma provável da Avaliação.

| Entrevistadores | Usuário | Data       | Início-Fim  | Local              |
| ------------- | ------- | ---------- | ----------- | ------------------ |
| [Douglas Alves](https://github.com/dougalvs) e [Geovanna Maciel](https://github.com/manuziny)  |<span style = "color: orange"> Nicolas Bomfim</span>| 10/06/2023 | 15:20-15:26 | Discord |
| [Douglas Alves](https://github.com/dougalvs) e [Geovanna Maciel](https://github.com/manuziny)  |<span style = "color: orange"> Lucas Maciel</span>| 10/06/2023 | 15:32-15:37 | Discord |
| [Douglas Alves](https://github.com/dougalvs) e [Geovanna Maciel](https://github.com/manuziny)  |<span style = "color: orange"> Rayssa Figueiredo</span>| 10/06/2023 | 15:49-15:55 | Discord |
| [Douglas Alves](https://github.com/dougalvs) e [Geovanna Maciel](https://github.com/manuziny)  |<span style = "color: orange"> Sidney Fernando</span>| 10/06/2023 | 16:05-16:10 | Discord |
| [Douglas Alves](https://github.com/dougalvs) e [Geovanna Maciel](https://github.com/manuziny)  |<span style = "color: orange"> Pedro Henrique</span>| 10/06/2023 | 16:14-16:20 | Discord |

</center>

<center>

**Fonte** - [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>



## Referências Bibliograficas
> <a id="REF1" href="#anchor_1">1.</a> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versão

| Versão | Data       | Descrição                                       | Autor            | Revisor                   |
| ------ | ---------- | ----------------------------------------------- | ---------------- | ------------------------- |
| 1.0    | 27/05/2023 | Criação do documento | [Douglas Alves](https://github.com/dougAlvs) | [Rafael Ferreira](https://github.com/rafaelclg0) |
| 1.1    | 27/05/2023 | Adição das Tarefas | [Rafael Ferreira](https://github.com/rafaelclg0) | [Geovanna Maciel](https://github.com/manuziny) |
| 1.2    | 10/06/2023 | Correções da tarefas e adição da gravação do teste| [Rafael Ferreira](https://github.com/rafaelclg0) | [Douglas Alves](https://github.com/dougAlvs) |


