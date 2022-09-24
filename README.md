# Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE

Esquema refinado do projeto conceitual de banco de dados E-commerce.
Solução do desafio:
> Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações
    Foi criado como atributo na entidade Cliente. 
> Pagamento – Pode ter cadastrado mais de uma forma de pagamento
    Criado entidade Cadastro Cartões relacioanada a entidade Cliente, na qual cada cliente pode ter mais de um cartão. 
    O pedido poderá ter mais de uma forma de pagamento assim como mais de uma forma de pagamento poderá ser usada em um pedido.
> Entrega – Possui status e código de rastreio
    O pedido terá apenas um código de rastreio e um status, mas a entrega poderá ter mais de um pedido associado ao mesmo código de rastreio
