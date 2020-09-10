# School-Management-System

This app is meant to be used by school manager to manage their school records:
(student data ,staff ,results and ,finances.)


It currently doesn't allow students/staff to login.
Solely, it's expected to be used on a single machine or online for managers only.

## Usage
It's best to install Python projects in a Virtual Environment. Once you have set up a VE, clone this project

```bash
cd Django-School-Management-System
```
Run

```python
pip install -r requirements.txt #install required packages
python manange.py migrate # run first migration
python manange.py runserver # run the server
```
Then locate http://172.0.0.1:8000

## Admin Login
When you run migrate, a superuser is created.
```bash
username: admin
password: admin078529618
```
