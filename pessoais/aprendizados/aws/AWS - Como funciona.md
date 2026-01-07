# AWS - Como funciona

AWS expõe serviços por **APIs**. Você cria e configura recursos (ex.: instâncias, buckets, filas) dentro de uma **conta**, em uma **região**, com controle de acesso via **IAM**.

## Modelo mental

- **Conta**: limite administrativo e de billing.
- **Regiões / AZs**: onde os recursos rodam fisicamente.
- **IAM**: quem pode fazer o quê (usuários, roles, policies).
- **VPC**: rede lógica onde recursos “vivem”.
- **Observabilidade e auditoria**: logs/metrics/traces e trilha de ações.

## Relacionado

- [[AWS - Infraestrutura global]]
- [[AWS IAM]]
- [[AWS VPC]]
- [[AWS CloudWatch]]
- [[AWS CloudTrail]]
- [[AWS Organizations]]

