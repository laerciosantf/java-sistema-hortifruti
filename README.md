# HortiSystem
- Sistema web simples em fase de criação. Tal sistema terá o back-end em Java mais o framework Spring MVC e o front-end com HTML5, CSS3, JavaScript e Bootstrap 4. Para o banco de dados será utilizado o MySQL mais o framework Hibernate.

- O HortiSystem deverá possibilitar o acesso de 3 usuários diferentes: caixa, gerente e administrador.

## Funcionalidades que serão vinculadas a cada usuário
### 1. Caixa
* Registrar venda
* Incluir produtos numa venda com diversos outros produtos
* Calcular o valor do produto por unidade

### 2. Gerente
* Cadastrar produtos utilizando nome, descrição, quantidade de entrada, unidade de medida e valor por unidade
* Controlar a validade dos produtos cadastrados
* Gerar relatório de produtos vencidos
* Ser notificado quando faltar pelo menos 7 dias para um produto vencer
* Relacionar produto a uma imagem
* Disponibilizar promoção num determinado período de tempo
* Dar descontos em produtos utilizando porcentagem
* Informar quantidade mínima de compra para receber desconto
* Gerar relatório de vendas diárias
* Gerar relatório de estoque atual
* Ser notificado quando o estoque de um produto estiver baixo
* Informar por produto a quantidade considerada baixa em estoque

### 3. Administrador
* Cadastrar perfil de gerente ou caixa no sistema

## Peculiaridades
* Os operadores dos caixas serão pessoas de mais idade, com idades que variam entre 50 e 70 anos, e com pouco conhecimento de informática
* Os gerentes serão pessoas mais novas, com idades que variam entre 30 e 50 anos, e com pouco conhecimento de informática
* Não haverão usuários externos. Nesse caso, um controle mínimo de usuário por funcionalidade deve ser implementado
