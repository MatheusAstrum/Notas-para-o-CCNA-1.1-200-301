

# CSMA/CD 

é um protocolo usado em redes Ethernet para gerenciar o acesso ao canal compartilhado.


## Como funciona o CSMA/CD

- Um dispositivo escuta a rede
- Se o canal estiver ocioso, ele começa a transmitir
- Se uma colisão for detectada durante a transmissão, ela para de enviar
- O dispositivo envia um sinal de bloqueio para informar os outros sobre a colisão
- Todos os dispositivosperam por um tempo de retrocesso aleatória antes antes de tentar novamente.

## Efeitos das colisões de dados no desempenho da rede

- Aumento de latência as colisões requerem retransmissão de dados, causados atrasos na comunicação
- Congestionamento da rede colisões frequentes levam ao tráfego congestionado, reduzindo a taxa de transferência geral da rede.
- Utilização reduzida da largura da banda: os recursos de rede são desperdiçados na detectação de colisões e na retransmissão de pacotes corrompidos.
- Confiabilidade mais baixa: os usuários podem experimentar respostas atrasadas, transferências lentas de arquivos ou conexões caídas
- Sobrecarga do dispositivo: Os dispositivos gastam mais tempo monitorando e tentando novamente, usando o poder de processamento e a memória.

## Como detectar uma colisão de dados

- Analisadores de rede: ferramentas como wireshark podem detectar e registrar eventos de colisão e retransmissões.
- Alta taxa de colisão em switchs logs: Switches modernos podem registra estatísticas de colisão que os administradores de rede podem monitorar.
- Problemas de desempenho em redes baseadas em hub desaceralções frequentes, tempo limite ou perda de dados podem indicar problemas de colisão.
