# GitHub – student13

## Uruchomienie lokalne
python3 app/app.py

## Uruchomienie przez Docker
docker build -t github-student:local .
docker run --rm github-student:local

## Testy
pip install -r requirements.txt
pytest
