# Segundo Cérebro: Engenharia de Prompts e Agentes de IA

## 🎯 Tema e Objetivo
> "Centralizar documentações técnicas, artigos de pesquisa, padrões de arquitetura (como ReAct e Chain-of-Thought) e tutoriais práticos em vídeo e texto para projetar, depurar e executar automações inteligentes integradas a scripts em Python."

---

## 📚 Fontes Utilizadas e Critérios de Confiabilidade

Selecionamos um núcleo enxuto e rigoroso de fontes técnicas para evitar ruídos e garantir alta precisão de engenharia:

1. **Prompt Engineering Guide (DAIR.AI)**
   - *Link:* [https://www.promptingguide.ai/](https://www.promptingguide.ai/)
   - *Por que confiamos:* É o guia aberto mais respeitado e atualizado da comunidade de IA para estudo de padrões lógicos (*Chain-of-Thought*, *Few-shot*, *ReAct*).
2. **OpenAI Cookbook (Repositório Oficial)**
   - *Link:* [https://github.com/openai/openai-cookbook](https://github.com/openai/openai-cookbook)
   - *Por que confiamos:* Traz código funcional em Python e diretrizes arquiteturais oficiais direto dos criadores dos modelos líderes de mercado.
3. **Anthropic Prompt Engineering Interactive Tutorial**
   - *Link:* [https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
   - *Por que confiamos:* Documentação oficial de nível avançado focada em controle rigoroso de contexto e engenharia de *System Prompts*.
4. **Masterclasses Técnicas (YouTube)**
   - *Fontes:* Conteúdos fundamentais de arquitetura de redes neurais, loops de raciocínio de agentes (*LangChain & Autonomous Agents*) e engenharia aplicada de grandes especialistas da área.

---

## 🤖 Diretriz de Comportamento (System Prompt)

Para guiar o assistente do Gemini Notebook, configuramos a seguinte diretriz de especialista:

> *"Comporte-se como um engenheiro especialista em IA e arquiteto de sistemas de linguagem. Suas respostas devem ser estritamente técnicas, baseadas em código (Python), focadas em padrões de projeto de agentes (como ReAct e Chain-of-Thought) e livres de generalizações superficiais."*

---

## 💬 Interações, Respostas e Citações

Abaixo estão exemplos práticos de consultas realizadas no chat do notebook, cruzando as fontes:

* **Pergunta 1:** *"Qual é a estrutura ideal de um System Prompt para garantir que um agente de IA execute chamadas de ferramentas (*tools*) em Python sem alucinar parâmetros?"*
  - **Resposta do Notebook:** O modelo indicou o uso de restrições estritas de formatação (como JSON Schema forçado), delimitação clara de contexto e loops de validação baseados nas diretrizes do *OpenAI Cookbook* e nas boas práticas de estruturação de system prompts da *Anthropic*.
  - **Fontes Citadas:** *OpenAI Cookbook* e *Anthropic Prompt Engineering Tutorial*.

* **Pergunta 2:** *"Como o framework ReAct melhora a capacidade de raciocínio comparado a prompts lineares simples?"*
  - **Resposta do Notebook:** Explicou a alternância sistemática entre blocos de Pensamento (*Thought*), Ação (*Action*) e Observação (*Observation*), permitindo que o modelo corrija o rumo da execução antes de gerar a resposta final ao usuário.
  - **Fontes Citadas:** *Prompt Engineering Guide (DAIR.AI)*.

---

## 🔗 Link do Notebook Compartilhado
* Acesse o ambiente interativo do segundo cérebro no Gemini Notebook: https://notebook.google.com/notebook/715a47cd-95b4-41d8-9b68-7704e9e4fb74
