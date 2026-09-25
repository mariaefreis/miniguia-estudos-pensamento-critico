# Caderno Temático: Pensamento Crítico, Vieses Cognitivos e Inteligência Artificial

## 1. Contexto e Objetivos
**Assunto de Interesse:** A intersecção entre Pensamento Crítico, Vieses Cognitivos Humanos e o papel da Inteligência Artificial na Tomada de Decisão e Gestão de Processos

**Objetivos de Estudo:**
1. Compreender como os vieses cognitivos humanos distorcem o mapeamento de processos e projetos de consultoria.
2. Explorar como ferramentas de IA generativa podem atuar como aliadas do pensamento crítico para auditar dados, gerar cenários alternativos e apoiar o *debiasing* (desbiasamento).

## 2. Curadoria de Fontes
As fontes abaixo foram selecionadas e inseridas no NotebookLM para embasar o estudo sobre vieses cognitivos, tomada de decisão e o papel da Inteligência Artificial:

* **[Cognitive Biases Codex (PDF)](https://www.sog.unc.edu/sites/www.sog.unc.edu/files/course_materials/Cognitive%20Biases%20Codex.pdf)**
* **[Before You Make That Big Decision - Harvard Business Review](https://hbr.org/2011/06/the-big-idea-before-you-make-that-big-decision)**
* **[Artigo acadêmico sobre Gestão de Projetos e Tomada de Decisão (ScienceDirect)](https://www.sciencedirect.com/science/article/pii/S0263786325000249)** 
* **[Nature - Artigo sobre IA e Desafios Tecnológicos](https://www.nature.com/articles/d41586-026-02930-6)**
* **[APA Monitor - AI and Job Skills Thinking](https://www.apa.org/monitor/2026/07-08/ai-job-skills-thinking)**

## 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Nesta seção, documento o processo iterativo de testes de prompts realizados no NotebookLM com foco em **Pensamento Crítico**, destacando as dificuldades encontradas (cicatrizes) e como os comandos foram evoluídos para conectar o conceito teórico à realidade de projetos de consultoria e gestão de processos.

### Iteração 1: 
* **Prompt Utilizado:** 
  > *"O que é pensamento crítico?"*
* **Resposta Obtida:** A IA trouxe definições puramente acadêmicas e enciclopédicas (ex: "um método disciplinado para desconstruir situações, analisar escolhas e filtrar o excesso de informações, permitindo identificar aspectos ocultos como vieses, manipulações e premissas falhas para tomar as melhores decisões"), extraídas das fontes.
* **Dificuldade:** A resposta ficou excessivamente abstrata. Embora correta, não servia para explicar o conceito em uma reunião de alinhamento ou apresentação corporativa de processos.
* **Aprendizado:** Entendi que precisava tirar a IA do modo "dicionário" e forçá-la a contextualizar o pensamento crítico dentro de um ambiente corporativo.

### Iteração 2: 
* **Prompt Utilizado:** 
  > *"Explique como o pensamento crítico se aplica na prática de uma empresa de consultoria e como ele ajuda a combater o 'Sempre fizemos assim'."*
* **Resposta Obtida:** A IA gerou um texto rico e estruturado, explicando o impacto do Sistema 1 vs. Sistema 2, o fenômeno do WYSIATI ("What You See Is All There Is") e apresentando rituais de desviesamento como o *Pre-Mortem* e a *Visão de Fora*.
* **Dificuldade:** Embora o conteúdo estivesse impecável, a resposta gerou um material densamente teórico e conceitual. A cicatriz aqui foi perceber que o texto precisava ser traduzido em um **framework operacional direto** para poder ser aplicado nas reuniões de mapeamento de processos sem virar uma aula de psicologia.
* **Aprendizado:** O prompt seguinte precisava focar na conversão dessa teoria em uma ferramenta de execução prática para o analista de processos.

### Iteração 3:
* **Prompt Utilizado:** 
  > "Com base nas fontes de gestão (HBR) e psicologia (APA), crie um framework progressivo de 3 níveis de pensamento crítico que um analista de processos deve usar: 
  > 1. Para desconstruir o viés do cliente durante entrevistas;
  > 2. Para auditar dados operacionais usando IA generativa sem cair no viés de automação;
  > 3. Para validar o redesenho do processo (TO-BE)."
* **Resposta Obtida:** Excepcional! A IA cruzou a gestão de decisões (HBR) com a psicologia cognitiva e a teoria de IA, gerando o **Framework Progressivo de Pensamento Crítico para Analistas de Processos**, cobrindo o Diagnóstico, a Auditoria com IA e a Validação TO-BE.
