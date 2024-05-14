# Placas da aviônica para o foguete Lovelace-1KM

Nesse repositório temos os arquivos das placas que farão parte da aviônica do foguete Lovelace de 1km da Cactus Rockets Design.

### Descrição

Temos duas placas principais para esta aviônica:
- Placa de Processamento
- Placa de Acionamento

A placa de processamento é responsável pelo processamento dos dados dos módulos, armazenamento desses dados e telemetria. A placa de acionamento possui o circuito necessário para a correta ativação do Skib.

OBS.: Os arquivos das placas podems ser abertos por meio software Eagle da Autodesk.

### Esquemáticos e layouts

### Conexões entre placas

### Funcionamento

A placa de processamento contém um switch de ativação do sistema. No momento que o switch é pressionado, o sistema liga e faz a leitura dos módulos. Após cada leitura, ele armazena esses valores no microSD e envia esses dados via telemetria.

No momento que a placa de processamento detectar uma queda, ela envia um sinal para a placa de acionamento para que a mesma ative o Skib da parte de recuperação.