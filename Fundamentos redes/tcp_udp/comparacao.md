

# TCP e UDP

O TCP e UDP não protocolos parte de um modelo conceitual (OSI) que padroniza as funções de comunicação na computação divididas em 7 camadas.

- aplicação
- apresentação
- sessão
- transporte
- rede
- enlace
- fisico

TCP E UDP estão na camada de transporte que é responsável pela transferência eficiente, confiável e econômica dos dados entre a máquina de origem e a máquina de destino, independente do tipo, topologia ou configuração das redes físicas existentes entre elas, garantindo que ainda os dados cheguem sem erros e na sequência correta.

## UDP

É uma escolha adequada para fluxos de dados em tempo real, especialmente aqueles que admitem perda ou corrompimento de parte de seu conteúdo, tais como vídeos ou voz(voip)

## TCP

É sobre o qual se assentam a maioria das aplicações cibernética scomo o SSH, FTP, HTTP - portanto a WWW (World Wide Web). O protocolo de contorle de transmissão provê confiabilidade

O TCP preza pela confiabilidade agregando em seu ´´header´´ bits de controle de fluxo e recebimento.
 
Já o UDP dispensa esses bits de controle.

O TCP é orientado a conexão atráves de seu Acknowledgement e o UDP não possui orientação a conexão, uma vez que é criada a conexão há apenas envio direto de dados.
