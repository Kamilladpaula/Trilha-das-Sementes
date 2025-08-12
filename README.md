# <h2> **🌱 Trilha das Sementes** <h2>
Plataforma digital para rastreamento, análise e gestão de sementes crioulas, integrando coleta de dados em campo, banco de dados relacional e visualização interativa para apoiar o PAA-Sementes.


## 🎯 Pitch Rápido
O **Trilha das Sementes** é uma plataforma digital colaborativa para mapear, conectar e fortalecer redes sociotécnicas de sementes crioulas, acompanhando o fluxo das sementes desde a produção até o uso final.  
A solução integra coleta de dados em campo via aplicativo mobile, armazenamento seguro, visualização em mapas e dashboards interativos, apoiando a gestão e avaliação do Programa de Aquisição de Alimentos – Modalidade Compra e Doação Simultânea (PAA-Sementes).

---

## 📌 Objetivo
Criar um sistema informatizado que:
- Rastreie o fluxo das sementes doadas.
- Facilite a coleta de dados em campo, com georreferenciamento.
- Disponibilize mapas e painéis interativos para análise.
- Apoie decisões estratégicas para políticas públicas de sementes crioulas.

---

## 🛠 Tecnologias Utilizadas

### **1. Aplicativo Mobile (App Trilha das Sementes)**
- **Linguagem**: Python  
- **Framework**: Kivy (UI e desenvolvimento multiplataforma)  
- **Funcionalidades**: leitura de QR Code, cadastro de fornecedores e recebedores, geolocalização, formulários auto-respondentes.
- **Plataforma**: Android (Google Play Store).  

---

### **2. Coleta de Dados**
- Plataforma **ODK** (Open Data Kit).
- Ferramentas: ODK Build, ODK Collect, ODK Central.
- Banco de dados no ODK Central: **PostgreSQL**.
- Sincronização automática entre o aplicativo mobile e o servidor web.

---

### **3. Backend**
- Banco de Dados: **PostgreSQL** (SGBDR – ACID).
- Linguagens: Python + SQL.
- Bibliotecas Python: psycopg2 (integração PostgreSQL).
- Framework Web: **Flask** (rotas, views, APIs).
- Integração com APIs externas e outros bancos (SQL Server/MySQL).
- Containerização: **Docker**.

---

### **4. Frontend / Visualização de Dados**
- Tecnologias: HTML, CSS, JavaScript.
- Dashboard: Python + **Dash** (open source).
- Bibliotecas de visualização: Plotly, Matplotlib, Seaborn.
- Mapa interativo: Folium / geolocalização no Dash.

---

### **5. Análise de Dados**
- Ferramentas: Python (Pandas, NumPy) e R.
- Análises: descritivas, inferenciais, testes de hipóteses.
- Geração de relatórios e indicadores de desempenho.

---

### **6. Outras Ferramentas**
- Controle de versão: Git, GitHub.
- Desenvolvimento: VS Code.
- Geoprocessamento: QGIS, ArcGIS (mapeamento geoespacial).

---

## 📂 Estrutura do Projeto
- `/app_mobile/` – Código do aplicativo em Python/Kivy.
- `/odk/` – Formulários ODK, scripts de integração.
- `/backend/` – APIs Flask e conexões de banco.
- `/frontend/` – HTML, CSS, JS e layouts do dashboard.
- `/scripts_analise/` – Códigos Python e R para análise.
- `/docs/` – Documentação e manuais técnicos.

---

## 👩‍💻 Autoria
Desenvolvido por **Kamilla de Paula**, **Márcio Celestino** e equipe do projeto Trilha das Sementes – UnB/FUP.  
🔗 [LinkedIn](https://linkedin.com/in/kamilladepaula) | 📧 gest.kamilla@gmail.com
