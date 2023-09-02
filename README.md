# E-commerce

Linguagens e frameworks  utilizados:

- Python
- JavaScript
- Html
- Css
- Django
- Bootstrap

Banco de dados modelos/tabelas:

- User: Modelo padrão do Django
- Customer: Relação com User
- Product
- Order: Relação com Customer
- OrderItem: Relação com Product
- ShippingAddress: Relação com Customer e Order


Formulario para cadastro de usuario utilizei o padrão do Django, validação desse formualrio tambem a padrão do django.

Utilização javascript:
- Pegar informação dos produto e quantidade e enviar para url update_item/ aonde eu fazia a validação no backend para atualizar a quantidade e o produto no carrinho
- Para processar a order do pedido de compra e eviar para url process_order/ aonde validei esse pedido no backend

Api Utilizadas:
- Utililizei a Api da Paypal para forma de pagamento

