# AWS - Infraestrutura global

AWS organiza a infraestrutura em camadas geográficas:

- **Regiões**: onde você escolhe “rodar” recursos (ex.: `sa-east-1`, `us-east-1`).
- **Availability Zones (AZs)**: datacenters separados dentro de uma mesma região.
- **Edge locations**: pontos de presença para reduzir latência (ex.: CloudFront).

## Por que isso importa

- **Disponibilidade**: distribuir entre AZs reduz impacto de falhas locais.
- **Latência**: escolha a região mais próxima do usuário/sistemas dependentes.
- **Resiliência**: multi-AZ e (quando necessário) multi-região.

## Relacionado

- [[AWS - O que é]]
- [[AWS - Como funciona]]
- [[AWS VPC]] (subnets por AZ)
- [[AWS EC2]] / [[AWS RDS]] (implantações multi-AZ)
- [[AWS CloudFront]] (edge)
- [[AWS Route 53]] (DNS e roteamento)

