# 📚 LibraCore (Library Management Backend) 
     [Django REST API]
**LibraCore** is a **Django REST API backend** for managing library operations efficiently.  
It handles **book issuing, returns, overdue fines, member profiles**, and audit tracking using clean architecture and production-ready workflows.

---

## 🚀 Features
- 📖 **Book Management:** Add, update, delete, and search books  
- 👤 **Member Profiles:** Custom user accounts for library members  
- 🔄 **Issue & Return Tracking:** Track book issuing and returns  
- 🕒 **Automated Fines:** Overdue fine calculation via management command  
- 📝 **Audit Trail:** Keep logs of all book issue/return events  
- 🔐 **REST API Endpoints:** Fully tested with Thunder Client/Postman  
- ⚡ **Admin-friendly:** Model design with filtering & sorting  

---

## 🛠️ Tech Stack
- **Framework:** Django, Django REST Framework  
- **Database:** SQLite (development), PostgreSQL (production-ready)  
- **Testing:** Django TestCase, Thunder Client/Postman  
- **Deployment:** WSGI-ready, `.env` support, minimal dependencies  

---

## 📦 Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/saif22003/LibraCore.git
cd LibraCore

# 2. Create & activate virtual environment
python -m venv venv
source venv/bin/activate     # Mac/Linux
venv\Scripts\activate        # Windows

# 3. Install dependencies
pip install -r backend/requirements_package/dev.txt

# 4. Apply migrations
python manage.py migrate

# 5. Create superuser for admin access
python manage.py createsuperuser

# 6. Start development server
python manage.py runserver

