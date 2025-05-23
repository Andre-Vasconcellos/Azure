## Introdução

Aprendemos nesse tópico os conceitos básicos no ambiente azure e sobre como implanta-los em ambiente coorporativo, vimos que existem diversas possibilidades para implantação de acordo com o tipo de negocio embarcado, que dentro do ambiente podemos ajustar as necessidades de acordo com SLA(Service Level Agreement) necessário para o atendimento ao cliente e dependendo do nível de criticidade da atividade designada, seguem alguns tópico interessantes sobre o assunto em questão:


## Fundamentos do Azure

Microsoft Azure é a plataforma de computação em nuvem da Microsoft, oferecendo uma ampla gama de serviços para computação, armazenamento, redes, banco de dados, inteligência artificial e muito mais.

### Principais Conceitos:

- **Regiões e Zonas de Disponibilidade:** Azure está distribuído globalmente em regiões, cada uma contendo múltiplas zonas de disponibilidade para garantir resiliência.
- **Modelos de Serviço:**
  - IaaS (Infraestrutura como Serviço): ex. Azure VMs
  - PaaS (Plataforma como Serviço): ex. Azure App Services
  - SaaS (Software como Serviço): ex. Office 365
- **Recursos e Grupos de Recursos:** Recursos são serviços individuais (como VMs, bancos de dados), organizados em grupos de recursos.
- **Controle de Acesso:** Azure usa RBAC (Controle de Acesso Baseado em Funções) para gerenciar permissões.
- **Azure Resource Manager (ARM):** Mecanismo de implantação e gerenciamento de recursos.

## Serviços Comuns do Azure

### 1. Azure Virtual Machines (VM)

Servidores virtuais escaláveis na nuvem, com suporte para Windows, Linux e workloads personalizados.

### 2. Azure App Service

Hospedagem de aplicações web com escalonamento automático, SSL, e integração com GitHub/DevOps.

### 3. Azure Functions

Execução de código sem provisionar infraestrutura (serverless), ideal para tarefas automatizadas e integrações.

### 4. Azure Storage

Serviço de armazenamento escalável para blobs, arquivos, tabelas e filas.

### 5. Azure SQL Database

Banco de dados relacional como serviço (PaaS), com alta disponibilidade, backup automático e escalabilidade.

## Dicas e Truques

### 1. Economia de Custos

- Use Azure Cost Management para monitorar gastos
- Aplique reservas de instância e escalonamento automático
- Desligue recursos não utilizados com scripts

### 2. Ferramentas Úteis

- **Azure CLI:** Automatize tarefas de gerenciamento
- **Azure Portal:** Interface gráfica intuitiva para gerenciamento manual
- **Azure PowerShell:** Alternativa ao CLI com foco em administração Windows

### 3. Melhores Práticas

- Nomeie recursos com padrões consistentes
- Use tags para organização e cobrança
- Monitore recursos com Azure Monitor e Log Analytics

