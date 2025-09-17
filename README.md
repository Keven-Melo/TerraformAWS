# Automatização de Infraestrutura com Terraform (IaC)

## Problema
Recriar ambientes (dev/staging/prod) manualmente na AWS gera inconsistências, erros e **drift**, podendo causar falhas em deploys de emergência.

## Solução
Trate a infraestrutura como código com **Terraform**. Recursos como **EC2**, **ECR** e **IAM Roles** são provisionados automaticamente, garantindo consistência e rastreabilidade.

## Ferramentas e Conceitos

- **Terraform:** `init`, `plan`, `apply`, `destroy`  
- **Backend remoto:** S3 para armazenar o estado (`state`)  
- **Recursos AWS gerenciados:** EC2, Security Groups, IAM Roles, ECR  
- **Provisionamento declarativo:** configuração de instâncias, regras de segurança e repositórios de container  
- **Outputs e variables:** integração e parametrização de recursos  
