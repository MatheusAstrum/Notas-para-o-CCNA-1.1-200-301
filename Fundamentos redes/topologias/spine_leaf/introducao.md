

# Introdução

É uma arquitetura de duas camadas. Esta arquitetura tem duas camadas, ou seja, a camada da coluna vertebral e a camada de leaf. A camada de coluna e a camada de leaf são conectadas na topologia completa da malha.
Esta arquitetura  supera as limitações da arquitetura hierarquica de três camadas. Cada switch de leaf é conectado a um interruptor de coluna em uma topologia de malha completa. A camada de folha contém os switches de acesso que se conectam aos servidores e fornecem uma conexão para usuários finais.

 
# Switchs de coluna e switchs de leaf
Os switchs de coluna são conectados com todos switchs de folha na topologia de malha, enquanto os switchs de de folha são conectados ao servidor e conectam os usuários finais. Os switches de coluna lidam com o tráfego de rede da camada 3; A arquitetura tradicional de três níveis tem três camadas e arquitetura espinha-folha tem duas camadas.


## Desenho da arquitetura da coluna vertebral

- Taxa de sobreassinatura:

É a taxa quando todos os dispositivos estão enviando dados ao mesmo tempo. Pode ser medido no tráfego que entra ou sai do data center e no tráfego entre os dispositivos no data center. É a razão entre a largura de banda d switches backbone e para a capacidade de servidores.

- Dimensionamento da leaf e da coluna vertebral:

As portas nos interruptores da coluna determinam o número máximo de switchs de leaf na topologia. O número de switchs de coluna é regido pela combinação da taxa de transferencia necessária entre os interruptores de folha, o número de caminhos redundantes e sua densidade de porta. Assim o número de spins e leafs deve ser considerado para evitar problemas na rede.

# Vantagens 

- Na arquitetura Spine-leaf, a velocidade fluxo de dados aumentou
- Essa arquitetura aumenta a largura de banda
- É uma arquitetura energeticamente eficiente
- O custo para esta arquitetura é baixo
- Melhora a escabilidade e redundância



