En caso de no tener Flask hacer un 

    pip install Flask

y usar en venv 

    python -m venv venv
    source venv/bin/activate  # En Windows, use "venv\Scripts\activate"

para correr docker usar 

    docker run -p 4000:80 myflaskapp

para docker compose usar

    docker-compose up

y al terminar 

    docker-compose down
