# validador-gtfs-api

API para validar GTFS via request

## Requisitos

- python 3.11

Recomendado:
- ambiente virtual como [anaconda](https://www.anaconda.com/) ou [venv](https://docs.python.org/pt-br/3/library/venv.html)

## Configuração inicial

Crie seu ambiente virtual:
```bash
conda create -n validador_gtfs_api python=3.11
```

Entre no ambiente virtual:
> Provavelmente você terá que fazer isso toda vez que abrir um novo terminal.
```bash
conda activate validador_gtfs_api
```

Instale as dependências:
```bash
pip install -r app/requirements.txt
```

## Desenvolvimento local

No seu ambiente virtual, execute o código em sua máquina:
```bash
uvicorn main:app --reload
```

Você deverá ver uma saída como essa:
```log
INFO:     Will watch for changes in these directories: ['<SEU-DIRETORIO>/validador-gtfs-api']
INFO:     Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
INFO:     Started reloader process [30712] using StatReload
INFO:     Started server process [24116]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
```

### Acessando a API

Aecsse [localhost:8000](http://localhost:8000)
