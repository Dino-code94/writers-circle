# Writer's Circle

 Writer's Circle is a full-stack community-based publishing platform that allows users to share stories, articles, tutorials, 
 and journalistic content. Built for writers and readers, the platform provides an interactive, 
 searchable, and categorized environment to create, discover, and engage with written content.

## 🚀 Overview

Writer's Circle empowers users to:

- Register and authenticate securely.
- Create, edit, and delete their own posts.
- Read and comment on other users' content.
- Vote on posts to highlight popular content.
- Search and filter content by multiple criteria.

## 🛠️ Tech Stack

**Frontend:**

- React.js  
- Bootstrap.js  
- Axios  
- JavaScript  
- HTML5 & CSS3

**Backend:**

- Django  
- Django REST Framework (DRF)  
- Python 3  
- PostgreSQL (or SQLite for development)

**Deployment & Tools:**

- Gunicorn  
- ESLint (Frontend code quality)  
- PEP8 / Flake8 (Backend code quality)  
- Git (version control)

## ⚙️ Setup Instructions

### Backend Setup (Django & DRF)

```bash
git clone https://github.com/your-username/writers-circle.git
cd writers-circle/backend

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
```
### Frontend Setup (React)

```bash
cd ../frontend

npm install

npm start
```
