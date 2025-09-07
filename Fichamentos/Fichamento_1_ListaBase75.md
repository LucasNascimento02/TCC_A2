# Can ChatGPT Repair Non-Order-Dependent Flaky Tests?

Chen, Yang; Jabbarvand, Reyhaneh. "Can ChatGPT Repair Non-Order-Dependent Flaky Tests?", in Proceedings of the IEEE/ACM International Flaky Tests Workshop (FTW ’24), April 14, 2024, Lisbon, Portugal. ACM. doi: [10.1145/3643656.3643900](https://doi.org/10.1145/3643656.3643900)

## 1. Fichamento de Conteúdo

O artigo investiga a viabilidade do uso de modelos de linguagem, especificamente o ChatGPT (GPT-4), para reparar testes flaky não dependentes de ordem (NOD). Esses testes são problemáticos porque podem passar ou falhar de forma não determinística, prejudicando a eficácia da regressão e levando ao desperdício de esforço dos desenvolvedores. Tradicionalmente, técnicas de reparo têm foco em testes order-dependent (OD) ou implementation-dependent (ID), com soluções baseadas em regras específicas de domínio. Para superar essas limitações, os autores propõem a ferramenta **NODoctor**, que utiliza GPT-4 em um ciclo iterativo com componentes de inspeção, geração de prompts, reparo e validação. Foram avaliados 118 testes NOD provenientes de 11 projetos Java. Os resultados mostraram que GPT-4 conseguiu gerar apenas 8 patches plausíveis, dos quais apenas 2 foram reparos corretos, enquanto 6 foram falsos positivos. As principais falhas observadas foram dificuldade na identificação das causas-raiz e geração de correções adequadas sem alterar a lógica original dos testes. A pesquisa conclui que, embora promissor, o uso de LLMs ainda é ineficaz para reparo generalizado de testes NOD.

## 2. Fichamento Bibliográfico

* **NOD Flaky Tests**: testes não dependentes de ordem que falham por razões diversas, como concorrência, dependência de plataforma, problemas de rede e condições de corrida (p. 22-23).
* **NODoctor**: ferramenta proposta que combina inspeção, geração de prompts, reparo e validação em um ciclo iterativo para corrigir testes NOD (p. 23).
* **Falhas do GPT-4**: principais dificuldades incluem localizar causas-raiz complexas e propor reparos corretos sem alterar a lógica do teste (p. 26-27).
* **Taxa de sucesso**: em 118 testes avaliados, apenas 2 foram reparados corretamente; 6 resultaram em falsos positivos (p. 25).
* **Falsos positivos**: patches que fazem o teste passar sem realmente corrigir a flakiness, geralmente alterando assertivas ou lógica do teste (p. 26).

## 3. Fichamento de Citações

* "Flaky tests, which can non-deterministically pass or fail on the same code version, may mislead developers’ concerns, resulting in missing some bugs or spending time pinpointing bugs that do not exist." (p. 21)
* "Our extensive evaluation of NODoctor that involved 118 NOD flaky tests from 11 real-world Java projects shows that the NODoctor can generate plausible patches for only eight tests." (p. 23)
* "Among them, six were false positives, and only two were confirmed to be a correct repair." (p. 23)
* "GPT-4 finds it challenging to identify the actual root causes of NOD tests." (p. 26)
* "To the best of our knowledge, we are the first to explore using LLM (GPT-4) for repairing NOD test flakiness." (p. 23)
