# 📡 IoT-Calc (Projeto de Estudo)

O **IoT-Calc** é uma aplicação web para análise e cálculo de dados geoespaciais provenientes de dispositivos IoT.  
O sistema processa e exibe informações de localização, permitindo rastreamento em tempo real com alta precisão.

---

## 🚀 Tecnologias Utilizadas

- **[Python](https://www.python.org/)** – Linguagem principal do backend  
- **[Django](https://www.djangoproject.com/)** – Framework web utilizado no servidor  
- **[Geopy](https://geopy.readthedocs.io/)** – Biblioteca para cálculos geoespaciais considerando a curvatura da Terra (modelo WGS-84)  
- **[Grunt](https://gruntjs.com/)** – Ferramenta para automação de tarefas no frontend  
- **[Heroku](https://www.heroku.com/)** – Plataforma utilizada para hospedagem do sistema  

---

## ⚙️ Funcionalidades

- Recebimento e processamento de dados IoT
- Cálculo preciso de distâncias usando o método **Geodesic** do Geopy
- Exibição dos dados em interface web otimizada
- Integração com banco de dados para armazenamento histórico

---

## 📦 Instalação e Uso

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/IoT-Calc.git
cd IoT-Calc

# Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Instale as dependências
pip install -r requirements.txt

# Execute as migrações do banco
python manage.py migrate

# Rode o servidor local
python manage.py runserver
