# Comandos Básicos

### Iniciando um Switch Extreme

Caso seja a primeira vez iniciando o switch, as credenciais de entrada serão:

User: admin

Senha:

Obs: A senha vem em branco por padrão, sendo assim apenas aperte ENTER.

### Para verificar informações Básicas do Switch (Arquivo de onfiguração selecionado, uptime, horário)

show switch

### Exibir configuração

show configuration

### Criar VLAN

create vlan "nomevlan"

## Incluir porta na VLAN (Exemplo porta 1)
configure vlan "nomevlan" add ports 1 untagged
