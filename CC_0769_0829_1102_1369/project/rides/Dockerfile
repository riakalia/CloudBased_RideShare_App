FROM python:3.6.9
COPY . /rides
WORKDIR /rides
RUN pip3 install -r requirement.txt
RUN pip3 install -U Flask-SQLAlchemy
RUN pip3 install flask-marshmallow
RUN pip3 install marshmallow-sqlalchemy
RUN pip3 install requests
CMD ["python3","./db.py"]
ENTRYPOINT ["python3"]
CMD ["rides.py"]
