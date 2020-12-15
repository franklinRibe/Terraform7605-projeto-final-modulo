## Utilizando o módulo

Foram criados três módulos específicos:

# gcp-network

Cria a VPC a sub-rede e as regras de firewall:

# gcp-instance-template

Cria um template para subir um grupo de instância

# gcp-instance-group 

Cria um grupo baseado no template acima que instancia máquinas em zonas distintas e configura um auto-escaler 

# gcp-load-balancer

Cria um load balancer para o grupo de instâncias criado acima e de aceso externo as máquinas


