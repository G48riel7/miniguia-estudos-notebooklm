# miniguia-estudos-notebooklm
# 🤖 Miniguia de Estudos: Inteligência Artificial & Machine Learning
### Caderno Temático criado com auxílio do NotebookLM | Projeto DIO

---

## 📌 Contexto e Objetivos

### Por que este tema?

A Inteligência Artificial e o Machine Learning estão transformando todas as áreas da sociedade — da medicina à agricultura, do entretenimento às finanças. Para profissionais de tecnologia, entender os fundamentos dessas tecnologias deixou de ser um diferencial e tornou-se uma **necessidade**.

Este caderno temático foi criado como parte de um desafio prático da **DIO (Digital Innovation One)**, com o objetivo de usar o **NotebookLM** como ferramenta de aprendizagem ativa para organizar, sintetizar e fixar conhecimentos sobre IA e ML.

### Objetivos de Estudo

- [ ] Compreender o que é Inteligência Artificial e como ela se diferencia do Machine Learning
- [ ] Conhecer os principais tipos de aprendizado de máquina (supervisionado, não-supervisionado e por reforço)
- [ ] Entender como funcionam algoritmos clássicos (regressão, árvores de decisão, redes neurais)
- [ ] Identificar casos de uso reais de IA/ML no mercado
- [ ] Dominar o vocabulário essencial da área para comunicação técnica
- [ ] Criar uma base sólida para evoluir para estudos mais avançados

---

## 📚 Curadoria de Fontes

As fontes abaixo foram selecionadas por serem **abertas, confiáveis e acessíveis para iniciantes**. Todas foram inseridas no NotebookLM para análise e síntese.

| # | Fonte | Tipo | Link | Por que escolhi? |
|---|-------|------|------|-----------------|
| 1 | **Machine Learning - Guia de Introdução (Google Developers)** | Documentação / Web | [🔗 Acessar](https://developers.google.com/machine-learning/crash-course) | Curso gratuito e didático do Google, cobrindo fundamentos com exemplos práticos |
| 2 | **Artificial Intelligence: A Modern Approach (capítulos introdutórios)** | PDF | [🔗 Acessar](https://people.engr.tamu.edu/guni/csce421/files/AI_Russell_Norvig.pdf) | Principal referência acadêmica da área, com linguagem acessível nos capítulos iniciais |
| 3 | **An Introduction to Machine Learning - Springer (Open Access)** | PDF | [🔗 Acessar](https://link.springer.com/book/10.1007/978-3-319-63913-0) | Livro acadêmico de acesso aberto com base matemática bem explicada |
| 4 | **Elements of AI (Universidade de Helsinki)** | Curso / Web | [🔗 Acessar](https://www.elementsofai.com/br) | Curso gratuito em português, desenvolvido para leigos e iniciantes |
| 5 | **A Brief Introduction to Machine Learning for Engineers (arXiv)** | PDF | [🔗 Acessar](https://arxiv.org/abs/1709.02840) | Paper introdutório excelente, disponível gratuitamente no arXiv |

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

Esta seção documenta o processo de elaboração de perguntas estratégicas no NotebookLM — incluindo os acertos, os ajustes e as lições aprendidas.

---

### 🔵 Rodada 1 — Prompts Iniciais (Diagnóstico)

**Objetivo:** Entender o escopo do material e mapear os conceitos principais.

#### Prompt 1.1
```
"Quais são os conceitos mais importantes presentes nessas fontes que um iniciante em IA precisa entender primeiro?"
```
**Resposta obtida:** O NotebookLM listou conceitos como: dados de treinamento, modelo, feature, label, overfitting, underfitting, algoritmos supervisionados vs. não-supervisionados.

**✅ O que funcionou:** A pergunta aberta foi ótima para mapear o terreno.

**⚠️ Dificuldade encontrada:** A resposta foi muito extensa e pouco organizada — difícil de usar como resumo.

**🔧 Ajuste feito:** Refinei o prompt para pedir uma estrutura específica (ver 1.2).

---

#### Prompt 1.2 (versão refinada)
```
"Liste os 10 conceitos mais importantes para iniciantes em IA/ML presentes nas fontes, em ordem crescente de complexidade. Para cada conceito, escreva uma definição em até 2 linhas."
```
**Resposta obtida:** Lista organizada e progressiva, muito mais utilizável.

**✅ Lição aprendida:** Especificar o **formato de saída** (lista, ordem, limite de linhas) melhora drasticamente a qualidade da resposta.

---

### 🟡 Rodada 2 — Prompts de Aprofundamento

**Objetivo:** Entender as diferenças entre os tipos de aprendizado de máquina.

#### Prompt 2.1
```
"Explica a diferença entre aprendizado supervisionado, não-supervisionado e por reforço com exemplos do dia a dia."
```
**Resposta obtida:** Explicação clara com analogias. Exemplo usado: filtro de spam (supervisionado), agrupamento de clientes (não-supervisionado) e videogames de IA (reforço).

**✅ O que funcionou:** Pedir "exemplos do dia a dia" tornou o conteúdo muito mais acessível.

---

#### Prompt 2.2
```
"Cria uma tabela comparativa entre os três tipos de aprendizado de máquina: supervisionado, não-supervisionado e por reforço. Inclua: definição, quando usar, exemplo prático e algoritmo mais comum."
```
**Resposta obtida:** Tabela clara e reutilizável para revisões rápidas.

**✅ Lição aprendida:** Pedir **tabelas comparativas** é excelente para fixar diferenças entre conceitos similares.

---

### 🔴 Rodada 3 — Prompts de Troubleshooting (Dificuldades Encontradas)

#### Problema 1: Respostas genéricas demais
**Prompt que causou o problema:**
```
"Me explica Machine Learning."
```
**Problema:** Resposta muito genérica, sem ancoragem nas fontes.

**Solução:** Sempre referenciar as fontes explicitamente:
```
"Com base nas fontes carregadas, especialmente no material do Google Developers e do Elements of AI, explica Machine Learning para alguém que nunca teve contato com programação."
```

---

#### Problema 2: Alucinação de informações
**Situação:** O NotebookLM mencionou um "Capítulo 7 do livro X" que não existia na fonte enviada.

**Solução:** Aprendi a sempre pedir que a IA **cite a fonte e o trecho** ao fazer afirmações:
```
"Ao responder, sempre indique de qual das fontes carregadas a informação foi extraída."
```

---

#### Problema 3: Respostas longas demais
**Solução:** Usar limitadores no prompt:
```
"Responda em no máximo 150 palavras" ou "Faça um resumo de 5 pontos principais"
```

---

## 📖 Miniguia de Estudo — Entrega Final

---

### 🗂️ 1. Resumos Estruturados

#### O que é Inteligência Artificial?

A **Inteligência Artificial (IA)** é um campo da ciência da computação que busca criar sistemas capazes de realizar tarefas que, se executadas por humanos, exigiriam inteligência — como reconhecer imagens, entender linguagem natural, tomar decisões e aprender com experiências.

A IA pode ser dividida em:
- **IA Estreita (Narrow AI):** focada em uma tarefa específica (ex: reconhecimento facial, recomendação de filmes)
- **IA Geral (AGI):** hipotética, capaz de realizar qualquer tarefa cognitiva humana
- **Super IA:** conceito teórico de IA que supera a inteligência humana em todos os aspectos

---

#### O que é Machine Learning?

**Machine Learning (ML)** é um subcampo da IA onde os sistemas **aprendem a partir de dados** — em vez de serem programados com regras fixas, eles identificam padrões nos dados e melhoram sua performance com a experiência.

```
IA ⊃ Machine Learning ⊃ Deep Learning
```

**Os 3 tipos principais de aprendizado:**

| Tipo | Como funciona | Exemplo prático |
|------|--------------|----------------|
| **Supervisionado** | Aprende com dados rotulados (input + output esperado) | Filtro de spam, detecção de fraude |
| **Não-supervisionado** | Encontra padrões em dados sem rótulos | Segmentação de clientes, compressão de dados |
| **Por reforço** | Aprende por tentativa e erro com recompensas | IA que joga xadrez, robótica |

---

#### Pipeline Básico de um Projeto de ML

```
1. Definir o problema
       ↓
2. Coletar e limpar os dados
       ↓
3. Escolher e treinar o modelo
       ↓
4. Avaliar o desempenho
       ↓
5. Ajustar (tuning) e otimizar
       ↓
6. Deploy e monitoramento
```

---

#### Algoritmos Mais Comuns para Iniciantes

| Algoritmo | Tipo | Uso típico |
|-----------|------|-----------|
| Regressão Linear | Supervisionado | Prever preços, valores numéricos |
| Regressão Logística | Supervisionado | Classificação binária (sim/não) |
| Árvore de Decisão | Supervisionado | Classificação com regras interpretáveis |
| K-Means | Não-supervisionado | Agrupamento (clustering) |
| Redes Neurais | Supervisionado / outros | Imagens, texto, áudio |

---

### 📘 2. Glossário de Conceitos

| Termo | Definição |
|-------|-----------|
| **Algoritmo** | Conjunto de instruções que o computador segue para resolver um problema ou aprender com dados |
| **Dataset** | Conjunto de dados usado para treinar ou avaliar um modelo de ML |
| **Feature (Atributo)** | Variável de entrada usada pelo modelo para fazer previsões (ex: idade, renda, altura) |
| **Label (Rótulo)** | Valor de saída esperado em aprendizado supervisionado (ex: "spam" ou "não spam") |
| **Modelo** | A "fórmula" ou estrutura matemática que o algoritmo cria após aprender com os dados |
| **Treinamento** | Processo em que o modelo aprende padrões a partir dos dados de treino |
| **Overfitting** | Quando o modelo aprende demais os dados de treino e vai mal em dados novos (decoreba) |
| **Underfitting** | Quando o modelo é simples demais e não aprende nem os padrões básicos dos dados |
| **Hiperparâmetro** | Configuração do modelo definida antes do treinamento (ex: número de camadas numa rede neural) |
| **Acurácia** | Percentual de previsões corretas feitas pelo modelo |
| **Validação Cruzada** | Técnica para avaliar o modelo dividindo os dados em múltiplos subconjuntos de teste |
| **Rede Neural** | Modelo inspirado no cérebro humano, composto por camadas de neurônios artificiais |
| **Deep Learning** | Subcampo do ML que usa redes neurais com muitas camadas para aprender representações complexas |
| **NLP** | Natural Language Processing — área de IA que lida com linguagem humana (texto e fala) |
| **Bias (Viés)** | Erro sistemático no modelo, geralmente causado por dados tendenciosos ou modelo simples |
| **Variância** | Sensibilidade do modelo a flutuações nos dados de treino |
| **Epoch** | Uma passagem completa por todo o dataset durante o treinamento |
| **Batch** | Subconjunto de dados processado de uma vez durante o treinamento |
| **Gradient Descent** | Algoritmo de otimização que ajusta os parâmetros do modelo para minimizar o erro |
| **Transfer Learning** | Técnica de reutilizar um modelo treinado para uma nova tarefa relacionada |

---

### 🔁 3. Prompts Reutilizáveis para Futuras Revisões

Abaixo, uma coleção de prompts testados e validados que podem ser reutilizados em sessões futuras de estudo no NotebookLM ou em qualquer LLM (ChatGPT, Claude, Gemini, etc.):

#### 📌 Prompts de Revisão Rápida
```
"Faça um quiz com 5 perguntas de múltipla escolha sobre [TÓPICO], com gabarito ao final."
```
```
"Resuma os 5 pontos mais importantes sobre [TÓPICO] em formato de bullet points curtos."
```
```
"Crie um mapa mental textual sobre [TÓPICO] com no máximo 3 níveis de profundidade."
```

#### 📌 Prompts de Aprofundamento
```
"Explique [CONCEITO] usando uma analogia do cotidiano, sem usar jargões técnicos."
```
```
"Qual é a diferença prática entre [CONCEITO A] e [CONCEITO B]? Dê um exemplo de quando usar cada um."
```
```
"Quais são os erros mais comuns que iniciantes cometem ao aprender [TÓPICO]?"
```

#### 📌 Prompts de Aplicação Prática
```
"Dê 3 exemplos reais de empresas que usam [CONCEITO/ALGORITMO] e explique como."
```
```
"Como eu implementaria [ALGORITMO] em um projeto simples? Descreva os passos sem código."
```
```
"Quais ferramentas ou bibliotecas Python são mais usadas para [TAREFA DE ML]?"
```

#### 📌 Prompts de Estruturação de Conhecimento
```
"Crie uma tabela comparativa entre [ITEM A], [ITEM B] e [ITEM C] com as colunas: definição, vantagens, desvantagens e caso de uso."
```
```
"Monte um plano de estudos de 4 semanas para dominar os fundamentos de [TÓPICO], com recursos gratuitos."
```
```
"Quais pré-requisitos eu preciso dominar antes de estudar [TÓPICO AVANÇADO]?"
```

---

## 🛠️ Ferramentas Utilizadas

- **[NotebookLM](https://notebooklm.google.com/)** — organização e síntese das fontes com IA
- **[GitHub](https://github.com)** — versionamento e portfólio do projeto
- **[DIO](https://www.dio.me)** — plataforma de desafio e aprendizagem

---

## 👤 Autor

**Gabriel Alves**
Analista de Dados | SQL · Python · Power BI | Background em Finanças e Controladoria

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gabriel_Alves-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/gabriel-alves-06755822b/)

---

⭐ Se este repositório foi útil para você, deixa uma estrela!

