# Modelo_bd
Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE

## Desenvolvimento do projeto

- Adição da conta CNPJ com chave primaria idConta e Codigo Atividade de valor unico e auto-incremento.
- Adição da conta CPF com chave primaria idCPF de valor unico e auto-incremento.
- As chaves de Cpf e Cnpj são adicionadas em cliente como chave estrangeira.
- Inserção do pagamento entre as entidades cliente e relação de produto/pedido. Quando o pedido for efetuado segue com o idPagamento.
- Entrega com idEntrega, status e codigo de rastreio mas apenas se produto estiver em estoque.
- Um cliente apenas pode fornecer ou CNPJ OU CPF na relação 1 para 1
- Um cliente pode fazer vários pagamentos na relação 1 para muitos.
- Um estoque pode fazer várias entregas na relação um para muitos.
