
# Do Prompt Patterns Affect Code Quality? A First Empirical Assessment of ChatGPT-Generated Code

Della Porta, Antonio; Lambiase, Stefano; Palomba, Fabio. "Do Prompt Patterns Affect Code Quality? A First Empirical Assessment of ChatGPT-Generated Code", in Proceedings of EASE 2025 (29th International Conference on Evaluation and Assessment in Software Engineering), 17–20 June 2025, Istanbul, Türkiye. doi: [10.48550/arXiv.2504.13656](https://doi.org/10.48550/arXiv.2504.13656)

---

## 1. Fichamento de Conteúdo  
Este estudo investiga empiricamente o impacto de *prompt patterns* na qualidade do código gerado via ChatGPT, com foco nos atributos de manutenção, segurança e confiabilidade. Utilizando o conjunto de dados *DevGPT* (7.583 arquivos de código gerado), os autores identificaram padrões como Zero-Shot, Zero-Shot com Chain-of-Thought e Few-Shot. Aplicando métricas de qualidade via SonarQube e testes estatísticos (Kruskal-Wallis), concluem que não houve diferenças significativas entre os padrões em relação aos atributos analisados, sugerindo que o tipo de estrutura de prompt pode não afetar substancialmente a qualidade do código gerado. É oferecida uma versão refinada do DevGPT com metadados sobre padrões de prompt e métricas de qualidade.

---

## 2. Fichamento Bibliográfico  
- **Prompt Patterns Avaliados**: Zero-Shot, Zero-Shot + Chain-of-Thought, Few-Shot.  
- **Métricas de Qualidade**: Manutenibilidade, segurança e confiabilidade, obtidas via SonarQube.  
- **Método Estatístico**: Testes de Kruskal-Wallis demonstraram ausência de diferenças estatisticamente significativas entre padrões de prompt.  
- **Contribuições**:
  - Empírica: análise de 7.583 códigos gerados com base em DevGPT.  
  - Dataset refinado do DevGPT com metadados prontos para reuso.  
  - Evidência de que formato de prompt pode não reverberar na qualidade do código gerado.

---

## 3. Fichamento de Citações  
- “Zero-Shot prompting is most common, followed by Zero-Shot with Chain-of-Thought and Few-Shot.”
- “Analysis of 7583 code files across quality metrics revealed minimal issues, with Kruskal-Wallis tests indicating no significant differences among patterns...”
- “Prompt structure may not substantially impact these quality metrics in ChatGPT-assisted code generation.”
