FROM jupyter/datascience-notebook

EXPOSE 8888

COPY ./requirements.txt /code/

WORKDIR /code

VOLUME /code

RUN pip install --upgrade pip
RUN pip install -r requirements.txt
RUN jupyter nbextension enable --py --sys-prefix ipyleaflet
RUN pip freeze
