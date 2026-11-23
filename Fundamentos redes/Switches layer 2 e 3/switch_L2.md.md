
# Switch Layer 2

Funciona na camada 2 que funciona com base no endereço MAC de um dispositivo.

## Aprendizagem 

O switch aprende o endereço MAC do dispositivo na porta de interruptor na qual recebe o quadro.

## Encaminhamento

O switch faz 2 tipos de encaminhamento de mensagens:
### Unicast

Envia o quadro para o destino somente quando ele tem uma entrada para endereço MAC de destino em sua tabela de endereço MAC.

### Unicast desconhecido

Quando um switch recebe um quadro unicast para um destino que o switch não tem entrada na sua tabela MAC, o switch simplesmente transmite o quadro através de todas as portas. Conhecido como flood.

## Filtragem

O quadro será encaminhado através dessa porta de switch apenas para a qual o switch já aprendeu o endereço MAC em sua tabela MAC.

## Evitação de loop

Para redundância, dois switchs são conectados um ao outro através de dois links que também podem resultar em loops da camada 2 esses loops são evitados comutando usando o protocolo STP.