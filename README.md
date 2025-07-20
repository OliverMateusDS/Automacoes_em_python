<h1 align="center">📦 Automação com Python</h1>
<p align="center">Notebooks práticos para tornar suas rotinas mais eficientes com Python</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow" />
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

---

## ✨ Visão Geral

Bem-vindo ao repositório de **Automação Cotidiana com Python**!  
Aqui você encontra projetos que demonstram habilidades em:

- 🔄 Automação de tarefas repetitivas  
- 📈 Análise de dados  
- 🌐 Web scraping  
- 🗂 Organização de arquivos  
- 🧠 Integração com APIs e Banco de Dados

---

## 🚀 Projetos Disponíveis

### 1️⃣ Automação Financeira: Dólar, Ações e Notícias
<p align="center">
  <img src="https://user-images.githubusercontent.com/placeholder/financeiro.png" width="600px" alt="automação-financeira" />
</p>

📊 Automatiza a coleta diária das principais informações financeiras.  

**Funcionalidades:**
- Coleta a cotação do **dólar** dos últimos 7 dias via API.
- Baixa preços de fechamento das ações **PETR4, VALE3, ITUB4** via Yahoo Finance.
- Faz scraping de **notícias financeiras** via Google News RSS.
- Armazena tudo em banco de dados **SQLite**.
- Gera **gráficos interativos** com Matplotlib.
- Pronto para **agendamento automático diário (cron/Windows Task Scheduler).**

🔗 [Ver notebook](./Automacao_Financeira.ipynb)

---

### 2️⃣ Organização Automática de Arquivos
<p align="center">
  <img src="https://user-images.githubusercontent.com/placeholder/organizador.png" width="600px" alt="organizador-de-arquivos" />
</p>

🗂 Organiza automaticamente arquivos de uma pasta local por tipo.

**Funcionalidades:**
- Criação automática de **subpastas** por categoria: PDF, imagens, planilhas etc.
- Movimentação **segura** dos arquivos.
- Fácil de adaptar para:
  - Renomear arquivos
  - Remover duplicados
  - Log de movimentações

🔗 [Ver notebook](./Organizador_de_Arquivos.ipynb)

---

## 🛠️ Tecnologias Utilizadas

| Ferramenta | Descrição |
|------------|-----------|
| 🐍 Python  | Linguagem principal |
| 🧮 Pandas  | Manipulação de dados |
| 📊 Matplotlib | Visualização de dados |
| 🕸 BeautifulSoup | Web Scraping |
| 📡 Requests | Acesso a APIs e RSS |
| 💾 SQLite | Banco de dados leve local |

---

## 🧠 Próximos passos

- [ ] Agendamento com cron no Linux
- [ ] Envio automático de e-mail com relatórios
- [ ] Deploy em nuvem (Streamlit, Lambda, etc.)

---
