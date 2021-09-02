# tfc-vault-local

## Vault operations
Unseal Key: OF7oIcMhxSAFMVSagPgqtMrQK1X3fyRzgPjNAbxECVI=<br />
Root Token: s.a2MZGPPyYKf4yOIJoK2jxzeb<br />

export VAULT_ADDR="http://127.0.0.1:8200"<br />
export VAULT_TOKEN="s.a2MZGPPyYKf4yOIJoK2jxzeb"<br />

vault server -dev<br />
vault status<br />
http://localhost:8200/ui<br />

vault list auth/paymentservices/pstest/role<br />

## Terraform cli
terraform init<br />
terraform fmt<br >
terraform plan<br />
terraform apply -auto-approve<br />
terraform destroy<br />

## Generate a self-signed certificate 
openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem<br />

## Futher reading
https://www.terraform.io/docs/language/modules/develop/composition.html#conditional-creation-of-objects<br />