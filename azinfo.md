az ad sp create-for-rbac --role="Contributor" --scopes="/subscriptions/8d4847a9-69e0-421a-a34c-bdbe015475c7"

{
  "appId": "bd15a6a6-f3f1-4f51-ab36-94b52bcaaa92",
  "displayName": "azure-cli-2019-08-09-07-12-57",
  "name": "http://azure-cli-2019-08-09-07-12-57",
  "password": "cfaf2fd7-7d36-46e6-81ac-0f6dd3e47c95",
  "tenant": "6acd597a-76b5-4908-ab09-f0180c308d3e"


export ARM_CLIENT_ID=bd15a6a6-f3f1-4f51-ab36-94b52bcaaa92
export ARM_CLIENT_SECRET=cfaf2fd7-7d36-46e6-81ac-0f6dd3e47c95
export ARM_SUBSCRIPTION_ID=8d4847a9-69e0-421a-a34c-bdbe015475c7
export ARM_TENANT_ID=6acd597a-76b5-4908-ab09-f0180c308d3e
export ARM_SAS_TOKEN="?sv=2018-03-28&ss=b&srt=co&sp=rwdlac&se=2019-11-01T15:09:19Z&st=2019-08-30T07:09:19Z&spr=https&sig=DbEfdgtoq7UCARcRfPtW6%2Bkw4njRG8TO%2F9fa07wRfWY%3D"


export TF_VAR_client_id=${ARM_CLIENT_ID}
export TF_VAR_client_secret=${ARM_CLIENT_SECRET}
export TF_VAR_subscription_id=${ARM_SUBSCRIPTION_ID}
export TF_VAR_sas_token=${ARM_SAS_TOKEN}
SAS_Token

"?sv=2018-03-28&ss=b&srt=co&sp=rwdlac&se=2019-11-01T15:09:19Z&st=2019-08-30T07:09:19Z&spr=https&sig=DbEfdgtoq7UCARcRfPtW6%2Bkw4njRG8TO%2F9fa07wRfWY%3D"