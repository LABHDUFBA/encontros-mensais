---
title: "História da Inteligência Artificial"
subtitle: "<br>Encontros Mensais — LABHDUFBA"
date: today 
date-format: full
lang: pt-br
format:
  revealjs: 
    theme: serif #[default, custom.scss]
    slide-number: true
    incremental: false
    chalkboard: 
      buttons: true
    footer: "LABHDUFBA | <a href=https://labhdufba.github.io/contact/>Entre em contato</a> "
    logo: https://raw.githubusercontent.com/ericbrasiln/hdan/refs/heads/main/imgs/LABHDUFBA.png
author:
  - name: Eric Brasil
    email: profericbrasil@gmail.com
    affiliation: UNILAB | PPGIHD/UFRRJ | LABHDUFBA
toc: false
---

## Nota sobre o uso de IA Generativa {.center}

🛠️ Esta apresentação foi **produzida com o apoio do Claude Code (modelo Sonnet 4.6)**, entre os dias **09 e 10 de abril de 2026**, a partir de instruções e curadoria do professor **Eric Brasil**.

---

## O que é Inteligência Artificial? {.columns .center}
<br>

::: {.column width="40%"}
![](https://ericbrasil.com.br/cclhm00114/aulas/assets/IA-BOT_ChatGPT_20250410_091806.png)
:::

::: {.column width="60%"}
<br>
<br>

>💬 Já discutiram o texto?

:::

---

## Alan Turing e a pergunta fundamental {.center}

> “Can machines think?” [*Computing Machinery and Intelligence* (1950)](https://doi.org/10.1093/mind/LIX.236.433)

- Essa pergunta é substituída por outra:  
  **Uma máquina pode imitar um ser humano a ponto de enganar um observador?**

- Essa proposta dá origem ao que hoje chamamos de **Teste de Turing**.

---

## Quem foi Alan Turing? {.columns .center}

::: {.column width="70%"}

- **Alan Mathison Turing** (1912–1954)  
- Matemático britânico, pioneiro na computação;
- Criou o conceito de **máquina universal** – base dos computadores;
- Atuou no projeto **Enigma**, quebrando códigos nazistas;
- Propôs o **Teste de Turing** (Jogo da Imitação, 1950);
:::

::: {.column width="30%"}
![Alan Turing aos 16 anos.](https://upload.wikimedia.org/wikipedia/commons/a/a1/Alan_Turing_Aged_16.jpg)
:::

---

## Perseguição estatal {.center}

- Em 1952, Turing foi condenado por **homossexualidade**, então considerada crime no Reino Unido;
- Foi submetido à **castração química** como pena alternativa à prisão;
- Morreu em 1954, em circunstâncias interpretadas como **suicídio**.

---

## 🏳️‍🌈 **Reconhecimento póstumo** {.columns .center}

::: {.column width="60%"}

- Em 2009, o governo britânico emitiu um pedido público de desculpas;
- Em 2013, recebeu **perdão póstumo oficial** da Rainha Elizabeth II;
- Hoje é símbolo da luta por direitos LGBTQIA+ e liberdade científica.
:::

::: {.column width="40%"}
![Estátua de Alan Turing](https://upload.wikimedia.org/wikipedia/commons/1/1a/Alan_Turing_by_Stephen_Kettle_2007.jpg)
:::

---

## Blade Runner (1982), dir. Ridley Scott {.center}

<video controls width="100%" src="https://ericbrasil.com.br/cclhm00114/aulas/assets/blade_runner_1080p.webm" crossorigin="anonymous">
</video>


---

### Her (2013), dir. Spike Jonze {.center}

<img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExMDNpbjV2cnZ2MmwydXNkZDc0ZHVtNGtrZTB4YnFxZXlwbzRvdXBqayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/unyYJeETm09laXfGui/giphy.gif" width="80%" />

> 🧠 O que significa “amar” uma IA?  
>
> Até que ponto uma consciência artificial pode ser considerada uma *pessoa*?

---

### Ex Machina (2014), dir. Alex Garland {.center}

![](https://ericbrasil.com.br/cclhm00114/aulas/assets/gif_ava.gif)

> 👁️ A IA passa no Teste de Turing — mas ela está realmente *consciente*?  
>
>  ❤️O afeto é um critério válido para reconhecer inteligência?

---

## IA Generativa ≠ IA Geral {.columns .center}

::: {.column width="49%"}
🤖 **IA Generativa (IAGen)**  

- Especializada em geração e processamento de linguagem, imagens e outros conteúdos  
- Usa padrões aprendidos em grandes volumes de dados  
- Não tem consciência nem compreensão
:::

::: {.column width="2%"}
:::
::: {.column width="49%"}
🧠 **IA Geral (AGI)**  

- Habilidade de aprender qualquer tarefa cognitiva  
- Equivalente (ou superior) à inteligência humana  
- Ainda **não foi alcançada**
:::

---

## E a Singularidade? {.center}

🌌 **Singularidade Tecnológica**  

- Futuro hipotético onde a IA supera amplamente a inteligência humana  
- Mudanças imprevisíveis e irreversíveis na sociedade

⚠️ Não é consenso entre especialistas  
⚠️ Mais presente em narrativas de ficção e futurologia

---

## {.center}

![IA Generativa, IA Geral e Singularidade - Criada pelo CHATGPT em 10/04/2025](https://ericbrasil.com.br/cclhm00114/aulas/assets/HQ_ChatGPT_20250410_103434.png)

---

## Características Gerais da IAGen {.center}

- Baseia-se em modelos avançados que identificam padrões em grandes volumes de dados.
- Aprende com dados massivos
- Produz conteúdo "original" e coerente
- Funciona com base em **probabilidades**, sem consciência
- Pode **alucinar** (gerar erros ou invenções convincentes)
- Requer **validação humana constante**

---

## O que são LLMs? {.center}

📚 **LLM** = *Large Language Model* (Modelo de Linguagem de Grande Escala)

São redes neurais treinadas com bilhões de palavras para:

- Entender e gerar linguagem natural
- Realizar tarefas complexas de texto (resumos, respostas, análises)

---

## O que são redes neurais? {.center}

🧠 Inspiradas no cérebro humano, redes neurais são estruturas matemáticas que:

- Recebem **entradas** (textos, imagens, números)
- Processam essas entradas em **camadas** de nós (neurônios artificiais)
- Aprendem a **reconhecer padrões** e gerar saídas (respostas)
- Com o tempo, ajustam seus pesos internos para melhorar os resultados.

---

## Deep Learning {.center}

- Conjunto de técnicas de **aprendizado de máquina** que usa redes neurais com **múltiplas camadas**.  
- Cada camada aprende representações mais complexas dos dados.  
- A “profundidade” se refere ao **número de camadas** de neurônios artificiais.

---

## Treinamento: como o modelo aprende? {.center}

1. O modelo **prevê uma palavra** em uma sequência.  
2. Compara com a palavra real do corpus.  
3. Calcula o **erro (diferença)** entre previsão e realidade.  
4. **Ajusta automaticamente os pesos internos** para reduzir o erro.  
5. Repete bilhões de vezes até aprender padrões estáveis.

⚙️ Esse processo iterativo é a base do **aprendizado de máquina** em redes neurais profundas.

---

## O que são os “parâmetros”? {.center}

🔢 **Parâmetros = pesos e vieses (biases)** das conexões entre neurônios.  

- Cada parâmetro define **como uma entrada influencia uma saída**.  
- Eles são **ajustados durante o treinamento** — é isso que o modelo realmente “aprende”.  

---

## O que são os “parâmetros”? {.center}

Em termos simples:

> Cada parâmetro é um **número** que representa um ajuste aprendido.  
> Quanto mais parâmetros, maior a **capacidade de representar padrões complexos**.

---

## Dimensão dos modelos {.center}

| Modelo | Ano | Parâmetros  |
|:-------|:----:|:----------:|
| GPT-2 | 2019 | 1,5 bilhão  |
| GPT-3 | 2020 | 175 bilhões |
| GPT-4 | 2023 | ≃ 1 trilhão † |
| GPT-5 | 2025 | ≃ 52,5 trilhões * |

† Estimativa não confirmada pela OpenAI.

\* Mixture-of-Experts (MoE) + Modelo unificado + Janela de contexto expandida. Estimativa não confirmada oficialmente.  

---

## Word Embeddings {.center}

**Como a máquina “entende” palavras?**

- Cada palavra é convertida em um **vetor numérico** (lista de números).  
- Palavras com sentidos semelhantes ficam **próximas no espaço vetorial**.

---

## Transformers {.center}

- Introduzidos por Vaswani et al. (2017): *“Attention is All You Need”*  
- Substituíram redes recorrentes (RNNs) por **mecanismos de atenção**.

**Atenção** = o modelo decide quais palavras anteriores são relevantes para prever a próxima palavra.

---

## Como o Transformer funciona? {.center}

Cada camada realiza três passos:

1. **Codifica** o contexto das palavras anteriores;  
2. **Aplica atenção** para focar nas partes mais relevantes;  
3. **Gera predições** ajustadas pela probabilidade.

As camadas se empilham — cada uma refina a compreensão da anterior.  

Resultado: o modelo aprende **estrutura, estilo e contexto** de linguagem.

---

## Do modelo ao diálogo {.center}

Textos => **Tokens** (pedaços de palavras) => **Probabilidades** => **Predição de palavras** => **Resposta gerada** 

- Mantém o contexto da conversa por meio de **atenção e embeddings**.
- Cada resposta é uma **nova previsão probabilística**, não uma busca em banco de dados.

---

## Como se estrutura um chatbot com IA? {.center}

- **Modelo base (LLM)**: entende e gera respostas
- **Interface (chat)**: onde ocorre a interação
- **Regras e filtros**: para segurança e adequação
- **Memória contextual**: para lembrar o que foi dito

---

## Temperatura e Criatividade {.center}

É um **parâmetro de controle de aleatoriedade** na geração de texto:

| Valor                    | Efeito                                    |
|:-------------------------|:------------------------------------------|
| 🔹 **Baixa (≈ 0.1–0.3)** | Respostas mais previsíveis e consistentes |
| 🔸 **Média (≈ 0.5–0.7)** | Equilíbrio entre coerência e criatividade |
| 🔺 **Alta (≈ 0.8–1.0+)** | Respostas criativas, mas menos estáveis   |


---

## Controle da Temperatura {.center}


| Contexto | Pode alterar? | Observação |
|:----------|:---------------|:------------|
| 💬 **Chatbots prontos** (ChatGPT, Gemini, Copilot) | ❌ Não | Valor pré-definido pelo sistema |
| 🧠 **API / código** (`temperature=`) | ✅ Sim | Controla a criatividade e variação das respostas |

---

## RAG: IA com memória de fontes {.center}

📚 **RAG** = *Retrieval-Augmented Generation* (Geração por Recuperação Aumentada)

- O modelo **busca documentos relevantes** em uma base de conhecimento antes de gerar a resposta;
- Ancora a resposta em **fontes verificáveis**, reduzindo alucinações;
- Permite trabalhar com **acervos, corpus e fontes primárias próprias** — não apenas com o que o modelo aprendeu no treinamento.

---

## RAG: IA com memória de fontes {.center}

**Exemplos na pesquisa em humanidades:**

- Perguntas sobre um corpus histórico digitalizado
- Indexação e consulta semântica de acervos documentais
- Análise de grandes conjuntos de fontes primárias

---

## Agentes de IA {.center}

🤖 **Agentes** são sistemas que combinam um LLM com **ferramentas externas** e capacidade de **encadear decisões e ações**.

- Podem executar **sequências de tarefas de forma autônoma**;
- Usam ferramentas: busca na web, execução de código, acesso a APIs, leitura e escrita de arquivos;
- Permitem construir **pipelines de pesquisa** complexos com mínima intervenção manual.

---

## Agentes de IA {.center}

**Exemplos na pesquisa em humanidades:**

- Raspagem, transcrição e análise de fontes em sequência
- Geração automatizada de metadados para acervos
- Assistentes de pesquisa que consultam bases, cruzam dados e produzem relatórios

> ⚠️ Agentes ampliam o poder da IA — e também seus riscos. Supervisão humana é indispensável.

---

## Por que pesquisadores das humanidades precisam conhecer a IA? {.center}

<br>

::: {.column width="40%"}
![](https://ericbrasil.com.br/cclhm00114/aulas/assets/IA-BOT_ChatGPT_20250410_091806.png)
:::

::: {.column width="60%"}
<br>
<br>

>💬 É só hype?

:::

