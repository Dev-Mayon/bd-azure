#  Configurando uma Instância de Banco de Dados no Microsoft Azure

Este repositório documenta a criação de uma instância gerenciada de banco de dados SQL no Microsoft Azure, como parte do laboratório prático da plataforma DIO.

---

##  Objetivo

Praticar o provisionamento de uma instância SQL no Azure, configurando:
- Nome do servidor
- Usuário e senha
- Políticas de firewall
- Conexão e gerenciamento pelo painel

---

## 🛠️ Etapas da Configuração

### 1. Acesso ao Portal Azure
- Acesse [portal.azure.com](https://portal.azure.com)
- Faça login com sua conta Microsoft

### 2. Criação da Instância SQL
- Vá até **“Banco de Dados SQL”**
- Clique em **“Criar”**
- Preencha os campos:
  - **Nome do banco**: `meu-banco-sql`
  - **Servidor**: criar novo servidor com nome único
  - **Usuário** e **senha fortes**
  - Escolha a região e plano gratuitos 

### 3. Configuração do Servidor
- Habilite o acesso ao IP do seu computador atual (regra de firewall)
- Mantenha as portas padrão para SQL Server (1433)
- Revise e crie a instância

### 4. Acompanhamento
- Após criado, acesse o painel da instância
- Visualize uso de CPU, conexões, dados e métricas

---

## O que aprendi

- Criar e configurar um banco SQL na nuvem
- Utilizar o Azure para gerenciamento seguro
- Ajustar regras de acesso e firewall
- Utilizar boas práticas de documentação técnica

---



## Conclusão

Este laboratório permitiu consolidar a prática em serviços de nuvem, essencial para profissionais que desejam trabalhar com DevOps, desenvolvimento web e soluções escaláveis.

> 🧪 Projeto criado como parte do curso “Tipos de Serviço de Nuvem – DIO”

