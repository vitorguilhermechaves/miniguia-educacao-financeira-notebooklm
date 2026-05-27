# miniguia-educacao-financeira-notebooklm
Caderno temático criado com apoio do NotebookLM para estudo introdutório de educação financeira, com fontes abertas, prompts, resumos, glossário e revisão guiada.

# Miniguia de Estudos com NotebookLM: Educação Financeira Introdutória

## 1. Contexto do projeto

Este repositório foi desenvolvido como entrega do desafio prático da DIO voltado à criação de um caderno temático no NotebookLM. O tema escolhido foi **educação financeira introdutória**, com foco em organização do orçamento pessoal, consumo consciente, juros, crédito, reserva de emergência e primeiros conceitos de investimento.

A escolha do tema se justifica pela relevância prática da educação financeira para a tomada de decisões cotidianas. Antes de falar em investimentos complexos, é necessário compreender como o dinheiro entra e sai do orçamento, como os juros afetam dívidas e aplicações, qual é a função da reserva de emergência e quais critérios básicos devem ser considerados antes de investir.

O NotebookLM foi utilizado como ferramenta de aprendizagem ativa, permitindo reunir fontes confiáveis, formular perguntas estratégicas, comparar respostas, identificar lacunas conceituais e consolidar o conhecimento em um miniguia de estudo.

## 2. Objetivos de estudo

O objetivo geral deste caderno temático é construir uma base introdutória de educação financeira para apoiar decisões pessoais mais conscientes.

Como objetivos específicos, o estudo busca compreender a importância do orçamento pessoal; identificar a diferença entre receita, despesa, poupança, dívida e investimento; reconhecer o impacto dos juros no crédito e nos financiamentos; compreender a utilidade da reserva de emergência; diferenciar liquidez, risco e rentabilidade; e elaborar prompts reutilizáveis para futuras revisões com apoio da IA.

## 3. Fontes abertas selecionadas

As fontes abaixo foram selecionadas por serem abertas, acessíveis e adequadas a um estudo introdutório. A curadoria priorizou materiais de instituições públicas ou reconhecidas em educação financeira, com linguagem didática e aplicabilidade prática.

| Nº | Fonte | Instituição | Tipo | Link | Justificativa |
|---|---|---|---|---|---|
| 1 | Caderno de Educação Financeira: Gestão de Finanças Pessoais | Banco Central do Brasil | PDF | https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf | Material central do estudo, pois aborda orçamento, consumo, crédito, poupança, investimento, risco, liquidez e planejamento financeiro. |
| 2 | Glossário Simplificado de Termos Financeiros | Banco Central do Brasil | PDF | https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Informacoes_gerais/glossario_cidadania_financeira.pdf | Fonte de apoio para compreender conceitos básicos como juros, crédito, financiamento, poupança, rentabilidade e demais termos financeiros essenciais. |
| 3 | O Uso do Crédito | Banco Central do Brasil | PDF | https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Folhetos_Serie_II_Financas_Pessoais/folder_serie_II_uso_credito.pdf | Material complementar sobre uso responsável do crédito, empréstimos, financiamentos, compras a prazo e impacto dos juros no orçamento. |
| 4 | Calculadora do Cidadão | Banco Central do Brasil | Ferramenta aberta | https://www.bcb.gov.br/meubc/calculadoradocidadao | Ferramenta prática para simular cálculos financeiros e visualizar o efeito do tempo e dos juros. |
| 5 | Guia de Planejamento Financeiro | Comissão de Valores Mobiliários | PDF | https://www.gov.br/investidor/pt-br/educacional/publicacoes-educacionais/guias/guia-de-planejamento-financeiro/guia-planejamento-financeiro.pdf/@@display-file/file | Complementa o estudo com conceitos sobre planejamento, diversificação, objetivos financeiros e cuidados com promessas irreais de rentabilidade. |

> Observação: as páginas antigas do Banco Central sobre planejamento e juros foram substituídas por PDFs oficiais e estáticos, mais adequados para validação no GitHub e para upload no NotebookLM.

## 4. Organização do caderno temático no NotebookLM

Após selecionar as fontes, o caderno foi organizado no NotebookLM com o título **Educação Financeira Introdutória: orçamento, juros e primeiros investimentos**.

A lógica de organização adotada foi a seguinte: primeiro foram carregadas as fontes sobre finanças pessoais e planejamento; em seguida, foram incluídos o glossário financeiro, o material específico sobre uso do crédito e a ferramenta de simulação; por fim, foi utilizada a fonte sobre planejamento financeiro e investimento para consolidar conceitos como risco, liquidez, rentabilidade e diversificação.

A partir desse conjunto, foram formuladas perguntas progressivas, começando por conceitos básicos e avançando para aplicações práticas. A intenção foi evitar respostas genéricas e conduzir a IA a trabalhar com base nas fontes, sempre pedindo síntese, exemplos e referências.

## 5. Engenharia de prompts e cicatrizes do processo

Nesta etapa, foram testadas perguntas estratégicas e variações de prompts para melhorar a qualidade das respostas obtidas no NotebookLM. O foco não foi apenas obter respostas prontas, mas compreender como formular boas perguntas, comparar resultados e corrigir falhas de interpretação.

| Teste | Prompt utilizado | Objetivo | Resposta consolidada | Referências esperadas | Cicatriz / aprendizado |
|---|---|---|---|---|---|
| 1 | Explique, com base nas fontes, o que é educação financeira e por que ela é importante para uma pessoa iniciante. | Obter uma visão geral do tema. | Educação financeira é o processo de desenvolver conhecimentos e comportamentos que ajudam a pessoa a planejar, consumir, poupar, usar crédito com responsabilidade e tomar decisões financeiras mais conscientes. | Fontes 1 e 2 | O primeiro prompt gerou uma resposta ampla demais. A melhoria foi pedir que a explicação fosse “para uma pessoa iniciante” e “com base nas fontes”. |
| 2 | A partir das fontes, organize os principais passos para montar um orçamento pessoal mensal. | Extrair procedimento prático. | O orçamento deve começar pelo levantamento das receitas, seguido pelo registro das despesas fixas e variáveis, identificação de desperdícios, definição de metas e acompanhamento periódico. | Fonte 1 | A resposta inicial confundiu orçamento com investimento. A variação do prompt passou a pedir “passos” e “orçamento pessoal mensal”. |
| 3 | Qual é a diferença entre poupar e investir? Responda em linguagem simples e dê um exemplo cotidiano. | Diferenciar conceitos próximos. | Poupar significa separar parte da renda para uso futuro. Investir significa aplicar o dinheiro poupado buscando remuneração, considerando liquidez, risco e rentabilidade. | Fonte 1 | O NotebookLM trouxe conceitos corretos, mas muito técnicos. A expressão “linguagem simples” ajudou a gerar resposta mais adequada ao público iniciante. |
| 4 | Explique como os juros podem trabalhar contra uma pessoa endividada e a favor de uma pessoa que investe. | Compreender juros no crédito e nos investimentos. | Os juros aumentam o custo de dívidas e financiamentos, especialmente quando a pessoa atrasa pagamentos ou usa crédito caro. Nos investimentos, os juros podem ampliar o patrimônio ao longo do tempo, principalmente quando os rendimentos são reinvestidos. | Fontes 1, 3 e 4 | A IA respondeu melhor quando o prompt comparou duas situações opostas: pessoa endividada e pessoa investidora. |
| 5 | Com base nas fontes, explique o que é reserva de emergência e quais características ela deve ter. | Consolidar conceito de segurança financeira. | A reserva de emergência é um valor separado para imprevistos. Deve priorizar liquidez e baixo risco, pois precisa estar disponível rapidamente e com menor chance de perda. | Fonte 1 | A resposta inicial sugeria rentabilidade como prioridade. A correção foi pedir expressamente as “características” da reserva. |
| 6 | Liste os conceitos de liquidez, risco e rentabilidade, mostrando como eles se relacionam. | Preparar o glossário. | Liquidez é a facilidade de transformar um investimento em dinheiro; risco é a possibilidade de perda ou variação negativa; rentabilidade é o retorno esperado ou obtido. Em geral, promessas de alta liquidez, baixo risco e alta rentabilidade ao mesmo tempo devem ser analisadas com cautela. | Fontes 1, 2 e 5 | O aprendizado foi que conceitos financeiros ficam mais claros quando comparados entre si, e não estudados isoladamente. |
| 7 | Crie um resumo estruturado de educação financeira introdutória, separando em orçamento, crédito, reserva de emergência e investimentos. | Gerar a base do miniguia. | A resposta final organizou o tema em quatro blocos: controle financeiro, uso consciente do crédito, construção de proteção financeira e introdução aos investimentos. | Fontes 1, 2, 3 e 5 | O prompt funcionou melhor quando indicou previamente os tópicos que deveriam estruturar a resposta. |
| 8 | Gere cinco perguntas de revisão sobre educação financeira para eu testar se compreendi o conteúdo das fontes. | Criar material de revisão ativa. | Foram geradas perguntas sobre orçamento, juros, reserva de emergência, liquidez, risco, rentabilidade e consumo consciente. | Fontes 1 a 5 | A pergunta foi útil para transformar a IA em ferramenta de autoavaliação, não apenas de resumo. |

## 6. Miniguia de estudo

### 6.1. Educação financeira

Educação financeira é a capacidade de compreender informações, hábitos e decisões relacionadas ao uso do dinheiro. Ela não se limita a saber fazer cálculos, pois envolve comportamento, planejamento e escolhas conscientes.

Uma pessoa financeiramente educada tende a conhecer sua renda, controlar seus gastos, evitar dívidas desnecessárias, planejar objetivos, formar reservas e avaliar riscos antes de contratar crédito ou investir.

O ponto central é transformar o dinheiro em instrumento de organização da vida, e não em fonte permanente de descontrole.

### 6.2. Orçamento pessoal

O orçamento pessoal é uma ferramenta de registro e planejamento das entradas e saídas de dinheiro. Ele permite visualizar quanto a pessoa ganha, quanto gasta, onde há excesso e quais ajustes podem ser feitos.

A construção de um orçamento começa pelo registro das receitas, como salário, renda extra ou benefícios. Depois, devem ser anotadas as despesas fixas, como aluguel, água, energia, internet e transporte, e as despesas variáveis, como lazer, alimentação fora de casa e compras eventuais.

O orçamento não deve ser visto apenas como restrição. Ele é uma ferramenta de escolha. Ao saber para onde o dinheiro está indo, a pessoa consegue decidir melhor o que manter, reduzir ou eliminar.

### 6.3. Consumo consciente

Consumo consciente significa avaliar se uma compra é necessária, se cabe no orçamento e se está alinhada com os objetivos da pessoa. Não se trata de deixar de consumir, mas de evitar decisões impulsivas que comprometam a saúde financeira.

Uma pergunta útil antes de comprar é: “essa despesa aproxima ou afasta meus objetivos financeiros?”. Esse tipo de reflexão ajuda a reduzir gastos automáticos e aumenta a capacidade de poupar.

### 6.4. Crédito e juros

O crédito permite antecipar consumo, mas possui custo. Esse custo aparece principalmente nos juros e demais encargos da operação. Por isso, antes de contratar empréstimos, financiamentos ou parcelamentos, é importante comparar o custo total da operação.

Os juros podem trabalhar contra a pessoa quando ela se endivida em modalidades caras, atrasa pagamentos ou usa crédito de forma recorrente para cobrir gastos do mês. Por outro lado, os juros podem trabalhar a favor quando a pessoa investe com planejamento e reinveste os rendimentos ao longo do tempo.

A principal lição é que o crédito deve ser usado com responsabilidade. Parcelas pequenas podem parecer inofensivas, mas várias parcelas acumuladas podem comprometer a renda futura.

### 6.5. Reserva de emergência

A reserva de emergência é o dinheiro separado para situações imprevistas, como perda de renda, problemas de saúde, consertos urgentes ou despesas inesperadas.

Sua função não é buscar a maior rentabilidade possível, mas oferecer segurança. Por isso, uma boa reserva deve priorizar liquidez, baixo risco e facilidade de acesso. Em outras palavras, o dinheiro precisa estar disponível quando necessário, sem exposição excessiva a perdas.

A reserva de emergência é uma etapa anterior a investimentos mais arriscados. Sem ela, qualquer imprevisto pode obrigar a pessoa a contrair dívidas ou resgatar investimentos em momento inadequado.

### 6.6. Poupar e investir

Poupar é separar parte da renda para uso futuro. Investir é aplicar o valor poupado com expectativa de remuneração.

A poupança é o hábito de guardar. O investimento é a decisão sobre onde colocar o dinheiro guardado. Para investir melhor, é necessário considerar objetivos, prazos, liquidez, risco e rentabilidade.

Antes de investir, a pessoa deve responder algumas perguntas: qual é o objetivo do dinheiro? Quando ele será usado? Qual risco eu aceito correr? Preciso poder resgatar rapidamente? Estou entendendo o produto em que estou aplicando?

### 6.7. Liquidez, risco e rentabilidade

Liquidez é a facilidade de transformar um investimento em dinheiro disponível. Quanto maior a liquidez, mais fácil é resgatar o valor.

Risco é a possibilidade de perda, oscilação negativa ou resultado diferente do esperado. Nenhum investimento é totalmente livre de risco, embora existam produtos mais seguros e mais arriscados.

Rentabilidade é o retorno do investimento. Pode ser prefixada, pós-fixada ou variável, a depender do produto financeiro.

Esses três elementos devem ser analisados em conjunto. Uma promessa de alta rentabilidade, alta liquidez e baixo risco ao mesmo tempo deve ser vista com cautela. Em finanças, retornos maiores geralmente envolvem algum tipo de risco adicional.

### 6.8. Primeiros passos para uma vida financeira organizada

O primeiro passo é conhecer a própria realidade financeira. Isso exige registrar receitas e despesas. O segundo passo é ajustar o orçamento, reduzindo gastos desnecessários e priorizando objetivos. O terceiro passo é evitar dívidas caras e usar crédito com responsabilidade. O quarto passo é formar reserva de emergência. O quinto passo é estudar investimentos simples, respeitando o próprio perfil, prazo e tolerância ao risco.

A educação financeira é um processo contínuo. O objetivo não é decorar conceitos, mas desenvolver critérios para tomar decisões melhores.

## 7. Glossário de conceitos

| Conceito | Definição |
|---|---|
| Receita | Todo dinheiro que entra no orçamento, como salário, renda extra, benefícios ou rendimentos. |
| Despesa | Todo gasto realizado, seja fixo, variável, necessário ou eventual. |
| Orçamento pessoal | Instrumento de organização das receitas e despesas em determinado período. |
| Despesa fixa | Gasto que se repete com valor igual ou aproximado, como aluguel, internet e mensalidades. |
| Despesa variável | Gasto que muda de valor conforme o consumo, como alimentação, transporte, lazer e compras. |
| Consumo consciente | Prática de consumir avaliando necessidade, orçamento, prioridade e impacto futuro. |
| Poupança | Hábito de separar parte da renda para uso futuro. |
| Investimento | Aplicação do dinheiro poupado com expectativa de retorno. |
| Juros | Remuneração pelo uso do dinheiro no tempo. Pode representar custo no crédito ou ganho no investimento. |
| Crédito | Recurso financeiro tomado para pagamento futuro, geralmente com juros e encargos. |
| Custo Efetivo Total | Indicador que representa o custo total de uma operação de crédito, incluindo juros, tarifas e encargos. |
| Reserva de emergência | Valor separado para cobrir imprevistos, com prioridade para liquidez e baixo risco. |
| Liquidez | Facilidade de converter um ativo ou investimento em dinheiro disponível. |
| Risco | Possibilidade de perda, oscilação ou resultado diferente do esperado. |
| Rentabilidade | Retorno obtido ou esperado em uma aplicação financeira. |
| Diversificação | Estratégia de distribuir recursos em diferentes ativos para reduzir exposição a riscos específicos. |
| Perfil de investidor | Conjunto de características que indica a tolerância ao risco, objetivos e prazo do investidor. |
| Planejamento financeiro | Processo de organizar recursos, objetivos, prazos e decisões financeiras. |

## 8. Prompts reutilizáveis para revisões futuras

Os prompts abaixo podem ser reutilizados no NotebookLM ou em outras ferramentas de IA, sempre com a recomendação de solicitar respostas baseadas nas fontes utilizadas.

### Prompt 1 — resumo geral

```text
Com base nas fontes carregadas, faça um resumo introdutório sobre educação financeira, explicando os conceitos de orçamento, consumo consciente, crédito, juros, reserva de emergência e investimentos. Use linguagem simples e destaque as ideias mais importantes para iniciantes.
```

### Prompt 2 — explicação por tópicos

```text
Explique o tema educação financeira em cinco blocos: orçamento pessoal, controle de gastos, uso do crédito, reserva de emergência e primeiros investimentos. Em cada bloco, apresente conceito, importância e exemplo prático.
```

### Prompt 3 — glossário

```text
Com base nas fontes, crie um glossário com os principais conceitos de educação financeira introdutória. Para cada conceito, apresente uma definição curta, clara e adequada para estudantes iniciantes.
```

### Prompt 4 — comparação de conceitos

```text
Compare os conceitos de poupar e investir; liquidez, risco e rentabilidade; crédito e financiamento. Explique as diferenças em linguagem simples e dê exemplos cotidianos.
```

### Prompt 5 — revisão ativa

```text
Crie dez perguntas de revisão sobre educação financeira introdutória com base nas fontes. Depois, apresente um gabarito comentado, explicando por que cada resposta está correta.
```

### Prompt 6 — aplicação prática

```text
Imagine uma pessoa que recebe salário mensal e deseja organizar sua vida financeira. Com base nas fontes, proponha um plano inicial em etapas para controlar gastos, reduzir dívidas, formar reserva de emergência e começar a estudar investimentos.
```

### Prompt 7 — identificação de erros comuns

```text
Com base nas fontes, liste os erros mais comuns de pessoas iniciantes em finanças pessoais, como uso inadequado do crédito, falta de orçamento e ausência de reserva de emergência. Explique como evitar cada erro.
```

### Prompt 8 — estudo para prova ou apresentação

```text
Transforme o conteúdo das fontes em um roteiro de apresentação de cinco minutos sobre educação financeira introdutória. Organize em introdução, desenvolvimento e conclusão.
```

## 9. Principais aprendizados

O estudo demonstrou que a IA pode ser uma excelente ferramenta de aprendizagem ativa quando é utilizada com fontes confiáveis, perguntas bem formuladas e análise crítica das respostas.

O NotebookLM não deve ser usado apenas para gerar resumos automáticos. Seu maior valor aparece quando o estudante cria boas perguntas, compara respostas, identifica dúvidas, pede exemplos e valida as informações com base nas referências.

No tema financeiro, esse cuidado é ainda mais importante, porque respostas genéricas ou mal interpretadas podem levar a decisões equivocadas. Por isso, a curadoria das fontes e o registro das “cicatrizes” do processo são partes essenciais do aprendizado.

## 10. Como reproduzir este projeto

Para reproduzir este caderno temático, siga os passos abaixo:

1. Crie um novo caderno no NotebookLM.
2. Faça upload das fontes selecionadas na seção 3.
3. Utilize os prompts da seção 8 para gerar respostas, resumos e revisões.
4. Compare as respostas com as referências apresentadas pelo NotebookLM.
5. Ajuste os prompts quando as respostas ficarem genéricas ou incompletas.
6. Registre os aprendizados e as dificuldades encontradas.
7. Publique este README em um repositório do GitHub.
