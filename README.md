# 🚘 Rare BMW Lottery Web App

A Django-based web application that allows users to apply for rare and luxurious BMW cars. Inspired by the Hermès reservation model, this platform creates exclusivity and fairness in the selection process.

## 🌟 Features

- Users apply for the BMW of their choice
- Applications are open for a limited period
- One winner is randomly selected per car
- The winner earns the exclusive right to purchase the vehicle
- Admin dashboard to manage cars and applicants

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (can be changed to PostgreSQL/MySQL)

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- pip
- Virtualenv (recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/rare-bmw-lottery.git
cd rare-bmw-lottery

# Create virtual environment and activate
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver
