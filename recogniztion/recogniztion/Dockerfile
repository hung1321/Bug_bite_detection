FROM python:3.11.5
WORKDIR /insect
copy . /insect
RUN pip install -r requirements.txt
CMD ["python", "manage.py","runserver"]