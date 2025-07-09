# 📊 Dashboard de Contratos de Projeto - Streamlit App

Este é um aplicativo web interativo desenvolvido em **Python** utilizando **Streamlit** para visualização de dados, **Pandas** para limpeza e tratamento de dados, e **SQLite** como banco de dados relacional. A autenticação de usuários e a modelagem do banco foram feitas com **SQLAlchemy**.

---

## 🔧 Tecnologias Utilizadas

- **Python 3.11+**
- **Streamlit** – Interface web interativa e rápida
- **Pandas** – Manipulação e limpeza de dados
- **SQLite** – Banco de dados leve e local
- **SQLAlchemy** – ORM para modelagem do banco e autenticação de usuários

---

## ⚙️ Funcionalidades

### 🧹 ETL (Extração, Transformação e Carga)
- Leitura de dados brutos
- Limpeza e tratamento com Pandas
- Armazenamento no banco SQLite

### 🔐 Autenticação de Usuários
- Sistema de login e criação de usuários
- Modelagem com SQLAlchemy
- Segurança e controle de acesso à aplicação

---

## 📈 Dashboard de Projetos

Na página principal do dashboard, você pode:

- **Filtrar por Setor da empresa**
- **Filtrar por Status do projeto**
- Visualizar:
  - **Total de projetos por mês**
  - **Gráfico de comparação entre orçamento e valores pagos**
  - **Gráfico de barras** com `Valor Orçado` vs `Valor Pago`

---

## 📊 Indicadores Estratégicos

Na aba de **Indicadores**, são exibidos os **6 principais KPIs**:

| Indicador         | Valor              |
|-------------------|--------------------|
| 🧭 Oportunidades  | 2.633              |
| 💰 Total Orçado   | R$ 10.489.500,00   |
| 📦 Projetos Fechados | 504            |
| ✅ Total Pago     | R$ 9.625.100,00    |
| 🔄 Em Andamento   | 331                |
| 💸 Total Desconto | R$ 864.400,00      |

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Python 3.11 ou superior
- pip

### Instale as dependências

```bash
pip install -r requirements.txt
```

```bash
streamlit run app.py
```

## Estrutura do Projeto

```bash
📦 projeto-analise-corporativa-completa
├── app.py
├── criar_admin.py
├── criar_conta.py
├── dashboard.py
├── data_loader.py
├── homepage.py
├── indicadores.py
├── LICENSE
├── main.py
├── models.py
├── README.md
├── requirements.txt
├── 📁 database/
│   └── dashboardauth.db
├── 📁 images/
```

## ✍️ Autor

- Desenvolvido por Guilherme Portugal – Analista de Dados / Desenvolvedor Python
- Entre em contato: guilherme.portugal.busi@gmail.com
