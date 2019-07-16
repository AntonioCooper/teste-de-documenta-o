---
title: "Assinaturas"
excerpt: ""
---
A **Assinatura** é a recorrência em si. Ela possibilita que você cobre os seus clientes com intervalos pré determinados, sem que seja necessário criar essa regra de negócio do seu lado. 

Desenvolvemos essa funcionalidade pensando nos mais diversos estilos de recorrência do mercado, desde academias até a clubes de assinatura!

Para realizar uma assinatura (`subscription`) são obrigatórios os dados abaixo: 

`Itens` (Itens da assinatura);
`Customer` (Dados do comprador);
`Interval` (Tipo de intervalo: ano, mês ou semana);
`Interval_Count` (Espaçamento entre os intervalos);
`Payment_Method` (Meio de pagamento);
`Card` ou `Boleto` (Dados do pagamento);
`Start_At` (Data de início);
`Billing_Type` (Tipo de cobrança: pré-paga, pós-paga ou dia exato);
`Installments` (Parcelamento);
`Cycles` (Número de ciclos: duração da assinatura).


[block:callout]
{
  "type": "info",
  "title": "Duração do ciclo",
  "body": "A duração de um ciclo compreende o tipo da cobrança e o intervalo que será cobrada\n        Ex: \n              `Interval`: Semana, mês, ano ...\n              `Interval_Count`: 1, 2, 3, 4, 5 ... \nIsso quer dizer que se for selecionado *mês* e 3, a cobrança será feita a cada 3 meses (trimestral)."
}
[/block]

[block:callout]
{
  "type": "warning",
  "title": "Atenção",
  "body": "Se não for selecionado o número de ciclos, automaticamente será entendido como uma assinatura com duração infinita."
}
[/block]
  

## [**Funcionalidades relacionadas a assinatura**]()
[block:parameters]
{
  "data": {
    "0-0": "**1)** [Criar assinaturas pré-pagas]()\nGeralmente utilizado por negócios cujo o valor da assinatura não varia com o consumo, como por exemplo academias, planos de saúde, etc.",
    "1-0": "**2)** [Criar assinaturas pós-pagas]()\nGeralmente utilizado por negócios cujo valor da assinatura varia com o consumo, como por exemplo assinaturas de telefonia pós-pagas.",
    "2-0": "**3)** [Criar assinaturas com cobrança em um dia específico do mês]()\nNesta opção a assinatura é cobrada em dias pré-definidos, como por exemplo todo dia 10 do mês.",
    "3-0": "**4)** [Aplicar descontos para um cliente em um mês ou período específico]()\nNesta opção é possível dar descontos em determinados períodos, com por exemplo um desconto nos três primeiros meses.",
    "4-0": "**5)** [Pular uma cobrança]()\nNesta opção é possível não cobrar o consumidor em determinados ciclos.",
    "5-0": "**6)** [Criar um *setup* que gera um pedido no momento em que a assinatura é criada.]()\nNesta opção é possível criar um pedido avulso no momento em que a assinatura é gerada, como por exemplo a taxa de matrícula de uma academia.",
    "6-0": "**7)** [Assinaturas podem conter itens temporários]()\nNesta opção é possível incluir itens na assinatura que durarão apenas um período específico, como por exemplo um programa pay-per-view de uma assinatura de TV."
  },
  "cols": 1,
  "rows": 7
}
[/block]

[block:api-header]
{
  "title": ""
}
[/block]