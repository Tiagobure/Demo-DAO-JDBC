# Padrão de projeto DAO (Data Access Object)
---
## Ideia geral do padrão DAO: Para cada entidade, haverá um objeto responsável por fazer acesso a dados relacionado a esta entidade. Por exemplo:

- O Cliente: ClienteDao
- O Produto: ProdutoDao
- O Pedido: PedidoDao
### Cada DAO será definido por uma interface.
### A injeção de dependência pode ser feita por meio do padrão de projeto Factory
---
![Screenshot 2025-02-21 at 10-51-50 acesso-a-dados-com-jdbc pdf](https://github.com/user-attachments/assets/4155f45c-00a6-4efb-940c-d0a621819d57)
---
