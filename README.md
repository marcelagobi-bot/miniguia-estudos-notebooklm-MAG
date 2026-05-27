<img width="1200" height="480" alt="Miniguia Financeiro" src="https://github.com/user-attachments/assets/99f8764c-7aad-4410-8b74-1e768c6fdd1f" />


<p align="center">



<img src="https://img.shields.io/github/repo-size/marcelagobi-bot/miniguia-estudos-notebooklm-MAG?style=for-the-badge&color=7B3FE4" />

<img src="https://img.shields.io/github/last-commit/marcelagobi-bot/miniguia-estudos-notebooklm-MAG?style=for-the-badge&color=00C896" />

<img src="https://img.shields.io/badge/NOTEBOOKLM-IA%20APLICADA-7B3FE4?style=for-the-badge" />

<img src="https://img.shields.io/badge/STATUS-CONCLUÍDO-00C896?style=for-the-badge" />




</p>

# 📚 Miniguia Inteligente de Finanças Pessoais com NotebookLM e IA
Projeto desenvolvido para o desafio da DIO utilizando Inteligência Artificial como ferramenta de aprendizagem ativa. 


## 📑 Índice

- [📋 Contexto e Objetivos](#contexto)
- [📚 Curadoria de Fontes Oficiais](#fontes)
- [🧠 Engenharia de Prompts](#prompts)
- [📖 Miniguia de Estudo](#miniguia)
- [📚 Glossário](#glossario)
- [🚀 Aprendizados Obtidos](#aprendizados)
- [💻 Tecnologias Utilizadas](#tecnologias)
- [🛠️ Como Replicar](#replicar)

<a id="contexto"></a>

## 📋 Contexto e Objetivos
Este repositório foi desenvolvido como entrega para o Desafio de Projeto da **Digital Innovation One (DIO)**. O projeto consiste na criação de um caderno temático inteligente no **NotebookLM** focado em conceitos financeiros introdutórios, utilizando a Inteligência Artificial como uma ferramenta de aprendizagem ativa e curadoria crítica.

*   **Tema Escolhido:** Fundamentos de Organização Financeira, Juros Compostos e Introdução aos Investimentos de Renda Fixa.
*   **Objetivo de Estudo:** Compreender como a inflação afeta o poder de compra, dominar a mecânica dos juros compostos e mapear as principais opções introdutórias de Renda Fixa no cenário brasileiro para a construção de uma reserva de emergência.

---

<a id="fontes"></a>

## 📚 Curadoria de Fontes Oficiais
Para alimentar o NotebookLM com informações oficiais, seguras e livres de vieses comerciais, foram selecionadas as seguintes fontes abertas em formato de texto e links oficiais:

1.  **Banco Central do Brasil (BCB) - Caderno de Educação Financeira**
    *   *Descrição:* Guia oficial sobre gestão de despesas, orçamento familiar e uso consciente do crédito.
    *   *Acesso:* Conteúdo programático oficial de cidadania financeira do BCB.
    *    **Acesso:** https://www.bcb.gov.br/cidadaniafinanceira
2.  **Tesouro Direto - Guia Oficial do Investidor**
    *   *Descrição:* Portal educacional oficial detalhando o funcionamento dos títulos públicos (Tesouro Selic, Tesouro IPCA+ e Tesouro Prefixado).
    *   *Acesso:* Seção "Como Investir" do site do Tesouro Nacional.
    *    **Acesso:** https://www.bcb.gov.br/cidadaniafinanceira
3.  **CVM (Comissão de Valores Mobiliários) - Série TOP Facilita: Investimentos**
    *   *Descrição:* Material educativo da autarquia que regula o mercado, explicando os conceitos fundamentais de risco, retorno e diversificação.
    *   *Acesso:* Cadernos educativos do Portal do Investidor da CVM.
    *   **Acesso:** https://www.gov.br/cvm/pt-br/assuntos/educacao-financeira

---

<a id="prompts"></a>

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Abaixo está o registro dos testes de prompts realizados dentro do NotebookLM para extrair análises profundas a partir das fontes carregadas.

### ❌ Teste 1: Abordagem Direta (Resultado Superficial)
*   **Prompt enviado:** *"O que é melhor: Tesouro Selic ou Poupança?"*
*   **Resultado da IA:** Uma resposta genérica dizendo que o Tesouro Selic costuma render mais, porém sem embasamento técnico ou conexão direta com os textos.
*   **Cicatriz/Lição aprendida:** O NotebookLM precisa que o contexto e as métricas sejam explicitados. Perguntas abertas como "o que é melhor" geram respostas vagas.

### ✅ Teste 2: Abordagem Refinada (Sucesso Técnico)
*   **Prompt enviado:** *"Com base nos materiais do Banco Central e da CVM fornecidos, faça uma comparação técnica entre a Caderneta de Poupança e o Tesouro Selic. Considere os fatores: liquidez (resgate), segurança (garantias) e o impacto da taxa Selic no rendimento de ambos. Cite as referências do texto."*
*   *   **Resultado da IA:** Resposta precisa e bem contextualizada. A IA explicou que o Tesouro Selic possui garantia do Tesouro Nacional (risco soberano), enquanto a poupança segue regras de rendimento atreladas à taxa Selic, especialmente quando ela está abaixo de 8,5% ao ano.
---

<a id="miniguia"></a>

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado do Assunto

*   **O Efeito dos Juros Compostos:** Diferente dos juros simples (onde o percentual incide apenas sobre o valor inicial), os juros compostos representam o conceito de "juros sobre juros". Matematicamente, a evolução do montante ($M$) ao longo do tempo ($t$) com uma taxa ($i$) sobre um capital inicial ($C$) segue a função exponencial:
$$
M = C(1 + i)^t
$$
    Isso significa que o fator tempo é o elemento mais crucial para a multiplicação do patrimônio.
*   **A Renda Fixa e a Reserva de Emergência:** A reserva de emergência deve equivaler a 3 a 6 meses do custo de vida. Pelas diretrizes da CVM, os ativos ideais para esse fim devem priorizar a **Liquidez Diária** (resgate imediato) e **Baixa Volatilidade** (baixo risco de perda de valor), destacando-se o Tesouro Selic e CDBs com liquidez diária cobertos pelo FGC (Fundo Garantidor de Créditos).

<a id="glossario"></a>

## 📚 Glossário de Conceitos Fundamentais

| Termo | Definição |
| :--- | :--- |
| **Taxa Selic** | Taxa básica de juros da economia brasileira definida pelo Copom (Banco Central). Influencia empréstimos, financiamentos e investimentos de renda fixa. |
| **Inflação (IPCA)** | Índice que mede a variação dos preços no país e o aumento do custo de vida. |
| **Juros Compostos** | Modelo de rendimento onde os juros incidem sobre o valor inicial e também sobre os juros acumulados anteriormente. |
| **Liquidez** | Facilidade de converter um investimento em dinheiro disponível rapidamente. |
| **Risco Soberano** | Risco relacionado à capacidade do governo honrar pagamentos de títulos públicos. |
| **Renda Fixa** | Categoria de investimentos com regras de rentabilidade definidas no momento da aplicação. |
| **Tesouro Selic** | Título público atrelado à taxa Selic, indicado para reserva de emergência devido à alta segurança e liquidez. |
| **CDB** | Certificado de Depósito Bancário emitido por bancos como forma de captação de recursos. |
| **FGC** | Fundo Garantidor de Créditos que protege determinados investimentos em instituições financeiras até o limite estabelecido. |
| **Rentabilidade Real** | Ganho obtido acima da inflação, representando aumento real do poder de compra. |
| **Reserva de Emergência** | Valor guardado para imprevistos financeiros e despesas inesperadas. |
| **Diversificação** | Estratégia de distribuir investimentos em diferentes ativos para reduzir riscos. |

### 3. Toolkit de Prompts Reutilizáveis para Revisão
Copie e cole estes prompts no seu NotebookLM para fixar o aprendizado ou simular cenários com novas fontes:

*   `"Atue como um professor de finanças. Com base nos documentos, crie um estudo de caso prático de uma família com orçamento estourado e peça para eu propor uma solução com base nas regras do Caderno do BCB."`
*   `"Extraia dos textos fornecidos uma tabela comparativa listando as vantagens e desvantagens de se investir no Tesouro IPCA+ em cenários de inflação alta."`
*   `"Crie um quiz de 3 perguntas com respostas justificadas sobre a diferença entre rentabilidade nominal e rentabilidade real."`

---
<a id="aprendizados"></a>

## 🚀 Aprendizados Obtidos

Durante o desenvolvimento deste projeto foi possível compreender:

- A importância da engenharia de prompts para gerar respostas mais precisas;
- Como utilizar IA como ferramenta de aprendizagem ativa;
- Diferença entre respostas genéricas e prompts contextualizados;
- A relevância de utilizar fontes oficiais para estudos financeiros;
- Como estruturar documentação técnica no GitHub utilizando Markdown.

---

<a id="tecnologias"></a>

## 💻 Tecnologias e Ferramentas Utilizadas

- NotebookLM
- GitHub
- Markdown
- Inteligência Artificial
- Documentação Técnica

---

<a id="replicar"></a>

## 🛠️ Como Replicar este Caderno Temático

1. Abra o NotebookLM.
2. Crie um novo caderno chamado "Estudos Financeiros Introdutórios".
3. Faça o upload das fontes oficiais mencionadas na seção de Curadoria.
4. Utilize o Toolkit de Prompts para gerar novos resumos e revisar os conteúdos.
5. Explore perguntas diferentes para testar a capacidade analítica da IA.

---
## ✨ Conclusão do Projeto

Este projeto permitiu explorar o uso da Inteligência Artificial como ferramenta prática de aprendizagem ativa, fortalecendo habilidades de pesquisa, pensamento crítico, documentação técnica e organização do conhecimento.
