---
title: "Planos"
excerpt: ""
---
Os **Planos** podem ser descritos como templates pré-definidos de assinaturas, o que facilita a criação de uma nova assinatura para um cliente. 

Para realizar um plano (`plan`) são obrigatórios os dados abaixo: 

`Name` (Nome do plano);
`Description` (Descrição do plano);
`Itens` (Itens do plano);
`Interval` (Tipo de intervalo: ano, mês ou semana);
`Interval_Count` (Espaçamento entre os intervalos);
`Payment_Methods` (Meios de pagamento aceitos);
`Start_At` (Data de início);
`Billing_Type` (Tipo de cobrança: pré-paga, pós-paga ou dia exato);
`Installments` (Parcelamento);
`Cycles` (Número de ciclos: duração do plano).
[block:callout]
{
  "type": "info",
  "body": "Todo plano possui um identificador como este: `plan_l0y1gJpfwSr0K8gL`.\nSe você enviar este `id` na hora de criar uma assinatura, ela será configurada automaticamente com todas as informações deste plano!",
  "title": "Identificador do plano"
}
[/block]

[block:callout]
{
  "type": "warning",
  "title": "Atenção",
  "body": "Ao alterar um plano você **não** altera automaticamente as assinaturas vinculadas a ele.\nPara isso você deve listar as assinaturas criadas a partir do plano e atualizá-las uma a uma."
}
[/block]