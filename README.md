# fastapi-book

## Run my program

D'après le livre :

```commandline
python main.py &
```

Mais comme j'ai créé un environnement poetry :

```commandline
poetry run python main.py &
```

## Faire des tests manuels

```commandline
http localhost:8000
```

Suivi des sous-pages en fonction du besoin.
- Option **-b** retire le header
- pour avoir les autres endpoints (pas les get), on ajoute le verbe clé avant l'URL: 
  GET, PUT (=remplacer), PATCH (=modifier), DELETE, POST (=créer)

### Interface de tests manuels de FastAPI

Dans un browser, taper: `http://localhost:8000/docs`