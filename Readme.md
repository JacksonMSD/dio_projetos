# Organizador de Declaração de Imposto de Renda

Ferramenta em Excel que ajuda a **organizar e reunir as informações essenciais** para a declaração de imposto de renda de pessoa física, deixando tudo em um só lugar, de forma padronizada e pronta para consulta na hora de declarar.

## Visão geral

A planilha foi dividida em etapas, cada uma em uma aba, que acompanham a ordem natural de preparação da declaração: primeiro os dados pessoais, depois os rendimentos informados pelos bancos e, por fim, as entradas de receita mês a mês.

> Os dados que acompanham o arquivo (nome, CPF, valores etc.) são **fictícios** e servem apenas como exemplo de preenchimento.

## Estrutura da planilha

### 1. TÍTULAR: dados do titular
Reúne os dados cadastrais da pessoa física que vai declarar:

- Nome, CPF, data de nascimento e título de eleitor
- Nome do cônjuge
- Endereço (rua, rua abreviada e CEP)
- Telefone, celular e e-mail
- Perguntas de sim/não, preenchidas por lista suspensa:
  - Houve alterações da entrega anterior?
  - Dependente cônjuge?
  - Residente do exterior?

### 2. INFORMES: informes de rendimentos bancários
Registra, para até três bancos, os rendimentos informados por cada instituição:

- **Banco**: escolhido em uma lista com código e nome da instituição (ex.: `336 - C6 Bank`, `77 - Banco Inter`)
- **Valor atual**: rendimento informado pelo banco
- **Anexo 📎**: nome do arquivo PDF do informe, para localizar o documento facilmente
- **Total**: soma automática dos valores dos três bancos

### 3. NOTAS: notas bancárias ou extratos de holerites
Tabela para lançar todas as entradas de receita mês a mês, com:

- **Data** do recebimento
- **Categoria**, escolhida em lista suspensa: `HOLERITE`, `CNPJ` ou `FREELANCER`
- **Valor** recebido

### ID_BANKS (aba oculta)
Aba de apoio com a lista de bancos (código + nome) que alimenta a lista suspensa da aba INFORMES.

## Recursos utilizados

- Listas suspensas (validação de dados) para padronizar o preenchimento
- Fórmula de soma para totalizar os rendimentos bancários
- Tabela do Excel na aba NOTAS, que facilita filtrar e ampliar os lançamentos
- Aba auxiliar oculta com a base de bancos
- Abas protegidas, para evitar alterações acidentais na estrutura da planilha

## Como usar

1. Abra o arquivo `organizador_de_declaracao_de_imposto_de_renda.xlsx` no Excel.
2. Preencha a aba **TÍTULAR** com seus dados pessoais.
3. Na aba **INFORMES**, selecione o banco, informe o valor atual e indique o nome do arquivo do informe de cada instituição.
4. Na aba **NOTAS**, lance cada entrada de receita com data, categoria e valor.
5. Com tudo preenchido, use as informações como apoio para preencher a declaração.

## Objetivo

Facilitar a vida de quem precisa declarar o imposto de renda, reduzindo o risco de esquecer documentos ou informações e mantendo os dados organizados ao longo do ano.
