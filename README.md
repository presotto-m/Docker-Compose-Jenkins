# Docker-Compose-Jenkins
Docker Compose para container docker com Jenkins

**Importante:** este é um trabalho em andamento.

**Ainda mais importante:** Se você realmente planeja usar isso, não se esqueça de editar os arquivos de configuração de acordo com suas necessidades (arquivos de serviço, arquivos de configuração YAML, etc.). Os arquivos de configuração fornecidos aqui são apenas arquivos genéricos.

Este script baixa os arquivos no diretório atual. Você poderia mudar isso.

Quaisquer sugestões e contribuições são bem-vindas.

# Como usar isso?

* docker-compose up -d

## Instalação completa

A instalação completa instalará o seguinte:

* Jenkins

# Acesso

* http://localhost:8080

* Senha Administrador: docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword
