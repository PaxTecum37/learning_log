🧠 Learning Log

Django web aplikacija napravljena prema knjizi *Python Crash Course* autora Eric Matthes.  
Omogućuje korisnicima da vode dnevnik učenja s vlastitim unosima i temama.

## 🚀 Tehnologije

- Python 3.x
- Django 5.2.5
- Bootstrap 5 (preko `django-bootstrap5`)
- SQLite (default Django baza)
- HTML, CSS

## 📦 Instalacija

1. Kloniraj repozitorij:

git clone https://github.com/PaxTecum37/learning_log.git
cd learning_log

Kreiraj i aktiviraj virtualno okruženje:

Windows:

python -m venv ll_env
ll_env\Scripts\activate


Linux/macOS:

python3 -m venv ll_env
source ll_env/bin/activate


Instaliraj potrebne pakete:

pip install -r requirements.txt


Pokreni migracije i server:

python manage.py migrate
python manage.py runserver


Otvori u pregledniku:

http://127.0.0.1:8000

✅ Funkcionalnosti

Kreiranje korisničkih računa

Dodavanje tema za učenje

Pisanje unosa (logova) po temama

Ograničen pristup vlastitim podacima

🛠️ Platforma

Razvijano lokalno, mogućnost deploya na Platform.sh (paket platformshconfig).

📄 Licenca

Ovaj projekt je napravljen u edukativne svrhe.
