FROM public.ecr.aws/lambda/python:3.12

COPY requirements.txt .

RUN pip3 install -r requirements.txt -U --no-cache-dir

COPY ./api ./api

CMD [ "api.app.handler" ]
