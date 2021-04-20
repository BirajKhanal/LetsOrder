# LetsOrder

## First install the requirement.txt
## Then, for alembic 
    - alembic revision --autogenerate -m "Initial tables"
    - alembic upgrade head
## Then, to run the application
    - uvicorn app.main:app --reload
