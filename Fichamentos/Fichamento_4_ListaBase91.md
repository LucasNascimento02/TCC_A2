# Using Large Language Models to Generate Concise and Understandable Test Case Summaries
 
Djajadi, Natanael; Deljouyi, Amirhossein; Zaidman, Andy. "Using Large Language Models to Generate Concise and Understandable Test Case Summaries", in Proceedings of the 33rd IEEE/ACM International Conference on Program Comprehension (ICPC ’25), 2025, pp. 322–326.

---

## 1. Fichamento de Conteúdo

Este artigo avalia empiricamente a capacidade de modelos de linguagem (LLMs) em sintetizar resumos de casos de teste que sejam ao mesmo tempo concisos e claros. Em um estudo de usuário com participantes que possuem experiência em Java, os autores compararam resumos gerados por LLMs—como GPT-3.5, GPT-4 e CodeLlama (7B)—com abordagens baseadas em templates, como TestDescriber e DeepTC-Enhancer. A avaliação abrangeu critérios como completude, correção, concisão e naturalidade. Os resultados indicam que resumos guiados por prompting (técnicas como few-shot, persona e chain-of-thought) são percebidos como mais naturais e igualmente informativos, apontando o potencial de LLMs para melhorar a compreensão de casos de teste

---

## 2. Fichamento Bibliográfico

* **Prompting na Sumarização de Testes**: técnicas exploradas incluem few-shot, uso de persona, action words e chain-of-thought. 
* **Modelos Avaliados**: GPT-3.5, GPT-4 e CodeLlama 7B.  
* **Estudo com Desenvolvedores**: avaliação qualitativa feita por 11 desenvolvedores com experiência em Java. 
* **Critérios de Avaliação**: completude, correção, concisão e naturalidade—pontuados com escala Likert. 
* **Conclusão**: prompting com contexto e estilo funcional potencializa resumos que são bem recebidos em termos de qualidade e legibilidade.

---

## 3. Fichamento de Citações

* “RQ1 What is the impact of using different prompt techniques to generate LLM-based test summaries?” 
* “We perform a user study to compare LLM-generated test summaries with those from existing tools by looking at the content (completeness and correctness), conciseness (no irrelevant information), and naturalness of the language.”  
* “Prompt engineering is important given that each LLM has its favoured input structures. As such, we use action words, adopt a persona, and employ Chain of Thought.”
