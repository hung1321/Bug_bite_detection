FROM python:3.10
WORKDIR /insect
copy . /insect
RUN pip install -r requirements.txt
CMD ["python", "manage.py","runserver"]
EXPOSE 8080
