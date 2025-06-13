# Writer's Circle

 Writer's Circle is a full-stack community-based publishing platform that allows users to share stories, articles, tutorials, 
 and journalistic content. Built for writers and readers, the platform provides an interactive, 
 searchable, and categorized environment to create, discover, and engage with written content.

# 🚀 Overview

Writer's Circle empowers users to:

- Register and authenticate securely.
- Create, edit, and delete their own posts.
- Read and comment on other users' content.
- Vote on posts to highlight popular content.
- Search and filter content by multiple criteria.

# 🛠️ Tech Stack

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

# ⚙️ Setup Instructions

## Backend Setup (Django & DRF)

```bash
git clone https://github.com/your-username/writers-circle.git
cd writers-circle/backend

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
```
## Frontend Setup (React)

```bash
cd ../frontend

npm install

npm start
```

# 🌟 Features

- User registration, login, logout
- Secure authentication with JWT
- Post creation, editing, deletion
- Commenting system
- Voting system (upvotes/downvotes)
- Full-text search with filters:
  - Username
  - Title & Content Keywords
  - Category
  - Date Created
  - Popularity
- Responsive design (Bootstrap)
- Fully separated frontend/backend architecture
- RESTful API following best practices

# 📈 User Stories

**As a Writer:**  
- I want to register and log in securely.  
- I want to create, edit, and delete my articles.  
- I want to categorize my articles for better visibility.  
- I want to receive feedback through comments and votes.

**As a Reader:**  
- I want to browse and search for articles by topic or author.  
- I want to comment and interact with writers.  
- I want to vote on articles I enjoy.

**As a Platform Owner:**  
- I want to maintain the system's stability and data integrity.

# 🧪 Experience Testing

- ✅ User registration tested on multiple devices
- ✅ JWT authentication fully verified
- ✅ Post creation, edit, and deletion tested
- ✅ Commenting system tested with concurrency
- ✅ Voting system stress-tested for race conditions
- ✅ Search filters tested across all combinations
- ✅ Frontend tested for responsive behavior (desktop, tablet, mobile)
- ✅ Backend API tested with Postman & automated tests

# 📊 Code Quality

**Frontend:**  
- ESLint with Airbnb config ensures clean React code.

**Backend:**  
- PEP8 standards enforced using Flake8.

**Version Control:**  
- Proper branching strategy & commit messages followed.

# 🔬 Code Validation & Testing Details

- ✅ **Backend Code Validation:**

  ![Backend Flake8](screenshots/backend-flake8-clean.png)

- ✅ **Frontend Code Validation:**

  ![Frontend ESLint](screenshots/frontend-eslint-clean.png)

- ✅ **CSS Validation:**

  ![CSS Validation](screenshots/TheW3C-CSS-Validator.png)


✅ Manual Testing (Full Application):

  - User registration & login (JWT authentication)

  - Post creation, editing, and deletion

  - Commenting & voting system

  - Search & filters functionality

  - Responsive design tested on mobile, tablet, and desktop

  - Backend API tested with Postman

  - Full functionality verified on multiple browsers
