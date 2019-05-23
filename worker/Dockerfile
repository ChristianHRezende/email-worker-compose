FROM python:3.6
LABEL maintainer 'Aluno Coder'

#N usar buffer
ENV PYTHONUNBUFFERED 1
RUN pip install redis==2.10.5

ENTRYPOINT ["/usr/local/bin/python"]

#para escalar pe necessario adicionar --scale worker=3 para 3 instancias