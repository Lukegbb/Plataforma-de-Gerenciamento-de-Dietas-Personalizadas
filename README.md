# Plataforma de Gerenciamento de Dietas Personalizadas

## Descrição | Description
### Português 🇧🇷
Uma aplicação web para sugerir planos alimentares e receitas personalizadas com base nos objetivos do usuário (perda de peso, ganho de massa muscular, etc.), utilizando Django, gráficos de progresso e uma API de alimentos (como Edamam ou Nutritionix).

### English 🇺🇸
A web application to suggest personalized meal plans and recipes based on user goals (weight loss, muscle gain, etc.), using Django, progress charts, and a food API (like Edamam or Nutritionix).

---

## Funcionalidades | Features
- 🇧🇷 Sugestões de dietas baseadas em perfis personalizados.
- 🇧🇷 Gráficos para rastrear progresso alimentar e de objetivos.
- 🇧🇷 Integração com APIs para dados nutricionais.

- 🇺🇸 Diet suggestions based on personalized profiles.
- 🇺🇸 Charts to track dietary and goal progress.
- 🇺🇸 Integration with APIs for nutritional data.

---

## Requisitos | Requirements
- Python 3.9 ou superior / or higher
- Django 5.1.3
- Bibliotecas: `requests`, `matplotlib`
- API Key da Edamam ou Nutritionix (opcional para teste).

---

## Instalação | Installation

# Crie um ambiente virtual | Create a virtual environment
python -m venv venv
source venv/bin/activate # Linux/macOS
venv\Scripts\activate    # Windows

# Instale as dependências | Install dependencies
pip install -r requirements.txt

# Aplique as migrações do banco de dados | Apply database migrations
python manage.py migrate

# Inicie o servidor local | Start the local server
python manage.py runserver
