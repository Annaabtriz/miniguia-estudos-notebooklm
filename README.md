# 📈 Value Investing & The Graham Methodology: Building a Financial Second Brain

[![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![NotebookLM](https://img.shields.io/badge/Second%20Brain-NotebookLM-emerald.svg)](https://gemini.google.com/notebook/3f5bf85b-a32e-42dd-ba89-b2b10945c934)
[![Markdown](https://img.shields.io/badge/Documentation-Markdown-000000.svg)](https://daringfireball.net/projects/markdown/)

> *Um guia estruturado de estudos sobre os fundamentos do Value Investing (Investimento em Valor), análise fundamentalista e seleção criteriosa de ativos.*

---

## 📌 1. Apresentação do Tema de Interesse

Este repositório é dedicado à **Metodologia de Investimentos de Benjamin Graham** (1894–1976), amplamente reconhecido como o "Pai do Value Investing" e o primeiro a transformar a análise de ações em uma disciplina rigorosa. 

O tema central aborda a filosofia fundamentada em suas duas obras clássicas — *Security Analysis* (1934) e *O Investidor Inteligente* (1949). A abordagem de Graham foca no estudo minucioso de demonstrações financeiras, na diferenciação estrita entre **investimento e especulação**, na busca pelo **Valor Intrínseco** das empresas e no uso disciplinado da **Margem de Segurança** para minimizar riscos no mercado de capitais.

---

## 🎯 2. Objetivos de Estudo

O propósito deste material é consolidar o aprendizado teórico e prático sobre a metodologia de Graham, servindo como base de consulta contínua e aplicação analítica.

### Objetivo Geral
Compreender e dominar os princípios do *Value Investing* clássico para avaliar a saúde financeira de empresas listadas em bolsa e identificar oportunidades de investimento com foco no longo prazo.

### Objetivos Específicos
1. **Compreensão Teórica:**
   * Assimilar os conceitos fundamentais da volatilidade de mercado através da parábola do **Sr. Mercado** (*Mr. Market*).
   * Compreender a distinção conceitual entre **Preço** (cotação de mercado) e **Valor Intrínseco** (valor real do negócio).
   * Analisar os diferentes perfis de investidor propostos por Graham (**Defensivo** vs. **Empreendedor**).

2. **Aplicação Prática e Quantitativa:**
   * Estudar e aplicar a **Fórmula do Valor Intrínseco de Graham** ($VI = \sqrt{22,5 \times LPA \times VPA}$).
   * Executar o cálculo e a verificação da **Margem de Segurança** antes de simular tomadas de decisão de compra.
   * Filtrar e analisar demonstrações financeiras utilizando métricas como P/L, P/VP, Liquidez Corrente e histórico de dividendos.

3. **Desenvolvimento de Ferramentas:**
   * Organizar uma base de conhecimento estruturada com checklists de análise fundamentalista.
   * Desenvolver planilhas ou scripts para automação de triagem de ações segundo os critérios quantitativos de Graham.

---

## 📂 3. Estrutura do Repositório

```text
.
├── 📁 01-fundamentos/          # Conceitos teóricos: Especulação vs. Investimento, Sr. Mercado
├── 📁 02-perfis-investidor/     # Estratégias para o Investidor Defensivo e Empreendedor
├── 📁 03-metricas-e-formulas/   # P/L, P/VP, Liquidez, Margem de Segurança e Fórmula de Graham
├── 📁 04-estudos-de-caso/       # Análises aplicadas a empresas reais e simulações
└── 📁 05-ferramentas/           # Planilhas, checklists e scripts auxiliares de automação

## 📖 4. Curadoria de Fontes e Materiais de Apoio

Abaixo estão listadas as principais fontes em texto e PDF utilizadas na composição deste caderno de estudos:

1. **[Security Analysis (PDF)](https://cdn.bookey.app/files/pdf/book/en/security-analysis.pdf)** — *Benjamin Graham & David Dodd*: Obra fundacional sobre análise fundamentalista e avaliação de ativos.
2. **[Security Analysis 7th Edition (PDF)](https://sanandres.uep.edu.py/filedownload.ashx/Ty4TAZ/704532/security__analysis_7th_edition.pdf)** — Material complementar de referência para estudo do Valor Intrínseco.
3. **A Arquitetura Teórica e Prática do Investimento em Valor** — Documento de síntese sobre o modelo mental do Sr. Mercado e Margem de Segurança.
4. **[Benjamin Graham's 7 Stock Criteria](https://www.bajajfinserv.in/benjamin-grahams-7-stock-criteria)** — Artigo detalhando os 7 filtros quantitativos para o Investidor Defensivo.
5. **[Defensive Investors: Rules from The Intelligent Investor](https://einvestingforbeginners.com/defensive-investors-daah/)** — Guia prático de alocação de ativos e gestão de risco.

---

## 🛠️ 5. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção estão documentadas a evolução das estratégias de encadeamento de comandos (*prompting*), os testes de variações, as respostas obtidas e as **"cicatrizes"** — os desafios, alucinações e ambiguidades enfrentadas na interação com a IA durante a estruturação do estudo sobre a Metodologia de Benjamin Graham.

### 🎯 Matriz de Prompts & Iterações

#### 🧪 Teste 1: Conceituação Teórica (Investimento vs. Especulação)

* **Prompt Naïve (V1):**
  > *"O que é investimento em valor segundo Benjamin Graham?"*
* **Resultado V1:** Resposta genérica e superficial, citando apenas "comprar ações baratas" sem diferenciar o aspecto técnico da análise fundamentalista.
* **Prompt Refinado com Papel e Restrições (V2):**
  > *"Atue como um professor especialista em análise fundamentalista clássica. Explique a distinção conceitual rigorosa entre 'Investimento' e 'Especulação' segundo o Capítulo 1 de 'Security Analysis' (1934) e 'O Investidor Inteligente' (1949) de Benjamin Graham. Use citações diretas e formate a resposta em uma tabela comparativa com 4 critérios de análise."*
* **Resultado V2:** Excelente. A IA trouxe a definição exata de Graham (*"operação que, após análise profunda, promete a segurança do principal..."*) e gerou uma tabela discriminando **Análise**, **Segurança**, **Retorno Esperado** e **Horizonte Temporal**.

#### 🧪 Teste 2: Cálculo Quantitativo (Fórmula do Valor Intrínseco)

* **Prompt Inicial (V1):**
  > *"Como calcular a fórmula de Graham para uma ação?"*
* **Resultado V1:** A IA misturou a fórmula clássica do Investidor Defensivo ($VI = \sqrt{22,5 \times LPA \times VPA}$) com a fórmula modificada para empresas em crescimento ($VI = LPA \times (8,5 + 2g)$), sem alertar sobre a necessidade de ajustes na taxa de juros ou limites de aplicabilidade.
* **Prompt Estruturado com Few-Shot & Chain-of-Thought (V2):**
  > *"Atue como um analista financeiro. Calcule o Valor Intrínseco de uma empresa hipotética com LPA = R$ 4,00 e VPA = R$ 25,00 usando a Fórmula do Investidor Defensivo de Graham ($VI = \sqrt{22,5 \times LPA \times VPA}$).*
  > *Exija o cumprimento das seguintes etapas no raciocínio:*
  > 1. Valide se LPA e VPA são estritamente positivos (caso contrário, aborte e explique por que a fórmula não se aplica).
  > 2. Explique a origem matemática da constante 22,5 ($15 \times 1,5$).
  > 3. Apresente o cálculo passo a passo formatado em LaTeX.
  > 4. Aplique uma Margem de Segurança de 30% sobre o resultado final."*
* **Resultado V2:** Resposta precisa, demonstrando $VI = \sqrt{22,5 \times 4 \times 25} = \sqrt{2250} \approx R\$ 47,43$, reduzido para $R\$ 33,20$ após a margem de segurança de 30%.

### 🩹 "Cicatrizes" & Troubleshooting (Desafios e Soluções)

Durante o processo de extração e sintetização de conhecimento com auxílio da IA, foram identificados e mitigados os seguintes problemas críticos:

1. **Confusão de Fórmulas (Investidor Defensivo vs. Empresas em Crescimento)**
   * **Causa Raiz:** O modelo frequentemente misturava a fórmula clássica do Investidor Defensivo (1949) com revisões posteriores (1962/1974) que contêm a taxa de crescimento esperado ($g$).
   * **Solução Aplicada:** Especificação explícita no prompt da equação exata a ser utilizada, exigindo estritamente a fórmula do Investidor Defensivo ($VI = \sqrt{22,5 \times LPA \times VPA}$).

2. **Alucinação de Métricas Reais de Ações**
   * **Causa Raiz:** Solicitar que a IA buscasse métricas atuais (como P/L, VPA ou cotações) sem uma base de dados atualizada integrada levou à geração de números inventados ou defasados.
   * **Solução Aplicada:** Eliminação de solicitações de dados financeiros em tempo real sem suporte de fontes externas. Adotou-se o uso de *grounding* via RAG (NotebookLM com PDFs dos relatórios) e o fornecimento prévio e manual das métricas nos prompts.

3. **Aplicação Anacrônica em Empresas de Tecnologia (*Techs*)**
   * **Causa Raiz:** O modelo aplicava a fórmula patrimonial de Graham de forma mecânica em empresas modernas baseadas em ativos intangíveis (*asset-light*), distorcendo a análise do Valor Intrínseco.
   * **Solução Aplicada:** Inclusão de travas conceituais (*guardrails*) instruindo a IA a emitir alertas e reconhecer as limitações da aplicação do VPA em modelos de negócios tecnológicos atuais.

### 💡 Principais Lições Aprendidas (Best Practices)

1. **Contextualização Temporal é Crucial em Finanças:** A teoria de Graham foi formulada nas décadas de 1930 a 1970. Instruir o modelo a contextualizar a época dos dados evita distorções na interpretação do valor patrimonial.
2. **Grounding via RAG (NotebookLM) Elimina Alucinações:** Fazer o upload do PDF de *Security Analysis* e utilizar consultas diretas à fonte garantiu que as definições conceituais mantivessem a fidelidade ao texto original.
3. **Instruções de Abortagem (Guardrails):** Definir condições para a IA recusar responder (ex: *"Se o VPA for negativo, não calcule a raiz quadrada e explique a limitação"*) evita erros matemáticos e alucinações de execução.

---

## 📚 6. Miniguia de Estudo: Metodologia Benjamin Graham

Este miniguia compila resumos estruturados, um glossário de termos essenciais e uma biblioteca de prompts para apoiar futuras revisões e análises contínuas.

### 📑 Resumos Estruturados do Assunto

#### A. A Filosofia do Value Investing (Investimento vs. Especulação)
A fundação da teoria de Graham (estabelecida em *Security Analysis*, 1934) baseia-se na distinção rigorosa entre investir e especular. 
* **Investimento:** É a operação que, após análise exaustiva, promete a segurança do principal (capital investido) e um retorno adequado. 
* **Especulação:** Qualquer operação que não atenda a esses requisitos. O foco do investidor não é prever o mercado, mas avaliar o negócio subjacente.

#### B. A Metáfora do "Sr. Mercado" (*Mr. Market*)
Apresentado em *O Investidor Inteligente* (1949), o Sr. Mercado é o sócio imaginário do investidor, sofrendo de flutuações de humor extremas (bipolaridade). 
* **A regra de ouro:** O investidor inteligente deve usar o Sr. Mercado a seu favor (comprando quando ele está deprimido/pessimista e vendendo quando está eufórico), e nunca se deixar influenciar por suas emoções. O mercado existe para *servir* o investidor, não para *guiá-lo*.

#### C. Perfis de Investidor: Defensivo vs. Empreendedor
* **Investidor Defensivo (Passivo):** Busca proteção contra erros e não quer dedicar muito tempo ao acompanhamento do mercado. Prefere carteiras diversificadas, empresas grandes, proeminentes, com longo histórico de dividendos e lucros estáveis.
* **Investidor Empreendedor (Ativo):** Disposto a dedicar tempo e esforço rigoroso para superar o desempenho médio do mercado (*Alpha*). Procura barganhas e "situações especiais" (empresas subavaliadas).

#### D. A Fórmula Clássica de Graham
Para o investidor defensivo, Graham propôs limites rígidos de preço baseados em Lucro (LPA) e Patrimônio (VPA). A combinação do multiplicador de lucros (máximo de 15x) com o multiplicador de patrimônio (máximo de 1,5x) resulta na constante $22,5$ ($15 \times 1,5$).
* **Fórmula do Valor Intrínseco:** $VI = \sqrt{22,5 \times LPA \times VPA}$

### 📖 Glossário de Conceitos Essenciais

* **Valor Intrínseco (VI):** O valor "real" e fundamentado de uma empresa, calculated através de seus ativos, lucros, dividendos e perspectivas futuras, independente da cotação atual na bolsa.
* **Margem de Segurança:** A diferença entre o Valor Intrínseco de uma ação e o seu Preço de Mercado atual. É o princípio central dos investimentos, atuando como um "colchão" que absorve erros de cálculo ou imprevistos econômicos.
* **VPA (Valor Patrimonial por Ação):** Indica quanto do patrimônio líquido da empresa corresponde a cada ação. (Patrimônio Líquido / Nº de Ações).
* **LPA (Lucro por Ação):** Indica a parcela do lucro líquido da empresa que corresponde a cada ação emitida.
* **P/L (Preço sobre Lucro):** Múltiplo que indica quanto o mercado está disposto a pagar pelos lucros da empresa. Graham recomenda P/L $\le$ 15 para investidores defensivos.
* **P/VP (Preço sobre Valor Patrimonial):** Múltiplo que indica quanto o mercado paga pelo patrimônio da empresa. Graham recomenda P/VP $\le$ 1,5.

### 🤖 Biblioteca de Prompts Reutilizáveis (Prompt Toolkit)

Estes prompts foram testados e refinados (*Chain-of-Thought* + *Guardrails*) para garantir que a IA não alucine métricas financeiras e execute a análise estritamente sob os preceitos de Benjamin Graham. Copie e cole na sua ferramenta substituindo os dados entre colchetes `[ ]`.

#### 🛠️ Prompt 1: Cálculo e Auditoria do Valor Intrínseco
> **Objetivo:** Calcular o VI com margem de segurança sem erros matemáticos.

```text
Atue como um analista financeiro sênior especializado em Value Investing. Calcule o Valor Intrínseco usando a Fórmula de Graham Clássica ($VI = \sqrt{22,5 \times LPA \times VPA}$) para os seguintes dados de entrada:
- LPA (Lucro por Ação): R$ [INSERIR LPA]
- VPA (Valor Patrimonial por Ação): R$ [INSERIR VPA]
- Preço Atual de Mercado: R$ [INSERIR PREÇO ATUAL]

Instruções obrigatórias:
1. Valide se LPA ou VPA são negativos (se sim, aborte o cálculo e explique que a fórmula de Graham não se aplica a empresas com prejuízo patrimonial/operacional).
2. Mostre o passo a passo matemático da equação.
3. Compare o VI calculated com o Preço Atual e determine a Margem de Segurança atual (em %).
4. Informe se, baseando-se apenas na margem de segurança de [INSERIR MARGEM EX: 30%], a ação apresenta oportunidade de compra ou se está sobreprecificada.

🛠️ Prompt 2: Validação dos Filtros do Investidor Defensivo
Objetivo: Checar se uma empresa atende aos critérios rígidos de proteção.
Com base nos princípios de 'O Investidor Inteligente' de Benjamin Graham, avalie se a empresa descrita abaixo passa no "Filtro do Investidor Defensivo".
Dados da empresa [NOME DA EMPRESA]:
- P/L atual: [INSERIR P/L]
- P/VP atual: [INSERIR P/VP]
- Histórico de dividendos: [EX: Pagou ininterruptamente nos últimos 10 anos]
- Crescimento dos lucros nos últimos 10 anos: [EX: 30%]

Análise requerida:
1. Verifique se o P/L é menor que 15 e o P/VP é menor que 1.5. 
2. Verifique se a multiplicação de P/L por P/VP ultrapassa a regra máxima de 22,5.
3. Emita um veredito curto (Aprovada/Reprovada) justificando os motivos sob a ótica da mitigação de riscos de Graham.

🛠️ Prompt 3: Revisão Teórica "Explain Like I'm 5" (ELI5)
Objetivo: Revisar conceitos complexos com metáforas fáceis.
Atue como Benjamin Graham. Explique o conceito de [INSERIR CONCEITO, ex: Sr. Mercado / Margem de Segurança / Diferença entre Valor e Preço] de forma simples, didática e utilizando uma metáfora do dia a dia (não use jargões financeiros difíceis). Termine a explicação com um princípio rápido que eu deva memorizar para aplicar nos meus estudos.
