
# Como ocorre uma colisão

Uma colisão de dados ocorre quando dois ou mais dispositivos transmitem dados em um segmento de rede compartilhada ao mesmo, fazendo com que os pacotes de dados interfiram entre si. Isso leva uma corrupção dos dados, exigindo retransmissão.

As colisões acontecem principalmente em redes meio duplex, onde os dispositivos podem enviar ou receber dados a qualquer momento, mas não simultaneamente.

# Como ocorre uma colisão de dados?

Em redes Ethernet tradicionais usando um meio de comunicação compartilhado (hub) vários dispositivos competem pel oacesso ao mesmo canal de rede.

Quando dois dispositivos detectam o canal como ocioso e transmitem simultaneamente, seus sinais colidem, Os sinais sobrepostos tornam impossível para o receptor interpretar os dados, levando a uma colisão.

## Ambientes onde ocorrem colisões

### Redes topologia bus
    - Todos os dispositivos compartilham uma única espinha dorsal
    - Grandes chances de colisões quando o tráfego aumenta.

### Redes ethernet baseadas em hub

    - Hubs transmitem sinais para todos os dispositivos conectados.
    - Nenhuma inteligência para gerencia o tráfego de dados, aumentando a probabilidade de colisão.

### Ethernet meio duplex

    - Os dispositivos se revezam enviando dados, mas ainda podem transmitir ao mesmo tempo por engano.
