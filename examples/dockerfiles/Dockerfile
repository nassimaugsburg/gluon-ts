FROM python:3.14.0a1

ADD . /gluonts

RUN pip install -r /gluonts/requirements/requirements-mxnet.txt
RUN pip install /gluonts[shell]

ENTRYPOINT ["python", "-m", "gluonts.shell"]
