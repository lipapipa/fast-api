# task-api

CRUD-сервис для управления задачами. FastAPI + Docker + автодеплой.

## Локальный запуск

    conda create -y -n task-api python=3.11
    conda activate task-api
    pip install -r requirements.txt
    uvicorn app.main:app --reload

Документация: http://localhost:8000/

Swagger UI: https://89.111.172.51.nip.io/docs