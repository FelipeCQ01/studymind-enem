# Prompts Principais — StudyMind ENEM

Este arquivo documenta os principais prompts utilizados durante o desenvolvimento do **StudyMind ENEM** no Google NotebookLM.

Os prompts foram organizados em módulos responsáveis por analisar o ENEM, compreender o desempenho do estudante, identificar prioridades e construir um ciclo personalizado de estudo e reavaliação.

> **Observação:** no histórico registrado do projeto, alguns módulos aparecem executados de forma conjunta. Por esse motivo, os Prompts 04 e 05, 06 e 07, e 08 e 09 são apresentados agrupados neste documento, preservando o registro original.

---

## Prompt 01 — Visão Geral do ENEM

**Módulo:** Análise estrutural e matrizes

> Você é o módulo de análise do StudyMind ENEM. Sua tarefa é analisar as fontes para identificar como o ENEM estrutura sua avaliação (divisão por áreas, competências, características 2023–2025, redação, etc.).

### Finalidade

Realizar uma análise geral da estrutura do ENEM a partir das fontes adicionadas ao NotebookLM.

---

## Prompt 02 — Mapeamento de Conteúdos

**Módulo:** Mapeamento de conteúdos por área

> Você é o módulo de MAPEAMENTO DE CONTEÚDOS do StudyMind ENEM. Organize os conteúdos por área e disciplinas, relacionando competências, habilidades e anos observados.

### Finalidade

Organizar os conteúdos encontrados nas fontes por área e disciplina, relacionando-os às competências, habilidades e provas analisadas.

---

## Prompt 03 — Análise de Desempenho

**Módulo:** Análise de desempenho do estudante

> Você é o módulo de ANÁLISE DE DESEMPENHO. Analise os dados do estudante (perfil, acertos, erros, lacunas).

### Finalidade

Analisar as informações disponíveis sobre o estudante e identificar possíveis dificuldades, lacunas e pontos que ainda precisam de investigação.

---

## Prompts 04 e 05 — Lacunas e Critérios de Priorização

**Módulos:** Identificação de lacunas e priorização dos estudos

> Determine quais conteúdos devem receber maior atenção nos estudos com base nos Critérios de Priorização do StudyMind ENEM.

### Finalidade

Cruzar as necessidades identificadas no desempenho do estudante com os critérios de priorização do projeto.

A partir dessa análise, os conteúdos podem receber diferentes níveis de prioridade, como:

* MUITO ALTA;
* ALTA;
* MÉDIA;
* BAIXA.

Algumas prioridades também podem permanecer provisórias quando ainda não existem evidências suficientes sobre o desempenho do estudante.

---

## Prompts 06 e 07 — Plano de Estudos e Revisão

**Módulos:** Planejamento e sistema de revisão

> Crie um plano de estudos personalizado (sessões de 20-30 min) e um sistema de revisão contínuo.

### Finalidade

Transformar as prioridades identificadas anteriormente em sessões de estudo compatíveis com o tempo disponível do estudante e estabelecer um processo contínuo de revisão.

O ciclo utilizado pelo projeto é:

**ESTUDO → REVISÃO → EXERCÍCIOS → ANÁLISE DOS ERROS → NOVA REVISÃO → NOVO TESTE**

---

## Prompts 08 e 09 — Testes e Análise de Erros

**Módulos:** Testes personalizados e análise inteligente dos erros

> Crie um sistema de geração de testes personalizados (Diagnóstico e Reavaliação) e uma estrutura para análise de erros.

### Finalidade

Produzir atividades capazes de gerar novas evidências sobre o desempenho do estudante.

Os resultados podem ser analisados considerando aspectos como:

* área e disciplina;
* conteúdo;
* causa provável do erro;
* ação pedagógica recomendada.

Essa etapa permite que os erros sejam utilizados como informações para orientar os próximos estudos.

---

## Prompt 10 — Reavaliação Completa

**Módulo:** Reavaliação do estudante

> Realize uma reavaliação completa do estudante confrontando o histórico com as novas evidências dos testes.

### Finalidade

Comparar o diagnóstico inicial com as novas evidências produzidas durante os estudos.

A reavaliação permite verificar:

* possíveis evoluções;
* dificuldades que permanecem;
* novas lacunas;
* conteúdos que precisam continuar sendo estudados;
* prioridades que precisam ser atualizadas.

---

# Fluxo dos Prompts

Os módulos foram organizados para formar o seguinte fluxo:

**1. Visão Geral do ENEM**
↓
**2. Mapeamento de Conteúdos**
↓
**3. Análise de Desempenho**
↓
**4. Identificação de Lacunas**
↓
**5. Priorização**
↓
**6. Plano de Estudos**
↓
**7. Sistema de Revisão**
↓
**8. Testes Personalizados**
↓
**9. Análise de Erros**
↓
**10. Reavaliação**

Após a reavaliação, novas evidências podem alimentar novamente o processo, formando um ciclo contínuo de aprendizagem.

---

## Observação sobre a evolução do projeto

Após a execução dos módulos principais, o StudyMind ENEM também foi utilizado em sessões práticas de estudo, especialmente em **Redação**, com atividades relacionadas às Competências II e III, Projeto de Texto e Repertório Produtivo.

Esses testes posteriores são documentados separadamente, pois fazem parte da etapa de experimentação e validação do protótipo, e não dos dez módulos principais apresentados neste arquivo.
