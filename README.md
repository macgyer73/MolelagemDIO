# MolelagemDIO
Para estudo de casos e melhoria modelagem Banco de Dados 
Estudo de Caso E-Commerce.

Modelo Proposto
<img src="https://github.com/macgyer73/MolelagemDIO/blob/main/Files/original.png" alt="Modelo E-Commerce Proposto">

# Alterações Propostas

•Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações 

• Pagamento – Pode ter cadastrado mais de uma forma depagamento

• Entrega – Possui status e código de rastreio

# Refinamento Proposto.
<img src="https://github.com/macgyer73/MolelagemDIO/blob/main/Files/refinado.png" alt="Modelo E-Commerce Refinado">

# Sobre as Alteraçoes Propostas.

Cliente PF e PJ - Criada as Entidades PJ e PF separadas, com relacionameo 1:1 - pois 1 Cliente só pode Ser de um tipo.

Pagamento - Mais Forma de Pagamento- Desafio Pagar com mais de um Cartão. Adicionado Entidade Pagamento Relacionado com Entedidade Cartão
Onde 1 Relacionamento com Pedido - 1:1 pois um Pedido só poder um Pagamento. e Relacionamento Pagamento com Cartão onde 1:N onde um Pagamento
poder ter varios cartões cadastrados.

Entrega adicionado a entidade Entrega - nela associada a Pedido 1:1 onde um Pedido pode ter somente 1 entrega, em entrega podemos armazenar, Status, 
Data da Entrega e codigo de rastreamento com base em um pedido.





