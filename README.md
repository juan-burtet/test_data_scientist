### Introdução
Modelos de score de crédito calculam a probabilidade de inadimplência e são uma das
principais ferramentas utilizadas por diversas empresas para aprovar ou negar um crédito.
O objetivo deste desafio é criar um modelo preditivo calculando a probabilidade de
inadimplência de cada novo pedido de crédito.

### Dados:
Cada linha representa um cliente e as colunas representam os dados (informações) desses
clientes.
A variável resposta é a coluna inadimplente, que indica se o tomador veio a se tornar
inadimplente(1) ou não(0).

#### As variáveis da base de dados são descritas abaixo:

**idade:** A idade do cliente.

**numero_de_dependentes:** O número de pessoas dependentes do cliente.

**salario_mensal:** Salário mensal do cliente.

**numero_emprestimos_imobiliarios:** Quantidade de empréstimos imobiliários que o
cliente possui em aberto.

**numero_vezes_passou_90_dias:** Número de vezes que o tomador passou mais
de 90 dias em atraso.

**util_linhas_inseguras:** Quanto que o cliente está usando, relativamente ao limite
dele, de linhas de crédito que não são seguradas por qualquer bem do tomador
e.g: imoveis, carros etc.

**vezes_passou_de_30_59_dias:** Número de vezes que o cliente atrasou, entre 30
e 59 dias, o pagamento de um empréstimo.

**razao_debito:** Razão entre as dívidas e o patrimônio do tomador. razão débito =
Dividas/Patrimônio

**numero_linhas_crdto_aberto:** Número de empréstimos em aberto pelo cliente.

**numero_de_vezes_que_passou_60_89_dias:** Número de vezes que o cliente
atrasou, entre 60 e 89 dias, o pagamento de um empréstimo.

**Obs: Estes dados são fictícios, portanto é possível que existam
incoerências, o que é perfeitamente comum em dados reais.**

## Objetivo:
Construir qualquer modelo preditivo utilizando o arquivo treino.csv.
Utilize este modelo para gerar as previsões na base **teste.csv**, inserindo uma nova coluna
na tabela de dados do arquivo **teste.csv** que contenha as previsões e nomeie esta coluna
com o nome **[inadimplente]**.

### Avaliação:
Serão avaliados o código, preferencialmente em Python ou R, e o desempenho do modelo.
Compartilhe com o recrutador a sua solução através de um repositório(público) na sua conta do Github.
