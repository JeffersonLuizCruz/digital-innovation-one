## :page_with_curl: Sobre o projeto <a name="-sobre"/></a>

> Esse é um simples projeto com objetivo de colocar em prática o conceito de POO.

<h4> Como o sistema funciona:</h4>
O sistema recebe informação de entrada e os dados são gravados em formatado .csv
Exemplo de entrada:


#### :page_with_curl: Exemplo de entrada de dados <a name="-diagrama"/></a>
<h1 align="center">
    <img alt="Ecommerce" src="https://github.com/JeffersonLuizCruz/digital-innovation-one/blob/main/src/main/resources/template/01-scanner.png" />
</h1>

Saída do arquivo está configurado para o caminho:
```
"C:\temp\storage\user\user-efa1b253-7723-4cc3-ab9f-9ea27dabad84.csv"
```

#### :page_with_curl: Exemplo de entrada de dados <a name="-diagrama"/></a>
<h1 align="center">
    <img alt="Ecommerce" src="https://github.com/JeffersonLuizCruz/digital-innovation-one/blob/main/src/main/resources/template/02-storage.png" />
</h1>

## Caso de Uso - Registro de um Pedido

### O cliente seleciona um produto para adicionar ao carrinho de compras:
Quando um produto já existente no carrinho é selecionado, a quantidade deste produto no carrinho deve ser incrementada, caso contrário o produto é devolvido ao carrinho com quantidade 1.

### O sistema exibe o carrinho de compras:
As informações do carrinho de compras são: nome, quantidade e preço unitário de cada produto (não será dado desconto), o subtotal de cada item do carrinho, e o valor total do carrinho.

### O sistema informa a confirmação do pedido:
As informações da confirmação do pedido são: número, data e horário do pedido,valor total do pedido,bem como o tipo e estado do pagamento (Pendente). Caso o pagamento seja com boleto, informar a data de vencimento, e caso o pagamento seja com cartão, informar o número de parcelas.


## :page_with_curl: Diagrama de Classe <a name="-diagrama"/></a>
<h1 align="center">
    <img alt="Ecommerce" src="https://github.com/JeffersonLuizCruz/financial/blob/main/src/main/resources/tamplates/Classe%20UML3.png" />
</h1>

## Tecnologia:
- [x] Java 11<br>
- [x] Spring Boot 2.7.4<br>
- [x] Lombok<br>

## Construção do Projeto:
- [x] Criação de Interface Service (garantir baixo acoplamento)<br>
- [x] Persistencia dos dados em arquivo CSV<br>

