# mini-guia-de-estudos-de-educacao-financeira-basica-para-iniciantes

[![NotebookLM](https://img.shields.io/badge/Tools-Google%20NotebookLM-blue?style=flat-square&logo=google)](https://notebooklm.google.com)
[![Finance](https://img.shields.io/badge/Subject-Financial%20Education-success?style=flat-square)](https://www.bcb.gov.br)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

Este repositório contém um **Miniguia Temático de Educação Financeira** desenvolvido de forma estruturada e inteligente. O projeto foi elaborado utilizando o **Google NotebookLM** como ferramenta central de curadoria, síntese e engenharia de conhecimento, tendo como foco auxiliar pessoas que estão iniciando sua jornada de organização financeira pessoal.

O guia busca simplificar conceitos fundamentais que servem de alicerce para a saúde financeira: **controle de orçamento**, construção de **reserva de emergência** e o entendimento de **juros compostos**.

---

## 🎯 Contexto e Objetivos

A falta de educação financeira básica é uma das principais causas do endividamento e da falta de investimentos no Brasil. Este projeto foi concebido para ser uma porta de entrada amigável, fornecendo um roteiro de estudos prático baseado em fontes oficiais e confiáveis.

### Objetivos deste Estudo:
1. **Dominar o Orçamento Pessoal:** Compreender como dividir a receita líquida de forma equilibrada através da **Regra 50-30-20**.
2. **Construir Segurança Financeira:** Aprender a calcular e estruturar uma **Reserva de Emergência** personalizada de acordo com o perfil profissional.
3. **Compreender o Poder do Tempo:** Entender de forma intuitiva como funcionam os **Juros Compostos** e a importância do reinvestimento.

---

## 📚 Curadoria de Fontes

Para alimentar a inteligência artificial do NotebookLM com materiais oficiais e evitar conselhos enviesados, foram curadas as seguintes fontes públicas de referência nacional:

| Fonte / Documento | Instituição | Descrição do Conteúdo | Link de Acesso |
| :--- | :--- | :--- | :--- |
| **Caderno de Cidadania Financeira (PDF)** | Banco Central do Brasil | Conceitos básicos sobre gestão de finanças pessoais, planejamento e orçamento. | [Acesse o PDF](https://www.bcb.gov.br/pre/pef/port/caderno_cidadania_financeira.pdf) |
| **Cartilha 1 de Educação Financeira (PDF)** | Caixa Econômica Federal | Orientações práticas sobre controle de gastos, planejamento familiar e poupança. | [Acesse o PDF](https://www.caixa.gov.br/Downloads/educacao-financeira-cartilhas/CARTILHA1_EDUCACAO_FINANCEIRA.pdf) |
| **Biblioteca de Cidadania Financeira** | Banco Central do Brasil | Acervo completo de publicações, estudos e materiais didáticos de apoio financeiro. | [Acesse a Biblioteca](https://www.bcb.gov.br/cidadaniafinanceira/cidadania_biblioteca) |
| **Recursos de Educação Financeira** | Caixa Econômica Federal | Portal de ferramentas, simuladores e guias interativos para finanças pessoais. | [Acesse o Portal](https://www.caixa.gov.br/educacao-financeira/recursos/Paginas/default.aspx) |

---

## ⚙️ Como Replicar este Estudo no NotebookLM

Se você deseja recriar ou expandir este ambiente de estudos utilizando o Google NotebookLM, siga os passos abaixo:

1. **Acesse a Ferramenta:** Vá até o [Google NotebookLM](https://notebooklm.google.com) e faça login com sua conta Google.
2. **Crie um Novo Caderno:** Clique em "Novo Caderno" (New Notebook) para abrir um espaço de trabalho limpo.
3. **Adicione as Fontes de Dados:** Na aba de fontes (Sources), clique em adicionar e escolha a opção de inserir **Links da Web** (Link). Copie e cole os links listados na tabela de [Curadoria de Fontes](#-curadoria-de-fontes) deste repositório.
4. **Interaja e Estude:** Com as fontes carregadas, use a barra de chat para fazer suas perguntas. Você pode começar utilizando os templates prontos da nossa [Caixa de Ferramentas de Prompts](#-prompts-reutilizaveis-sua-caixa-de-ferramentas).

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Abaixo está o registro histórico da interação com a IA durante a construção do miniguia, demonstrando os testes de prompts aplicados e como corrigimos desvios conceituais.

### 🔄 Evolução dos Prompts

#### 1. Prompt Inicial (Muito Amplo)
> **Prompt:** *"Como eu posso organizar minha vida financeira?"*
* **Resultado do NotebookLM:** Gerou respostas vagas como "faça uma planilha" e "evite compras por impulso". Sem metodologia prática ou links diretos com as fontes de referência fornecidas.

#### 2. Prompt Intermediário (Foco Metodológico)
> **Prompt:** *"Explique a regra 50-30-20 e como a reserva de emergência se encaixa nela usando os documentos anexados."*
* **Resultado do NotebookLM:** Resposta mais focada. A IA dividiu os conceitos, mas não detalhou como a reserva varia de acordo com o tipo de trabalho do investidor (CLT vs. Autônomo).

#### 3. Prompt Final (Refinado e Estruturado)
> **Prompt:** *"A partir dos manuais do Banco Central e da Caixa, explique a Regra 50-30-20 detalhando o que entra em cada categoria. Em seguida, forneça uma tabela mostrando como calcular a Reserva de Emergência com base nas despesas mensais reais para profissionais CLT/servidores e para profissionais autônomos."*
* **Resultado do NotebookLM:** Resposta exata, direta ao ponto e com dados perfeitamente estruturados.

---

### 🩹 Cicatrizes de IA (O que deu errado e como consertamos)

* **Alucinação no Cálculo da Reserva (Receita Bruta vs. Despesas):** 
  * *O Problema:* Em uma das respostas, a IA afirmou que a reserva de emergência deveria ser de "6 meses da receita bruta mensal do trabalhador". Esse cálculo é ineficiente, pois a reserva deve cobrir o *custo de vida real* (despesas líquidas) e não o faturamento bruto antes dos impostos e despesas essenciais.
  * *A Correção:* Refinamos o prompt instruindo: *"Corrija a definição de reserva de emergência. Ela deve ser calculada estritamente sobre as despesas mensais indispensáveis (custo de vida líquido) do indivíduo, e não sobre a receita bruta. Explique a diferença."*
* **Explicação Excessivamente Matemática de Juros:**
  * *O Problema:* Ao falar sobre juros compostos, a IA respondeu apenas com a fórmula algébrica e termos técnicos de cálculo atuarial, o que afasta o público iniciante.
  * *A Correção:* Aplicamos a técnica de contextualização: *"Reescreva a explicação de juros compostos sem usar fórmulas matemáticas complexas no início. Explique de forma visual o conceito de 'dinheiro gerando novos juros que se somam ao bolo', utilizando a analogia da bola de neve."*

---

## 📖 Miniguia de Estudo: Educação Financeira Básica

Este miniguia resume as lições fundamentais extraídas das fontes oficiais sob curadoria da IA.

### 1. O Orçamento 50-30-20
Uma metodologia recomendada por especialistas para distribuir sua receita líquida mensal (o dinheiro que cai na conta após impostos):

* **50% para Necessidades (Gastos Fixos/Essenciais):**
  Moradia (aluguel, condomínio), alimentação, saúde, transporte, contas básicas (água, luz, internet). É o custo básico para viver.
* **30% para Desejos (Gastos Variáveis/Estilo de Vida):**
  Lazer, jantares fora, assinaturas de streaming, compras não essenciais, viagens. É o que traz qualidade de vida no presente.
* **20% para Prioridades Financeiras (Futuro/Segurança):**
  Investimentos, amortização de dívidas com juros altos ou construção da reserva de emergência. É o seu foco no futuro.

---

### 2. A Reserva de Emergência
A reserva é o colchão financeiro para imprevistos (demissão, problemas de saúde, consertos urgentes). Ela deve ser guardada em investimentos de **baixíssimo risco e alta liquidez** (resgate rápido, como Tesouro Selic ou fundos DI taxa zero).

O cálculo varia de acordo com a previsibilidade da sua renda:

| Perfil Profissional | Estabilidade | Tamanho Recomendado da Reserva | Exemplo Prático (Gasto de R$ 3.000/mês) |
| :--- | :--- | :--- | :--- |
| **Funcionário CLT ou Servidor Público** | Média / Alta | 3 a 6 meses de custo de vida | **R$ 9.000,00 a R$ 18.000,00** |
| **Profissional Autônomo, MEI ou Freelancer** | Baixa | 6 a 12 meses de custo de vida | **R$ 18.000,00 a R$ 36.000,00** |

---

### 3. Juros Compostos: O Efeito Bola de Neve
Enquanto nos juros simples a rentabilidade é sempre calculada em cima do valor inicial investido, nos **juros compostos** o rendimento é calculado em cima do valor inicial somado aos juros já acumulados.
* **Mês 1:** Você investe R$ 1.000,00 e ganha R$ 10,00 de juros. (Total: R$ 1.010,00).
* **Mês 2:** Os novos juros vão incidir sobre R$ 1.010,00, gerando R$ 10,10. (Total: R$ 1.020,10).
* **No longo prazo:** Esse pequeno acréscimo se transforma em uma curva exponencial. O tempo é o fator mais poderoso na multiplicação do dinheiro.

---

### 📖 Glossário de Educação Financeira

* **`Receita Líquida`**  
  O valor de fato recebido por você (salário ou retirada) após todos os descontos de impostos e previdência na fonte. É a base real do seu orçamento.
* **`Custo de Vida`**  
  A soma de todas as despesas essenciais necessárias para manter o seu padrão de vida básico ativo (moradia, alimentação, saúde, contas).
* **`Ativos Financeiros`**  
  Tudo aquilo que coloca dinheiro no seu bolso ao longo do tempo (investimentos, títulos, ações, imóveis alugados).
* **`Passivos Financeiros`**  
  Tudo aquilo que retira dinheiro do seu bolso ao longo do tempo (empréstimos, financiamentos, parcelamentos, cartões de crédito).
* **`Poder de Compra`**  
  A capacidade de adquirir bens e serviços com uma determinada quantidade de dinheiro. É diretamente afetado pela inflação.

---

## 🛠️ Prompts Reutilizáveis (Sua Caixa de Ferramentas)

Copie e cole estes prompts em qualquer LLM (NotebookLM, ChatGPT, Claude) para fazer simulações personalizadas.

### 1. O Mentor do Orçamento 50-30-20
```text
Aja como um planejador financeiro pessoal. Eu recebo uma receita líquida mensal de R$ [INSIRA_VALOR] e minhas despesas fixas essenciais somam R$ [INSIRA_VALOR]. Aplique a regra 50-30-20 e monte um plano detalhado mostrando quanto devo direcionar para Necessidades, Desejos e Prioridades Financeiras. Se minhas despesas essenciais estiverem acima do recomendado de 50%, me dê 3 ideias realistas para equilibrar meu orçamento.
```

### 2. O Calculador de Reserva de Emergência
```text
Minha despesa mensal básica para sobreviver (custo de vida) é de R$ [INSIRA_VALOR]. Eu trabalho sob o regime de [CLT / AUTÔNOMO / CONCURSADO]. Calcule o valor exato recomendado para a minha reserva de emergência e sugira 3 opções de investimentos seguros e de alta liquidez no Brasil para alocar esse dinheiro.
```

### 3. O Explicador Visual de Juros Compostos
```text
Explique o conceito de juros compostos para um iniciante total. Use a analogia de uma planta que cresce e cujas próprias folhas geram novas mudas, ou a clássica bola de neve descendo a montanha. Mostre de forma intuitiva a diferença de rendimento no longo prazo de investir R$ 100 por mês em comparação a guardar esse dinheiro embaixo do colchão.
```

### 4. Quiz de Finanças Pessoais
```text
Gere um quiz interativo de 5 perguntas de múltipla escolha sobre Educação Financeira Básica (abordando orçamento, reserva de emergência, juros compostos e controle de gastos). Faça uma pergunta por vez. Apresente as alternativas e aguarde minha resposta. Só passe para a próxima pergunta após me dar o gabarito comentado da pergunta anterior.
```

---

## 🤝 Contribuições

Este é um projeto de caráter educacional. Caso queira sugerir novos prompts, fontes oficiais ou melhorias didáticas:
1. Faça um **Fork** do repositório.
2. Crie uma branch para sua modificação (`git checkout -b feature/melhoria-didatica`).
3. Envie um **Pull Request** com suas sugestões.

## 📄 Licença

Este projeto está sob a licença [MIT](https://opensource.org/licenses/MIT). Veja o arquivo de licença para mais detalhes.
