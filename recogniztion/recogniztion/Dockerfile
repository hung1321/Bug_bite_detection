FROM python:3.11
WORKDIR /insect
copy . /insect
RUN pip install -r requirements.txt
CMD ["python", "manage.py","runserver"]
EXPOSE 8000
