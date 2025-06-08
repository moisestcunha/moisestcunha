# 📊 Portfólio Moisés Cunha 

Bem-vindo ao meu portfólio! Aqui você encontrará projetos práticos envolvendo **Power BI, SQL, Python e RPA**, demonstrando minhas habilidades em análise de dados e automação.

## 📌 Sobre Mim
Sou um **Analista de Dados** apaixonado por transformar dados em insights estratégicos. Tenho experiência com:
- 📊 **Power BI** para criação de dashboards interativos
- 📂 **SQL** para manipulação e análise de dados
- 🐍 **Python** para análise de dados e automação
- 🤖 **RPA** (Robotic Process Automation) para otimizar processos repetitivos

📩 **Contato:** [www.linkedin.com/in/moises-cunha](#) | [moisestcunha](#) | [mtiago_jc@hotmail.com](#)

---

## 📁 Projetos
Aqui estão alguns dos projetos disponíveis neste repositório:

### 🚀 1. Dashboard de Vendas no Power BI
📌 **Descrição:** Desenvolvimento de um dashboard interativo para análise de vendas. Utilizando ETL para o tratamentos dos dados.
usando medida DAX em nível avançado.
🔗 [Acesse o projeto](https://app.powerbi.com/links/_lgamaSAzL?ctid=c99f1f25-d23f-49c9-99df-6d6f43f94016&pbi_source=linkShare)

### 📊 2. Análise de Montadoras 
📌 **Descrição:** Utilização de consultas SQL para extrair insights valiosos de uma base de dados. Elevando a agilidade da informação em tempo real para o usuário.

-- Consulta para obter o número total de veículos vendidos por cada montadora no último ano
SELECT
    montadora,
    COUNT(veiculo_id) AS total_veiculos_vendidos
FROM
    vendas
WHERE
    data_venda BETWEEN DATEADD(year, -1, GETDATE()) AND GETDATE()
GROUP BY
    montadora
ORDER BY
    total_veiculos_vendidos DESC;

🔗 [Acesse o projeto](https://app.powerbi.com/links/WTZLK-2xkv?ctid=c99f1f25-d23f-49c9-99df-6d6f43f94016&pbi_source=linkShare)

### 🤖 3. Projeto de Ponta a Ponta em Dados
📌 **Descrição:** Buscando os dados na API com Python;
Tratando os dados com SQL no ambiente BigQuery;
Modelando com DAX avançada no Power BI;
Criando background no Figma;
Aprimorando com Analises Estatísticas;
Automatização com Power Automate;
Integração com IA;
🔗 [Acesse o projeto](https://app.powerbi.com/links/1ZSpxWsy4c?ctid=c99f1f25-d23f-49c9-99df-6d6f43f94016&pbi_source=linkShare)

### 📈 4. Análise de Dados com Python
📌 **Descrição:** Explorando dados utilizando Pandas conectando na Big Query;
ETL no SQL Server e modelagem no Power BI
🔗 [Acesse o projeto](https://app.powerbi.com/links/3bGgjCN7Ur?ctid=c99f1f25-d23f-49c9-99df-6d6f43f94016&pbi_source=linkShare&bookmarkGuid=611ff75b-acb3-42c5-aef3-35dadbdeca3c)

### 📈 5. Análise de Cancelamento
📌 **Descrição:** Tratamento de BD, análise da taxa de cancelamento e ações para melhorar diminuindo;
ETL e Análise via Python
 [Acesse o projeto](https://github.com/moisestcunha/Portif-lio/blob/main/Analise%20de%20Cancelamento)
---

## 🛠️ Tecnologias Utilizadas
- **Power BI** 📊
- **SQL (MySQL, PostgreSQL, SQL Server)** 🗄️
- **Python (Pandas, NumPy, Matplotlib, Seaborn, OpenPyXL)** 🐍
- **RPA (UiPath, Selenium, PyAutoGUI)** 🤖

---

## 📬 Contato
Se quiser bater um papo sobre análise de dados, fique à vontade para me chamar!
📩 [mtiago_jc@hotmail.com](#) | 🌐 [www.linkedin.com/in/moises-cunha](#) 

---
🚀 *Este portfólio está em constante atualização. Fique à vontade para explorar!*

