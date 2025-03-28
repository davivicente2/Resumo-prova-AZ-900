# Resumo do Lab  
# Resumo da atividade do curso de preparo para prova AZ-900 Certification

## Nuvem Pública  
### - Vem de provedoras como AWS e Azure  
### - Facilidade de expansão, serviços com fácil acesso, custo por uso  

## Nuvem Privada  
### - É localizada fisicamente dentro da empresa  
### - A empresa tem controle total de dados, recursos e segurança  

## Nuvem Híbrida  
### - É localizada tanto localmente quanto por provedoras  
### - Maior flexibilidade e gerenciamento de dados, custo e equipamentos  

# CapEx e OpEx  
## Despesas Operacionais  

## CapEx: Gasto em infraestrutura  
### - As despesas reduzem com o decorrer do tempo (basicamente tem um custo alto para instalação, mas a manutenção é mais barata)  

## OpEx: Gasto sob demanda  
### - As despesas são constantes, onde tudo que for usado será cobrado  

# Beneficios da nuvem:
### 	Sob demanda, ou seja pague somente o que usar.
### 	Alta disponibilidade.
### 	Escalabilidade e elasticidade

## (S.L.A.):
### 	Em caso de falha, gera-se credito para compensar a falha.
### 	Indisponiblidade de serviço
### 	Varios niveis onde é fornecido vairos niveis onde retrata o tempo medio que um serviço pode ficar fora do ar.
### 	Irá se fornecido informações sobre status geral (em caso de ser um problema que afete uma grande area: regional, geral outros), e meios de contornar o problema se possivel.

## Escalabilidade:
### 	Ajustar a capaciade do ambiente para atender demanda.	
### 	Dividido em escalamento vertical e horizontal.
	
## Elasticidade:
### 	Pode dimencionar o ambiente a partir da demanda (quantidade de acessos), aumentando e diminuindo de acordo com o fluxo de acessos.

## Confiabilidade:
### 	Divisão regional, proporciona maior segurança em casos catastroficos, one é possivel ter serviços em multiplas regioes onde em caso de falha regional, serviços em outras regioes não são afetados.
### 	Previsibilidade.

## Segurança
### 	Oferece multiplas ferramentas para auxiliar no mantimento da segurança de serviços.
### 	Implantação parte do usuario (cliente, TI, empresa, ...), a microsoft só fornece as ferramentas.

## Governaça
###	 Politicas e regras para gerirservisços e a rede.
	
## Gerenciabilidade
### 	Facilidade de uso.
### 	Pocibilidade de uso de codigos de automatização

# Modelos de Serviço em Nuvem  

## IaaS (Infraestrutura como Serviço)  
Ambiente onde é gerido o bruto, como personalização do servidor, firewalls e manutenção.  
- Serviço de nuvem mais flexível (é possível configurar e gerenciar o hardware necessário).  

## PaaS (Plataforma como Serviço)  
Ambiente onde apenas os serviços (ex: banco de dados, sistema operacional) são gerenciados, sem foco na infraestrutura.  
- Focado no gerenciamento de aplicativos (a gestão da plataforma é responsabilidade do provedor de nuvem).  

## SaaS (Software como Serviço)  
Ambiente onde os aplicativos e softwares hospedados (Office, Teams, entre outros) são gerenciados, incluindo suas licenças.  
- Modelo de pagamento sob demanda (os usuários pagam pelo software utilizado em um modelo de assinatura).  

# Modelo de Responsabilidade Compartilhada  

## Responsabilidades  

- **Local:** Responsável por tudo.  
- **IaaS:** Hosts físicos, rede física e datacenter físico são responsabilidades do fornecedor.  
- **PaaS:** Mantém as responsabilidades do IaaS, adicionando a gestão do sistema operacional ao provedor e compartilhando a gestão de aplicativos, controle de rede e infraestrutura de identidade e diretório.  
- **SaaS:** Mantém as responsabilidades do IaaS e do PaaS, sendo que apenas a infraestrutura de identidade e diretório é compartilhada.  
