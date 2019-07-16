---
title: "Esquemas de precificação dos itens"
excerpt: ""
---
A Nova API foi projetada para atender diferentes modelos de recorrência, como academias, escolas, operadoras de telefonia, clubes de assinatura, entre outros. 

Porém, cada um desses mercados tem diferentes tipos de precificações para seus produtos e serviços.

Pensando nisso, montamos lógicas de precificação para itens de uma assinatura, sendo essa funcionalidade chamada `Price_Scheme`.

Os **Esquemas de Precificação** possíveis para os itens da assinatura estão apresentados abaixo, utilizando a unidade de medida "minuto" como exemplo:


* [**UNIT**]()

1 minuto - Custa R$1,00 

Se um cliente utilizar 100 minutos o valor será R$100,00 (100 x R$1,00)

* [**PACKAGE**]()

De 0 a 10 minutos -  Custa R$50,00
De 11 a 50 minutos - Custa R$70,00 
De 51 a 100 minutos - Custa R$100,00
Cada minuto acima da última faixa custa R$0,90

Se um cliente utilizar 25 minutos o valor será R$70,00

* [**VOLUME**]()

1~10 - Cada minuto custa R$1,00
11~20 - Cada minuto custa R$0,90
21~50 - Cada minuto custa R$0,80
Cada minuto acima da última faixa custa R$0,70

Se um cliente utilizar 25 minutos o valor total será R$20,00 (25 x R$0,80)

* [**TIER**]()

1~10 - Cada minuto custa R$1,00
11~20 - Cada minuto custa R$0,90
21~50 - Cada minuto custa R$0,80
Cada minuto acima da última faixa custa R$0,70

Se um cliente utilizar 25 minutos o valor total será R$23,00 (10 x R$1,00 + 10 x R$0,90 + 5 x R$0,80)