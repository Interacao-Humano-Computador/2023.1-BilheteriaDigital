# Verificação do Análise de Tarefas - Análise Hierárquica de Tarefas

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas acerca do artefato de [Análise de Tarefas - Análise Hierárquica de Tarefas](../../../../analise-de-requisitos/analise-de-tarefas/hta) da Etapa 2 do [grupo](https://github.com/Interacao-Humano-Computador/2023.1-BilheteriaDigital).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das checklists elaboradas na página de [planejamento](../etapa2/planejamento-verificacao-etapa2-grupo). Para responder às perguntas apresentadas nas checklist o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários.

## Cronograma e Participantes

Os participantes são os integrantes do grupo [Matheus Henrique](https://github.com/mathonaut), que será responsável por realizar a verificação e a correção dos problemas encontrados. Além disso, o integrante do grupo [Rafael Ferreira](https://github.com/RafaelCLG0) realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](../etapa2/planejamento-verificacao-etapa2-grupo).

<center>

**Tabela 1** - Participantes da Verificação.

|                   Participante                   |   Papel   |
| :----------------------------------------------: | :-------: |
| [Matheus Henrique](https://github.com/mathonaut) | Avaliador |
| [Rafael Ferreira](https://github.com/RafaelCLG0) |  Revisor  |

_Fonte: [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

### Sumários dos Dados Encontrados

A tabela 2 a seguir apresenta a checklist com os dados obtidos a partir da verificação. As fontes de cada pergunta foram apresentadas na página de [planejamento](../planejamento-verificacao-etapa2-grupo/#analise-de-tarefas-analise-hierarquica-de-tarefas).

<center>

**Tabela 2** - Checklist de Verificação.

|  ID  | Descrição                                                                                                                                                                            | Avaliação  | Observações |
| :--: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :--------: | :---------: |
|      | **Padronização**                                                                                                                                                                     |
|  1   | O artefato possui introdução?                                                                                                                                                        |    Sim     |      -      |
|  2   | O artefato possui uma bibliografia/referência bibliográfica?                                                                                                                         |    Sim     |      -      |
|  3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores?                                                                               |    Sim     |      -      |
|  4   | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                                                                                                         |    Sim     |      -      |
|  5   | Todos os textos estão na norma padrão?                                                                                                                                               |    Não     |      -      |
|      | **Análise Hierárquica de Tarefas**                                                                                                                                                   |            |             |
|  6   | Os objetivos a serem alcançados são apresentados?                                                                                                                                    | Incompleto |      -      |
|  7   | As tarefas foram descritas em termos de objetivos que os usuários precisam executar, evitando descrições vagas ou ambíguas?                                                          | Incompleto |      -      |
|  8   | As tarefas apresentadas são verossímeis?                                                                                                                                             |    Sim     |      -      |
|  9   | As tarefas foram formuladas de maneira conceitual e orientada ao usuário, focando nas ações que eles executam, em vez de detalhes técnicos ou da implementação/interface do sistema? |    Sim     |      -      |
|  10  | As tarefas são decompostas?                                                                                                                                                          |    Sim     |      -      |
|  11  | As tarefas relacionam o que as pessoas fazem com o porquê o fazem e quais as consequências caso não façam corretamente?                                                              | Incompleto |      -      |
|  12  | Os diagramas apresentam os elementos esperados (plano, objetivos, operações e as relações entre os subobjetivos)?                                                                    | Incompleto |      -      |
|  13  | As operações são especificadas?                                                                                                                                                      |    Sim     |      -      |
| 13.1 | Elas possuem entradas?                                                                                                                                                               |    Sim     |      -      |
| 13.2 | Elas possuem ações?                                                                                                                                                                  |    Sim     |      -      |
| 13.3 | Elas possuem _feedbacks_?                                                                                                                                                            |    Sim     |      -      |
|  14  | A decomposição termina quando os objetivos são atingidos ou quando a origem de um erro é identificada?                                                                               |    Sim     |      -      |
|  15  | As tarefas são apresentadas em tabelas?                                                                                                                                              |    Sim     |      -      |
| 15.1 | As tabelas apresentam os objetivos/operações?                                                                                                                                        |    Sim     |      -      |
| 15.2 | As tabelas apresentam os problemas e recomendações?                                                                                                                                  |    Não     |      -      |
| 15.3 | As tabelas apresentam as entradas, ações, _feedbacks_ e os planos?                                                                                                                   |    Sim     |      -      |

_Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

## Problemas Encontrados e Análise dos Dados

### ID 05 - Todos os textos estão na norma padrão?

- No tópico "Análise de tarefas" a frase "... respeito as tarefas..."" está errada.

### ID 6 - Os objetivos a serem alcançados são apresentados?

Os objetivos não são apresentados corretamente, é abordado os objetivos de acessar meu painel (que não existe uma HTA para) e compartilhar eventos os outros são chamados apenas por tabelas e figura sem uma explicação prévia.

### ID 7 - As tarefas foram descritas em termos de objetivos que os usuários precisam executar, evitando descrições vagas ou ambíguas?

As tarefas não possuem uma descrição clara, fica a cargo da pessoa que visualiza em entender os diagramas e tabelas.

### ID 11 - As tarefas relacionam o que as pessoas fazem com o porquê o fazem e quais as consequências caso não façam corretamente?

Não é apresentado as consequências caso os usuários não façam corretamente.

### ID 12 - Os diagramas apresentam os elementos esperados (plano, objetivos, operações e as relações entre os subobjetivos)?

Os elementos não estão de acordo com o que é recomendado por Barbosa e Silva.<a id=anchor_1 href="#REF1"><sup>1</sup></a>
No diagrama de cancelar, os objetivos hora está uma do lado do outro hora está abaixo do outro. Além disso, o objetivo de fazer login é apresentado erroneamente.

### ID 15.2 - As tabelas apresentam os problemas e recomendações?

Não são apresentados problemas ou recomendações relativas às tarefas.

## Sugestões de Correção

Tendo em vista os problemas abordados anteriormente, fica como sugestão a realização das seguintes correções:

- Corrigir o erro ortográfico na frase apresentada;
- Criar um texto de descrição com os objetivos a serem alcançados para cada tarefa;
- Apresentar possíveis erros que os usuário possam enfrentar na realização das tarefas;
- Corrigir os diagramas HTA's com erros;
- Incluir recomendações nas tabelas dos HTA's.

A correção dos erros será realizada após uma discussão e validação dos problemas encontrados com o grupo e apresentação dos resultados para o professor da disciplina.

## Acompanhamento

A figura 1 apresenta um gráfico com o percentual de respostas sim, não, incompleto ou não se aplica, obtidas através da checklist de verificação.

<center>

**Figura 1** - Gráfico do resultado da verificação.

<iframe style="border-radius: 5px; border:3px solid red" width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQnfNsjYgFO41FTklkiZumb3OIGCMd_eIAWa-DcA9dD4GiXztP_THgdUYnWyTvA7cdPiJ2vf1TiYUbZ/pubchart?oid=263511503&amp;format=interactive"></iframe>

_Fonte: [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

## Retrabalho

Como proposto por Fagan, para o retrabalho os autores do artefato ([Arthur de Melo](https://github.com/arthurmlv), [Douglas Alves](https://github.com/dougAlvs), [Gabriel Campello](https://github.com/G16C), [Geovanna Maciel](https://github.com/manuziny) e [Matheus Henrique](https://github.com/mathonaut)) serão responsáveis em um primeiro momento por corrigir os problemas apresentados seguindo a lista de sugestão de correção apresentada anteriormente, porém há a possibilidade de outros integrantes do grupo realizarem as correções propostas. O responsável por essa verificação fará uma revisão das correções feitas, checando se as correções são suficientes e se foi introduzido novos erros ou não. A tabela 3 a seguir apresenta o cronograma de correções.

<center>

**Tabela 3** - Cronograma de Correções.

| Data de Correção | Descrição                                                                             |                 Responsável(eis)                 |                   Revisor(es)                    |      Status      |
| ---------------- | :------------------------------------------------------------------------------------ | :----------------------------------------------: | :----------------------------------------------: | :--------------: |
| 30/06/2023       | Corrigir os erros ortográficos.                                                       | [Matheus Henrique](https://github.com/mathonaut) | [Rafael Ferreira](https://github.com/RafaelCLG0) | :material-check: |
| 02/07/2023       | Criar um texto de descrição com os objetivos a serem alcançados para cada tarefa.     | [Matheus Henrique](https://github.com/mathonaut) | [Rafael Ferreira](https://github.com/RafaelCLG0) | :material-check: |
| 02/07/2023       | Apresentar possíveis erros que os usuário possam enfrentar na realização das tarefas. | [Matheus Henrique](https://github.com/mathonaut) | [Rafael Ferreira](https://github.com/RafaelCLG0) | :material-check: |
| 02/07/2023       | Corrigir os diagramas HTA's com erros.                                                | [Matheus Henrique](https://github.com/mathonaut) | [Rafael Ferreira](https://github.com/RafaelCLG0) | :material-check: |
| 02/07/2023       | Incluir recomendações nas tabelas dos HTA's.                                          | [Matheus Henrique](https://github.com/mathonaut) | [Rafael Ferreira](https://github.com/RafaelCLG0) | :material-check: |

_Fonte: Elaborado por [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> BARBOSA, S. D. J.; SILVA, B. S. **Interação Humano-Computador.** Rio de Janeiro: Elsevier, 2011.

## Bibliografia

> FERREIRA, Rafael. **Verificação do Planejamento da Avaliação da Análise de Tarefas.** Repositório do Grupo Bilheteria Digital da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <<>>. Acesso em: 18 de junho 2023.

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 19/06/2023 | Criação da página. | [Matheus Henrique](https://github.com/mathonaut) | [Rafael Ferreira](https://github.com/RafaelCLG0) |
