# Qruit Job Portal

## Phase 1: Project Setup and Structure

### Completed Tasks:
1. **Virtual Environment Setup**
   - Created `.venv` directory
   - Activated virtual environment

2. **Package Installation**
   - Installed Django
   - Installed psycopg2-binary for PostgreSQL support
   - Installed python-decouple for environment variable management

3. **Project Structure Creation**
   ```
   D:\qruit\
   ├── .venv\
   ├── manage.py
   ├── requirements.txt
   ├── .env
   ├── backend\
   │   ├── core\
   │   ├── accounts\
   │   ├── recruiter\
   │   ├── candidate\
   │   ├── campus\
   │   ├── api\
   │   └── utils\
   ├── qruit\
   │   ├── settings.py
   │   ├── urls.py
   │   └── wsgi.py
   ├── theme\
   │   ├── static\theme\css\
   │   ├── templates\layout.html, navbar.html
   │   └── tailwind.config.js
   ├── templates\
   │   ├── base.html
   │   ├── auth\
   │   ├── recruiter\
   │   ├── candidate\
   │   ├── campus\
   ├── static\
   ├── media\
   └── sent_emails\
   ```

4. **Configuration Files**
   - Created requirements.txt with project dependencies
   - Created .env file with basic configuration
   - Created tailwind.config.js for styling

### Next Phase
Phase 2 will involve:
- Django settings configuration
- Database setup
- Initial app creation
- Basic URL routing 