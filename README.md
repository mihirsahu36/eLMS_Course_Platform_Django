# eLMS_Course_Platform_Django

A e-platform for academic institutions that combines learning management and online assessment.

## Features

- Admin can add courses, teachers, and students, and assign courses to them.
- Teachers can create course content, announcements, assignments, quizzes, and take attendance. They can also view details and analysis of the assessments.
- Students can enroll in courses using an access key, view the content of their enrolled courses, participate in assessments, and see their detailed results.
- There is a discussion section available for both teachers and students.

## Run Locally

1. Clone the project

```bash
git clone https://github.com/mihirsahu36/eLMS_Course_Platform_Django.git
```

2. Go to the project directory

```bash
cd eLMS_Course_Platform_Django
```

3. Create a virtual environment and activate it (Windows)

```bash
python -m venv env
```

```bash
env\Scripts\activate
```

4. Install dependencies

```bash
pip install -r requirements.txt --use-deprecated=legacy-resolver
```

5. Make migrations and migrate

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```

6. Create admin/superuser

```bash
python manage.py createsuperuser
```

7. Finally run the project

```bash
python manage.py runserver
```

