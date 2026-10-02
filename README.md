# Controle simples de almoxarifado

Atividade feita em Python e SQLite, sem a parte do DER. O codigo foi mantido simples para rodar pelo terminal.

## Como executar

Precisa ter Python 3 instalado. Na pasta do projeto, execute:

```text
python main.py
```

Na primeira execucao, o programa cria o arquivo `almoxarifado.db` e carrega os dados de exemplo definidos em `banco.sql`. O script SQL cria as tabelas `produtos`, `entradas` e `saidas`, e a view `vw_estoque`. Cada tabela comeca com pelo menos tres registros.

## O que o programa faz

- Lista os produtos e o valor total do estoque por categoria.
- Cadastra produtos validando categoria, valor unitario e quantidade.
- Registra entradas e saidas e atualiza o saldo automaticamente.
- Lista as saidas da data mais recente para a mais antiga.
- Mostra movimentacoes e maiores saidas dentro de um periodo informado.
- Mostra produtos que chegaram ao estoque minimo (0) ou maximo (100), com o percentual atingido.

O limite de estoque definido para este exemplo e de 0 a 100 unidades por produto. As datas devem ser digitadas no formato `AAAA-MM-DD`."# Simulado-Sap" 
