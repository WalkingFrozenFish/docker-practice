FROM python:3.6

RUN mkdir /somepython/
WORKDIR /somepython/

COPY . /somepython/
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8080

CMD ["python", "app.py"]