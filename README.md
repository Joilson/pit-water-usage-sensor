### Pit Water Usage Sensor

 Projeto em arduino para monitorar o enchimento da caixa d' agua com uma bomba de poço artesiano, semi-artesiano ou  caipira.
 
#### Objetivo principal:

 Identificar o mais rápido possivel se a água do poço acabou, impedindo que a moto bomba se danifique. 

#### Demais Objetivos:

 Identificar quando uma boia eletrica é ligada automaticamente
 
***
### Fluxo

 - Quando a bóia automatica ligar, o programa aguarda alguns segundos até que identifique o fluxo de água
 - Se o fluxo de agua não for identificado, pode ser sinal de:
   - Falta de água no poço
   - Um buzzer começa e só para quando:
     - A bóia seja desligada manualemte 
     - O fluxo de água inicie.
 - Se o fluxo de água for identificado nenhum buzzer começa e o led verd acende até a bóia desligue

### Items necessários:

 - Sensor De Fluxo Vazão De Água 
 - Módulo Semáforo Led
 - Sensor De Tensão
 - Módulo Buzzer Ativo
 - Cabos Jumper
 - Placa Compatível Com Arduíno Uno R3

### Blibliotecas adicionais

 - EmonLib