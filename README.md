# 🚀 Implementação do GLPI em Nuvem (AWS EC2 + Docker)

Este projeto demonstra a implantação de uma infraestrutura de gerenciamento de serviços de TI (ITSM) utilizando o GLPI, rodando em containers isolados dentro da nuvem AWS.

## 🛠️ Tecnologias Utilizadas
* **Provedor de Nuvem:** AWS (Amazon EC2 - Instância Ubuntu Server)
* **Conteinerização:** Docker & Docker Compose
* **Serviço de ITSM:** GLPI (Central de Ajuda e Inventário)
* **Banco de Dados:** MariaDB

## 📦 Arquitetura da Solução
A aplicação foi desenhada utilizando o conceito de infraestrutura imutável e containers, onde o serviço do GLPI e o banco de dados rodam de forma isolada, garantindo fácil manutenção, portabilidade e backups simplificados.

## 🚀 Como Executar este Projeto
1. Instale o Docker e o Docker Compose no seu servidor.
2. Clone este repositório.
3. Execute o comando: `sudo docker compose up -d`
4. Acesse via navegador através do IP público do servidor.

## 📊 Resultados do Laboratório
* Redução do tempo de deploy da aplicação de horas para minutos utilizando Docker.
* Ambiente preparado para auditorias e gerenciamento de inventário de ativos de TI.
