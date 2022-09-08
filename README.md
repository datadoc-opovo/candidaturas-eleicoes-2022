# ELEIÇÕES 2022 - Análise das candidaturas no Ceará

Com a campanha eleitoral de 2022, a Central de Jornalismo de Dados (DATADOC) do O POVO busca entender as características dos candidatos em diferentes aspectos, como: cor/raça, gênero e se eles se apresentam politicamente como parte de grupos religiosos.

## Notebooks com análise em Python

| Tema | Notebook | Matéria | 
| -------- | -------- | -------- |
| Indígenas     | [Link para análise de candidaturas indígenas](https://github.com/datadoc-opovo/candidaturas-eleicoes-2022/blob/main/Candidaturas_no_CE_ind%C3%ADgenas.ipynb)  | [Indígenas representaram menos de 1,2% do total de candidaturas no CE](https://mais.opovo.com.br/reportagens-especiais/2022/09/10291900-indigenas-representaram-menos-de-12-do-total-de-candidaturas-no-ce.html) |

---
## Arquivos gerados
### Indígenas

***Dataframes***

* `candidatos_ce_cor_raca_2014_2018_2022.csv`: total de candidatos por ano e cor/raça;
* `candidatos_indigenas_ce_cargo_2014_2022.csv`: candidatos autodeclarados indígenas por ano, cargo, nome e partido;
* `percentuais_cand_indigenas_uf_2022.csv`: total de candidatos, quantidade de candidatos indígenas e não indígenas e percentual de candidaturas indígenas, por UF, em 2022.
* `candidatos_ce_perc_raca_cor_2002_2022.csv`: percentual de candidaturas por raça/cor de 2002 a 2022 no Ceará;
* `df_cand_indigenas_sem_duplicacoes.csv`: base de candidatos indígenas sem duplicação de nome e ano;
* `df_candidatos_cargos_pivot.csv`: variação da quantidade de candidaturas por cargo;
* `df_candidaturas_2022_cor_raca_populacao.csv`: percentual de candidaturas indígenas por pleito.

***Visualizações***

* [Quantidade de candidatos no Ceará, por raça ou cor, nas Eleições Gerais de 2014, 2018 e 2022](https://public.flourish.studio/visualisation/10949978/);
* [Candidatos autodeclarados indígenas nas Eleições do Ceará em 2014, 2018 e 2022](https://public.flourish.studio/visualisation/10950284/);
* [Percentual de candidatos indígenas nas eleições de 2022 por UF](https://public.flourish.studio/visualisation/10950161/).

---

## Fonte e coleta de dados

* [Portal de dados abertos do Tribunal Superior Eleitoral](https://dadosabertos.tse.jus.br/)

---

**Como utilizar**

Para executar o notebook com a coleta e processamento dos dados, é necessário um ambiente com Python3 e dependências que podem ser instaladas via Pip:

```
!pip install 
!pip install 
!pip install 
```

---

**A Central DATADOC**

A Central de Jornalismo de Dados do O POVO (DATADOC) alia tecnologia e técnicas diversas de análises de dados para produzir um jornalismo de precisão para que você forme sua opinião com segurança. Nosso objetivo é fazer com que todos tenham acesso aos dados utilizados nas notícias que produzimos.

A DATADOC é composta por uma equipe de três jornalistas (sendo uma infografista), uma desenvolvedora front-end e um cientista da computação que coletam, enriquecem e disponibilizam as bases e códigos de cada reportagem para um jornalismo transparente e baseado em evidências.

---

**🔥📰👩🏻‍💻 Se você gostou do nosso material, apoie assinando o OP+ e acompanhando o nosso trabalho.**

**📝📨 Para feedback, dúvidas ou sugestões: datadoc@opovodigital.com**

---

🗓️🕵🏻 Confira também outras produções recentes da central DATADOC: A reportagem *Mortalidade materna no Ceará cresce 59% depois de três anos em queda* foi feita em parceria com o núcleo de Cotidiano do Jornal O POVO e mostrou que, entre 2015 e 2020, 507 grávidas ou puérperas morreram no Ceará. Fatores sociais, como etnia e escolaridade, influenciam indicador. A matéria está [disponível no **O POVO+**](https://mais.opovo.com.br/jornal/reportagem/2022/08/22/mortalidade-materna-no-ceara-cresce-59-depois-de-tres-anos-em-queda.html).
