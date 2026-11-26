
# Erros comuns

- CRC error
- Runts
- giants
- input error

## Error CRC


Ocorre quando um frame recebido falha com a checagem CRM, normalmente indicando que o frame esta corrompido durante a transmissão.

CRC é um erro da camada um se o CRC continuar crescendo, cheque os cabos, conectores ou tentar uma porta diferente


## Runts

Runt é o frame menor que o minimo do tamanho da Ethernet frame, menor que 64 bytes, causas do runts pode ser colisões na conexão half duples, duplex dismatch entre dispositivos, ou problemas do hardware.

## Giants

Giants é o frame Ethernet maior que o padrão MTU normalmente sendo 1,518 bytes.

pode ser causada por misconfiguration das configurações MTU
Mal funcionamento dos NICs
Jumbo frames não são suportados ou mismatched

## Input errors

É como um contador genérico que inclui vários tipos de recepção de erros.

