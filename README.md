# Aplikacja do anonimizacji i pseudonimizacji danych implementowana w ramach pracy magisterskiej. 

Uruchomienie aplikacji:

docker-compose down -v --remove-orphans
docker-compose build --no-cache 
docker-compose up


Uruchomienie aplikacji testowych:

python3 ./srodowisko_testowe/nprod/app.py
python3 ./srodowisko_testowe/prod/app.py
