# Flix App

Interface web desenvolvida com Streamlit para consumo da Flix API. Permite gerenciar filmes, atores, gêneros e avaliações através de uma interface visual simples e intuitiva.

## 🚀 Tecnologias

- Python 3.x
- Streamlit 1.x
- Pandas
- Plotly
- Requests
- Streamlit AgGrid

## ✅ Funcionalidades

- Autenticação via JWT integrada com a Flix API
- Dashboard com estatísticas de filmes e avaliações (gráfico de pizza por gênero, totais e média de estrelas)
- Cadastro e listagem de Gêneros
- Cadastro e listagem de Atores/Atrizes com nome, data de nascimento e nacionalidade
- Cadastro e listagem de Filmes com título, gênero, elenco, data de lançamento e resumo
- Cadastro e listagem de Avaliações com estrelas (0 a 5) e comentário

## 🔧 Como rodar o projeto localmente

Pré-requisitos: Python 3.x instalado e a Flix API em execução.

**1. Clone o repositório**
```bash
git clone https://github.com/seu-usuario/flix_app.git
cd flix_app
```

**2. Crie e ative o ambiente virtual**
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

**3. Instale as dependências**
```bash
pip install -r requirements.txt
```

**4. Inicie a aplicação**
```bash
streamlit run app.py
```
Acesse http://localhost:8501 no navegador.

## 🔐 Autenticação
O app utiliza autenticação JWT consumida diretamente da Flix API. Ao iniciar, o usuário é redirecionado para a tela de login e, após autenticado, tem acesso a todas as funcionalidades do sistema.

## 📁 Estrutura do Projeto
flix_app/
├── actors/       # Gestão de atores/atrizes
├── genres/       # Gestão de gêneros
├── movies/       # Gestão de filmes e estatísticas
├── reviews/      # Avaliações de filmes
├── home/         # Dashboard com estatísticas
├── login/        # Autenticação e logout
├── api/          # Serviço de autenticação com a API
├── app.py        # Ponto de entrada da aplicação
└── requirements.txt

👨‍💻 Autor
Leonardo — [LinkedIn](https://www.linkedin.com/in/leonardoalmeida-/) · [GitHub](https://github.com/LeonardoAlmeidaGit)
