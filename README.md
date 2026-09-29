# Desafio-2

# Cadastro de Produtos

Projeto desenvolvido em **PHP e MySQL** para praticar cadastro e validação de produtos em um banco de dados.

## Objetivo

Criar um sistema simples que permita cadastrar produtos informando o **nome** e o **preço**, realizando a validação dos dados antes de salvar no banco de dados.

## Funcionalidades

* Criar a tabela `produtos` no banco de dados `exercicio`.
* Exibir um formulário para cadastro de produtos.
* Solicitar:

  * Nome do Produto
  * Preço
* Validar se o nome do produto não está vazio.
* Validar se o preço é um número maior que zero.
* Inserir os dados válidos no banco de dados.
* Exibir mensagem de sucesso após o cadastro.
* Exibir mensagem de erro quando os dados forem inválidos.

## Tecnologias utilizadas

* **PHP**
* **HTML**
* **MySQL**
* **MySQL Workbench**

## Validações

Quando os dados estão corretos, o sistema exibe:

> Produto cadastrado com sucesso!

Quando os dados estão incorretos, uma mensagem de erro é apresentada, por exemplo:

> Erro: O preço deve ser um número positivo.

## Banco de Dados

O projeto utiliza o banco de dados:

```sql
exercicio
```

E a tabela:

```sql
produtos
```

O **MySQL Workbench** foi utilizado para verificar se os produtos foram inseridos corretamente na tabela.

## Como executar

1. Inicie o **Apache** e o **MySQL** no XAMPP.
2. Crie o banco de dados `exercicio`.
3. Execute o script SQL indicado na atividade para criar a tabela `produtos`.
4. Coloque os arquivos do projeto na pasta `htdocs` do XAMPP.
5. Acesse o projeto pelo navegador através do localhost.
6. Cadastre um produto pelo formulário.
7. Utilize o **MySQL Workbench** para verificar se o produto foi inserido corretamente no banco de dados.

## Finalidade

Este projeto foi desenvolvido como atividade prática para exercitar conceitos de **PHP, formulários, validação de dados e integração com banco de dados MySQL**.
