

# Arquitetura de tier 2


É chamada também de modelo hieráquico de duas camadas ou modelo de núcleo desmontado. essa arquitetura é usada por pequenas empresas que não podem usar a arquitetura de 3 níveis, por que é uma solução cara. 


- camada de acesso: 
É composto por todas as LANs que estão conectadas ao switches.

- Camada de distribuição:
Essa camada tem um switch de várias camadas ao qual cada switch LAN é conectado

Caso um ponto caia, vários pontos vão cair



    Router
    |   |   |
    |   |   |
    |   |   |
    |   |   |
    |   |   |
    |   |   |
    S1  S2  S3

# Arquitetura ideal do tier 2

De vez dos switchs fazerem uma conexão direta com os pontos de acesso agora ambos os switchs fazem conexão com os switchs de distribuição para os endpoints.

- tem uma camada de distribuição e uma acesso.
- Mas tem menos número de falhas de ponto único.
- Arquitetura confiável do que o normal de 2 níveis.


