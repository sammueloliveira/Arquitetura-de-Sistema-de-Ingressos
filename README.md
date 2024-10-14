# arquitetura-sistema-ingressos
## Componentes

1. **Frontend**: Interface em React/Angular para navegação e compra de ingressos.
2. **API de Autenticação**: Serviço em .NET/C# gerenciando login e registro com JWT.
3. **Gerenciador de Ingressos**: Controla disponibilidade e vendas.
4. **Banco de Dados**: PostgreSQL/MongoDB para armazenar dados de usuários e eventos.
5. **Sistema de Fila**: RabbitMQ/Redis para gerenciar requisições de compra.
6. **Cache**: Redis/Memcached para melhorar performance.
7. **Notificações**: Firebase/SendGrid para confirmações e lembretes.

## Fluxo
Usuários se autenticam, compram ingressos e recebem notificações de confirmação.
