# AWS VPC + EC2 + SSH Lab

## Objetivo

Criar uma infraestrutura básica na AWS utilizando recursos do Free Tier, incluindo rede personalizada, instância EC2 e acesso remoto via SSH.

## Tecnologias Utilizadas

- AWS VPC
- Amazon EC2
- Security Groups
- Internet Gateway
- Route Tables
- Linux (Amazon Linux 2023)
- SSH
- WSL (Windows Subsystem for Linux)

## Arquitetura

Internet 
 │
 ▼
Internet Gateway 
 │
 ▼
VPC (10.0.0.0/16) 
 │
 ▼
Public Subnet (10.0.1.0/24) 
 │
 ▼
EC2 Amazon Linux 2023

## Etapas Realizadas

1. Criação da VPC personalizada.
2. Criação da subnet pública.
3. Configuração do Internet Gateway.
4. Configuração da Route Table.
5. Criação do Security Group para SSH.
6. Lançamento da instância EC2.
7. Conexão remota utilizando chave PEM e SSH.

## Evidências

## VPC

![VPC](vpc-lab.png)

## Public Subnet

![Public Subnet](public-subnet.png)

## Internet Gateway

![Internet Gateway](internet-gateway.png)

## Route Table

![Route Table](route-table.png)

## Security Group

![Security Group](sg-lab.png)

## EC2 Running

![EC2](ec2-executando.png)

## Acesso SSH

![SSH](acesso-ssh.png)

## Aprendizados

- Criação de redes virtuais na AWS.
- Configuração de conectividade com Internet Gateway.
- Associação de subnets e rotas.
- Configuração de Security Groups.
- Gerenciamento de instâncias EC2.
- Acesso remoto via SSH utilizando chaves PEM.
- Utilização do WSL para administração Linux.

## Resultado

Infraestrutura criada com sucesso utilizando recursos do AWS Free Tier e acesso SSH validado em ambiente Linux.
