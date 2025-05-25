# Resumo sobre Microsoft Azure, Tecnologias Cloud e Aplicações

## 💻 Introdução

Durante o desenvolvimento deste laboratório prático, tive a oportunidade de explorar e entender os principais conceitos relacionados à **computação em nuvem** utilizando a plataforma **Microsoft Azure**. Este resumo contém os aprendizados obtidos ao longo das atividades realizadas.

## ☁️ O que é Microsoft Azure?

O **Microsoft Azure** é uma plataforma de computação em nuvem oferecida pela Microsoft, que disponibiliza uma ampla gama de serviços para construir, implantar e gerenciar aplicativos e serviços por meio de data centers distribuídos globalmente.

## 🧠 Conceitos Aprendidos

### 1. **Computação em Nuvem (Cloud Computing)**

- Compreensão dos três principais modelos:
  - **IaaS (Infrastructure as a Service)** – Ex: Máquinas virtuais no Azure.
  - **PaaS (Platform as a Service)** – Ex: Azure App Service.
  - **SaaS (Software as a Service)** – Ex: Microsoft 365.

### 2. **Serviços do Azure Utilizados**

- **Azure Portal**
- **Azure Virtual Machines (VMs)**
- **Azure App Service**
- **Azure SQL Database**
- **Azure Blob Storage**
- **Azure Functions**
- **Azure Resource Groups**
- **Azure Monitor**

### 3. **Conceitos de Segurança e Governança**

- **Azure Active Directory (Azure AD)**
- **Role-Based Access Control (RBAC)**
- **Políticas do Azure**
- **Tags e Naming Convention**

### 4. **Deploy e Monitoramento**

- Deploys automatizados via GitHub ou Azure DevOps.
- Dashboards personalizados no Azure Monitor.
- Alertas e logs para identificação de falhas.

### 5. **Aplicações Práticas**

- Aplicação web no Azure App Service.
- Integração com Azure SQL Database.
- Uso de Blob Storage e Azure Functions.

## ✅ Conclusão

Explorar a plataforma Microsoft Azure me permitiu entender na prática como a nuvem pode ser utilizada para tornar o desenvolvimento e a manutenção de aplicações mais eficiente, escalável e segura.

## 🚀 Como rodar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/azure-lab.git
   cd azure-lab
   ```

2. Instale as dependências:
   ```bash
   cd api
   npm install
   ```

3. Execute localmente:
   ```bash
   node index.js
   ```

A aplicação rodará localmente em `http://localhost:3000`.

## ☁️ Deploy no Azure via GitHub Actions

### Requisitos

- Conta no [Azure](https://portal.azure.com).
- Criar um App Service no portal.
- Criar um *Publish Profile* e adicionar como **Secret** no GitHub:
  - Nome do secret: `AZURE_WEBAPP_PUBLISH_PROFILE`.

Push no `main` = deploy automático 🚀
