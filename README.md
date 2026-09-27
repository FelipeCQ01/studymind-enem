# StudyMind ENEM

## Sobre o projeto

O **StudyMind ENEM** é um protótipo de assistente de estudos personalizado desenvolvido utilizando o **Google NotebookLM**.

O projeto explora o uso de **Inteligência Artificial e Engenharia de Prompts** para auxiliar estudantes na preparação para o ENEM, utilizando fontes oficiais, materiais de estudo e informações sobre o desempenho do estudante.

A proposta é transformar essas informações em um ciclo de estudo capaz de identificar necessidades, estabelecer prioridades e adaptar as próximas atividades conforme novas evidências são obtidas.

---

## Objetivo

Criar um fluxo de estudos capaz de:

* analisar dificuldades do estudante;
* identificar possíveis lacunas de aprendizagem;
* determinar conteúdos prioritários;
* criar sessões de estudo;
* gerar atividades e exercícios;
* analisar erros;
* recomendar revisões;
* acompanhar novas evidências de aprendizagem;
* reavaliar prioridades.

---

## Problema identificado

A preparação para o ENEM envolve uma grande quantidade de conteúdos, competências e habilidades.

Nesse cenário, o estudante pode encontrar dificuldades para responder perguntas como:

* O que devo estudar primeiro?
* Em quais conteúdos tenho mais dificuldade?
* Quanto tempo devo dedicar a cada assunto?
* O que preciso revisar?
* Meus erros estão relacionados ao conteúdo ou à interpretação?
* Minha dificuldade realmente foi superada?

O StudyMind foi desenvolvido para experimentar uma abordagem em que essas decisões sejam orientadas por **fontes selecionadas e evidências do desempenho do estudante**.

---

## Como funciona

O StudyMind utiliza um ciclo contínuo:

**DIAGNÓSTICO**

↓

**PLANEJAMENTO**

↓

**ESTUDO**

↓

**TESTE**

↓

**ANÁLISE DOS ERROS**

↓

**REVISÃO**

↓

**REAVALIAÇÃO**

↓

**NOVO DIAGNÓSTICO**

As novas evidências produzidas durante os estudos podem modificar as prioridades e recomendações seguintes.

---

## Fontes utilizadas

O projeto utiliza diferentes tipos de fontes no Google NotebookLM.

### Fontes oficiais e materiais de estudo

* Matriz de Referência do ENEM;
* Cartilhas do Participante — Redação;
* provas anteriores do ENEM;
* gabaritos oficiais;
* materiais educacionais oficiais do INEP.

### Fontes próprias do StudyMind

Também foram criados documentos para fornecer contexto ao protótipo:

* Perfil e Desempenho do Estudante;
* Critérios de Priorização;
* Manual Operacional do StudyMind.

A documentação completa está disponível em:

**[Fontes utilizadas](fontes/fontes-utilizadas.md)**

Os principais PDFs utilizados também estão disponíveis em:

**[Fontes em PDF](fontes/pdfs/)**

---

## Engenharia de Prompts

Foi desenvolvida uma cadeia de prompts organizada em dez módulos:

1. Visão Geral do ENEM;
2. Mapeamento de Conteúdos;
3. Análise de Desempenho;
4. Identificação de Lacunas;
5. Priorização;
6. Plano de Estudos;
7. Sistema de Revisão;
8. Testes Personalizados;
9. Análise de Erros;
10. Reavaliação.

A cadeia permite que os resultados de uma etapa sirvam como contexto para as etapas seguintes.

Os prompts utilizados estão documentados em:

**[Prompts principais](prompts/prompts-principais.md)**

---

## Testes realizados

O protótipo foi testado em situações como:

* identificação de prioridades;
* geração de sessões de 20–30 minutos;
* atividades de Redação;
* construção de tese;
* utilização de repertório sociocultural;
* planejamento argumentativo;
* análise de respostas;
* estruturação da análise de erros;
* reavaliação do estudante.

Um dos principais testes ocorreu na área de **Redação**, inicialmente identificada como prioridade muito alta.

O StudyMind transformou essa prioridade em atividades relacionadas principalmente ao **Projeto de Texto, desenvolvimento argumentativo, repertório sociocultural e Competências II e III**.

---

## Cicatrizes e aprendizados

Durante os testes também foram identificadas limitações importantes.

Em determinado momento, após uma boa produção de um parágrafo de Redação, o sistema interpretou o resultado como evidência de que uma fragilidade inicial havia sido superada.

Essa conclusão foi considerada forte demais para a quantidade de evidências disponíveis.

A partir desse teste foi reforçado um princípio importante:

> **Bom desempenho pontual não significa domínio consolidado.**

Da mesma forma:

> **Um erro isolado não significa necessariamente uma lacuna de aprendizagem.**

O protótipo passou a considerar a necessidade de novas atividades, testes, revisão e comparação entre resultados antes de alterar significativamente o diagnóstico do estudante.

Os testes e aprendizados estão documentados em:

**[Testes e Cicatrizes](prompts/testes-e-cicatrizes.md)**

---

## Miniguia de estudo

Como parte da documentação final, foi desenvolvido um miniguia contendo:

* resumo dos principais conceitos trabalhados;
* organização do ciclo de aprendizagem;
* conceitos relacionados à Redação;
* diagnóstico e priorização;
* análise de erros;
* glossário;
* prompts reutilizáveis para futuras sessões.

Acesse em:

**[Miniguia StudyMind ENEM](miniguia/studymind-enem.md)**

---

## Estrutura do repositório

```text
studymind-enem/
│
├── README.md
│
├── fontes/
│   ├── fontes-utilizadas.md
│   ├── pdfs/
│   │   ├── README.md
│   │   └── [fontes oficiais em PDF]
│   └── textos/
│       ├── perfil-desempenho-estudante.md
│       ├── criterios-priorizacao.md
│       └── manual-operacional.md
│
├── prompts/
│   ├── prompts-principais.md
│   └── testes-e-cicatrizes.md
│
└── miniguia/
    └── studymind-enem.md
```

---

## Tecnologias e ferramentas

* **Google NotebookLM**
* **Engenharia de Prompts**
* **Inteligência Artificial**
* **Markdown**
* **GitHub**

---

## Limitações

O StudyMind ENEM é um **protótipo experimental**.

As respostas produzidas por Inteligência Artificial podem apresentar interpretações incorretas ou conclusões excessivamente confiantes.

Além disso, a qualidade das recomendações depende diretamente:

* das fontes adicionadas;
* da quantidade de informações disponíveis sobre o estudante;
* da qualidade das evidências de desempenho;
* da forma como os resultados são interpretados.

Por isso, o StudyMind deve ser utilizado como **apoio ao processo de aprendizagem**, e não como substituto de professores, materiais oficiais ou outras fontes confiáveis.

---

## Resultado

O desenvolvimento resultou em um protótipo no Google NotebookLM capaz de utilizar:

**FONTES DO ENEM + MATERIAIS DE ESTUDO + DADOS DO ESTUDANTE**

para apoiar um processo de:

**DIAGNÓSTICO → PRIORIZAÇÃO → ESTUDO → TESTE → ANÁLISE → REVISÃO → REAVALIAÇÃO**

O principal resultado do projeto não é apenas um cronograma de estudos, mas uma metodologia capaz de adaptar as próximas recomendações conforme novas evidências sobre o desempenho do estudante são produzidas.
