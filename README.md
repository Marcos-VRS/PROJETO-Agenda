# **PROJETO-Agenda**  

[![Django Version](https://img.shields.io/badge/Django-5.1-green)](https://www.djangoproject.com/) [![Python Version](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)  

Um sistema simples para cadastro e gerenciamento de contatos, desenvolvido em **Python** com o framework **Django**.  
O projeto oferece:  
- Uma interface para **cadastrar novos contatos**.  
- Armazenamento seguro dos dados de contatos em um **banco de dados**.  
- Utilização do **Faker** para geração de dados fictícios.  

---

## **Tabela de Conteúdo**

1. [Recursos](#recursos)  
2. [Tecnologias Utilizadas](#tecnologias-utilizadas)  
3. [Instalação](#instalação)  
4. [Uso](#uso)  
5. [Contribuição](#contribuição)  
6. [Licença](#licença)  

---

## **Recursos**  

### **Cadastro de Contatos**  
- Interface simples para adicionar novos contatos ao banco de dados.  
- Campos para nome, e-mail, telefone e outros dados de contato.  

### **Banco de Dados**  
- Armazenamento de dados em banco de dados SQLite, fácil de configurar e usar.  

### **Geração de Dados Fictícios**  
- Utiliza a biblioteca **Faker** para a criação de dados fictícios, útil para testes.  

---

## **Tecnologias Utilizadas**  

- **Frontend:** HTML, CSS, JavaScript.  
- **Backend:** Django 5.1, Python 3.11.  
- **Banco de Dados:** SQLite (configuração padrão, personalizável).  
- **Bibliotecas e Dependências:**  
  - [Faker](https://faker.readthedocs.io/) para gerar dados fictícios.  
  - [Python Dateutil](https://pypi.org/project/python-dateutil/) para manipulação de datas.  
  - [Pillow](https://pillow.readthedocs.io/) para manipulação de imagens.  

---

## **Instalação**  

### **Pré-requisitos**  
- Python 3.11 ou superior.  
- Pip instalado.  

### **Passos para Instalação**  
1. Clone o repositório:  
   ```bash
   git clone https://github.com/Marcos-VRS/PROJETO-Agenda.git
   cd PROJETO-Agenda


2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv  
   source venv/bin/activate  # Linux/Mac  
   venv\Scripts\activate     # Windows
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt

4. Execute as migrações:
   ```bash
   python manage.py migrate


5. Inicie o servidor:
   ```bash
   python manage.py runserver  

---

## **Uso**
1. Acesse a plataforma na URL: http://127.0.0.1:8000/.
2. Crie uma conta para começar a jogar ou faça login se já tiver um perfil.
3. Escolha um contato da agenda e veja suas informações.

---

## **Contribuição**
Contribuições são bem-vindas! Para contribuir:
1. Faça um fork do repositório.
2. Crie uma branch com sua funcionalidade ou correção:
   ```bash
   git checkout -b minha-contribuicao  
3. Envie um Pull Request para revisão.

---

## **Licença**
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.


---

## **Contato**
•Desenvolvedor: Marcos-VRS
•Email: marcosvrsdevmail@gmail.com
•LinkedIn: https://www.linkedin.com/in/marcos-vin%C3%ADcius-ramos-da-silva-557b18a5/
