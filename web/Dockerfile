FROM python:3.4-onbuild
CMD uwsgi --http :5000 --master --processes 4 --threads 2 -w app:app
