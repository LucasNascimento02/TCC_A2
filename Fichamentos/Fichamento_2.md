# Detecting False Alarms from Automatic Static Analysis Tools: How Far are We?

Kang, Hong Jin; Aw, Khai Loong; Lo, David. "Detecting False Alarms from Automatic Static Analysis Tools: How Far are We?", na *Proceedings of the 44th International Conference on Software Engineering (ICSE ’22)*, maio de 2022, Pittsburgh, PA, EUA. ACM. doi: [10.1145/3510003.3510214](https://dl.acm.org/doi/abs/10.1145/3510003.3510214)

---

## 1. Fichamento de Conteúdo

O artigo analisa o elevado índice de falsos positivos gerados por *Automatic Static Analysis Tools* (ASATs), como o FindBugs, que frequentemente emitem avisos irrelevantes ou não resolvidos por desenvolvedores. Estudos anteriores utilizam *machine learning* com o conjunto de chamadas “Golden Features” para filtrar os alertas acionáveis, muitas vezes apresentando resultados muito otimistas. Ao investigar mais a fundo, os autores identificam problemas graves com esses métodos, dentre eles:

- **Data leakage**: alguns *features* incluem informações do próprio rótulo (ação do desenvolvedor), comprometendo a validade do aprendizado.
- **Data duplication**: mesmos alertas aparecem em conjunto de treinamento e teste, inflando artificialmente a precisão.
- **Limitações do oracle de referência**: a heurística utilizada para definir o que é um verdadeiro bug (com base em referências futuras) pode estar enviesada ou discordar de avaliações humanas.

Essas descobertas demonstram que os resultados quase perfeitos relatados por estudos anteriores podem não refletir o desempenho real em cenários práticos e destacam a necessidade de práticas mais rigorosas na avaliação de detecção de falsos positivos em análise estática.

---

## 2. Fichamento Bibliográfico

* **Golden Features & ML para ASATs**: uso de métricas provenientes de código, histórico e padrões de avisos para predizer quais alertas são relevantes ou falsos positivos.  
* **Data Leakage**: problema onde o conjunto de treino “vaza” informações que correlacionam diretamente com o rótulo, levando a uma avaliação inflada.  
* **Data Duplication**: presença de exemplos duplicados nos conjuntos de treino e teste, prejudicando a avaliação realista de performance.  
* **Avisos como ground-truth problemático**: o uso heurístico de revisões futuras para rotular alertas pode gerar rótulos imprecisos, influenciando os resultados.  
* **Conclusão crítica**: a precisão elevada observada em métodos anteriores está superestimada devido a falhas metodológicas; recomenda-se cuidado e práticas mais robustas na construção de datasets e validação de modelos ML em ASATs.

---

## 3. Fichamento de Citações

* “Automatic static analysis tools (ASATs), such as Findbugs, have a high false alarm rate. The large number of false alarms produced poses a barrier to adoption.”
* “We found that several studies used an experimental procedure that results in data leakage and data duplication.”
* “Firstly, the ground-truth labels have leaked into features that measure the proportion of actionable warnings in a given context.” 
* “Secondly, many warnings in the testing dataset appear in the training dataset.”
* “The heuristic produces labels that do not agree with human oracles.”
