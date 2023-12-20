FROM python:3.10.13

ADD . /gluonts

RUN pip install -r /gluonts/requirements/requirements-mxnet.txt
RUN pip install /gluonts[shell]

ENTRYPOINT ["python", "-m", "gluonts.shell"]
