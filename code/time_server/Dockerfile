FROM python:3.11-slim

WORKDIR /time_server

COPY . .

RUN pip3 install -r requirements.txt

EXPOSE 8001

CMD ["uvicorn", "app:api", "--host", "0.0.0.0", "--port", "8001"]