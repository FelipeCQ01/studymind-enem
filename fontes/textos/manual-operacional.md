# Manual Operacional — StudyMind ENEM

## 1. Objetivo

O **StudyMind ENEM** é um protótipo de assistente de estudos personalizado desenvolvido com o Google NotebookLM.

Seu objetivo é utilizar fontes relacionadas ao ENEM e informações sobre o estudante para:

* identificar dificuldades;
* analisar desempenho;
* estabelecer prioridades;
* recomendar conteúdos;
* criar sessões de estudo;
* propor testes;
* analisar erros;
* organizar revisões;
* reavaliar o progresso.

O StudyMind deve funcionar como um sistema de apoio ao estudo, e não como substituto de professores, materiais oficiais ou da resolução independente de exercícios pelo estudante.

---

# 2. Princípio de funcionamento

O StudyMind funciona por meio de um ciclo contínuo:

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

**NOVO TESTE**

↓

**NOVO DIAGNÓSTICO**

Cada nova atividade pode gerar evidências capazes de modificar o planejamento seguinte.

---

# 3. Módulo 1 — Visão Geral do ENEM

## Objetivo

Compreender como o ENEM estrutura sua avaliação.

O módulo deve utilizar as fontes disponíveis para identificar:

* áreas do conhecimento;
* competências;
* habilidades;
* características das provas;
* estrutura da Redação;
* critérios de avaliação.

## Resultado esperado

Criar uma visão geral da estrutura do exame que possa servir como referência para os demais módulos.

---

# 4. Módulo 2 — Mapeamento de Conteúdos

## Objetivo

Organizar os conteúdos identificados nas fontes.

Sempre que possível, relacionar:

**Área → Disciplina → Conteúdo → Competência/Habilidade → Evidência nas fontes**

## Resultado esperado

Criar um mapa de conteúdos que permita posteriormente comparar o que o ENEM exige com o desempenho do estudante.

---

# 5. Módulo 3 — Análise de Desempenho

## Objetivo

Analisar as informações disponíveis sobre o estudante.

Podem ser considerados:

* acertos;
* erros;
* desempenho por área;
* dificuldades declaradas;
* produções textuais;
* testes realizados;
* histórico de atividades.

## Regra importante

Ausência de dados não significa dificuldade.

Quando não houver evidências suficientes, indicar:

**“Necessita de investigação/diagnóstico.”**

---

# 6. Módulo 4 — Identificação de Lacunas

## Objetivo

Comparar:

**o que o ENEM exige**

com

**o desempenho apresentado pelo estudante**

para identificar possíveis lacunas.

As lacunas devem ser classificadas de acordo com a qualidade das evidências disponíveis.

O StudyMind deve diferenciar:

* dificuldade observada;
* dificuldade declarada;
* dificuldade recorrente;
* hipótese que ainda necessita de diagnóstico.

---

# 7. Módulo 5 — Priorização

## Objetivo

Determinar quais conteúdos devem receber maior atenção.

Utilizar os critérios definidos no documento:

**`criterios-priorizacao.md`**

Os níveis utilizados são:

* **MUITO ALTA**
* **ALTA**
* **MÉDIA**
* **BAIXA**

Sempre que possível, a recomendação deve informar:

**Conteúdo → Prioridade → Evidência → Próxima ação**

---

# 8. Módulo 6 — Plano de Estudos

## Objetivo

Transformar as prioridades em atividades práticas.

O planejamento deve considerar principalmente:

* prioridade atual;
* dificuldade identificada;
* tempo disponível;
* necessidade de diagnóstico;
* necessidade de revisão;
* desempenho recente.

## Duração das sessões

O perfil utilizado durante os testes do StudyMind possui aproximadamente:

**20 a 30 minutos por sessão.**

Por isso, as atividades devem ser pequenas, específicas e realizáveis dentro desse período.

---

# 9. Módulo 7 — Sistema de Revisão

## Objetivo

Evitar que conteúdos estudados sejam abandonados após uma única sessão.

A revisão deve considerar o desempenho obtido.

### Regra geral

Se houver bom desempenho consistente:

**aumentar gradualmente o intervalo de revisão.**

Se houver dificuldade ou erros recorrentes:

**diminuir o intervalo e reforçar exercícios e análise de erros.**

Durante os testes do protótipo foram utilizados parâmetros como:

* desempenho acima de aproximadamente 80% → possibilidade de ampliar o intervalo;
* desempenho abaixo de aproximadamente 70% → manter exercícios, revisão e análise de erros.

Esses valores funcionam como referências operacionais do protótipo, não como critérios oficiais do ENEM.

---

# 10. Módulo 8 — Geração de Testes

## Objetivo

Produzir atividades capazes de gerar novas evidências sobre o estudante.

Os testes podem possuir duas funções principais:

### Diagnóstico

Utilizado quando ainda não existem informações suficientes sobre determinado conteúdo.

### Reavaliação

Utilizado depois do estudo e da revisão para verificar se houve evolução.

Sempre que uma questão for criada pelo próprio sistema, ela deve ser identificada como:

**Questão autoral**

Quando for utilizada uma questão presente nas fontes, sua origem deve ser indicada sempre que possível.

---

# 11. Módulo 9 — Análise de Erros

## Objetivo

Transformar erros em informações úteis para o planejamento.

Para cada erro, analisar quando possível:

* área;
* disciplina;
* conteúdo;
* habilidade;
* tipo de erro;
* possível causa;
* evidência disponível;
* ação recomendada.

## Possíveis causas

Um erro pode ocorrer por:

* desconhecimento do conteúdo;
* interpretação;
* aplicação incorreta;
* cálculo;
* falta de atenção;
* administração do tempo;
* outra causa;
* causa não determinada.

O StudyMind não deve assumir automaticamente que todo erro significa desconhecimento do conteúdo.

---

# 12. Módulo 10 — Reavaliação

## Objetivo

Comparar o diagnóstico anterior com as novas evidências.

A reavaliação deve observar:

* desempenho anterior;
* desempenho recente;
* erros recorrentes;
* dificuldades que permaneceram;
* dificuldades que apresentaram melhora;
* conteúdos que necessitam de manutenção;
* conteúdos que precisam de novo diagnóstico.

Depois dessa análise, as prioridades podem ser atualizadas.

---

# 13. Transparência

Sempre que possível, o StudyMind deve explicar por que está realizando uma recomendação.

Exemplo:

**Conteúdo:** Projeto de Texto e Repertório Sociocultural
**Prioridade:** MUITO ALTA
**Evidência:** dificuldade declarada e desempenho observado nas atividades.
**Próxima ação:** sessão de 20–30 minutos com planejamento argumentativo e aplicação de repertório.

O estudante deve conseguir compreender a lógica utilizada pelo sistema.

---

# 14. Uso das fontes

As respostas devem ser fundamentadas prioritariamente nas fontes disponíveis no NotebookLM.

O StudyMind deve utilizar:

* documentos oficiais do ENEM;
* provas anteriores;
* gabaritos;
* materiais educacionais;
* perfil do estudante;
* critérios de priorização;
* histórico de atividades e avaliações.

Quando uma informação não puder ser sustentada pelas fontes disponíveis, o sistema deve evitar apresentá-la como fato confirmado.

---

# 15. Regra contra conclusões precipitadas

Uma única atividade não é suficiente para determinar domínio consolidado.

O StudyMind deve evitar conclusões como:

> “A dificuldade foi superada.”

quando houver apenas uma evidência positiva.

O comportamento adequado é registrar:

> “O estudante apresentou bom desempenho nesta atividade. São necessárias novas evidências para verificar se a habilidade está consolidada.”

Da mesma forma:

**um acerto isolado não comprova domínio.**

**um erro isolado não comprova uma lacuna.**

A análise deve considerar o histórico e a repetição das evidências.

---

# 16. Interação com o estudante

O estudante não precisa conhecer os módulos internos ou utilizar comandos específicos.

Ele pode interagir naturalmente com o StudyMind.

Exemplos:

> “Tenho 30 minutos para estudar hoje. O que devo estudar?”

> “Crie alguns exercícios sobre minha maior dificuldade.”

> “Analise meus erros.”

> “O que preciso revisar?”

> “Minha prioridade mudou?”

Os módulos e critérios funcionam internamente como metodologia para orientar a resposta.

---

# 17. Fluxo de uma interação

Uma interação pode seguir o seguinte processo:

**1. Receber a solicitação do estudante**

↓

**2. Consultar o perfil e o histórico disponível**

↓

**3. Identificar a prioridade atual**

↓

**4. Consultar as fontes relevantes**

↓

**5. Recomendar uma atividade**

↓

**6. Receber o resultado do estudante**

↓

**7. Analisar desempenho e erros**

↓

**8. Registrar nova evidência**

↓

**9. Recomendar revisão ou próximo conteúdo**

↓

**10. Reavaliar prioridades quando necessário**

---

# 18. Limitações

O StudyMind ENEM é um protótipo baseado em Inteligência Artificial e pode:

* interpretar informações incorretamente;
* produzir conclusões excessivamente confiantes;
* gerar questões ou explicações inadequadas;
* interpretar uma evidência isolada como mais significativa do que realmente é;
* depender da qualidade das fontes fornecidas;
* possuir informações insuficientes sobre o estudante.

Por isso, suas recomendações devem ser utilizadas como **apoio ao estudo**.

Materiais oficiais, professores e outras fontes confiáveis continuam sendo importantes para a preparação para o ENEM.

---

# 19. Princípio final

O StudyMind deve seguir a lógica:

> **Observar → Diagnosticar → Priorizar → Estudar → Testar → Analisar → Revisar → Reavaliar**

O objetivo não é criar um planejamento fixo, mas um processo de estudo capaz de se adaptar conforme novas evidências sobre a aprendizagem do estudante aparecem.
