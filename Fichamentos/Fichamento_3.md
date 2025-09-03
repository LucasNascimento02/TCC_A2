# Model-Driven Prompt Engineering

*Clarisó, Robert; Cabot, Jordi.* Model-Driven Prompt Engineering. In: Proceedings of the ACM/IEEE 26th International Conference on Model-Driven Engineering Languages and Systems (MODELS ’23), 2023 ([modeling-languages.com](https://modeling-languages.com/wp-content/uploads/2023/08/model-driven-prompt-engineering.pdf?utm_source=chatgpt.com)).

---

## 1. Fichamento de Conteúdo

O artigo apresenta uma abordagem inovadora que aplica os princípios da *engenharia dirigida por modelo (MDE)* ao campo emergente da *prompt engineering*, que consiste no processo de elaboração de instruções em linguagem natural para sistemas de IA generativa. 
Reconhecendo que boas práticas de prompts variam conforme a plataforma e até versões do sistema, os autores propõem a criação de uma linguagem específica de domínio (DSL) chamada *Impromptu*, que permite a definição de *prompts* independentes de plataforma. 
Essa DSL facilita a modularização, versionamento e encadeamento de *prompts*, possibilitando sua adaptação automática para plataformas específicas como *Midjourney*, *Stable Diffusion* ou outros sistemas de geração de texto e imagem. 
A solução inclui suporte via um plugin para *Visual Studio Code* (baseado em Langium), oferecendo também geração de código para execução dos prompts e mecanismos de gestão da qualidade dos resultados gerados.

---

## 2. Fichamento Bibliográfico

* *Prompt Engineering & MDE*: aplicação dos conceitos de engenharia dirigida por modelo para facilitar a criação, portabilidade e manutenção de prompts em IA generativa.  
* *Impromptu DSL*: linguagem específica de domínio para definir prompts de forma modular, multimodal e independente da plataforma alvo.  
* *Suporte automatizado*: geração de prompts específicos para diferentes sistemas, manipulação de versões, e validação de qualidade de saída com infraestrutura baseada em plugin.  
* *Desafios de portabilidade*: prompts que funcionam bem em uma plataforma podem falhar em outras ou em versões diferentes do mesmo sistema.  
* *Gestão de conhecimento*: funcionalidades para documentar, rastrear, encadear e traduzir prompts para múltiplas linguagens ou sistemas.  

---

## 3. Fichamento de Citações

* “Using a domain-specific language (DSL), we define platform-independent prompts that can later be adapted to provide good quality outputs in a target AI system.”  
* “Prompt engineering … is essentially a platform-specific process. Prompts that perform well in a particular system may under-perform in other systems.”  
* “The DSL also facilitates managing prompts by providing mechanisms for prompt versioning and prompt chaining.”  
* “Impromptu offers a domain-specific language (DSL) to define multimodal prompts in a modular and tool-independent way. The language offers additional features such as versioning, prompt chaining and multi-language support.”
