FROM python:3.9.1

RUN pip install pandas

WORKDIR /app
COPY pipelline.py pipelline.py

ENTRYPOINT [ "python" , "pipelline.py" ]