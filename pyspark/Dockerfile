FROM python:3.10-slim
COPY requirements.txt /tmp/
RUN pip install -r /tmp/requirements.txt
RUN rm -f /tmp/requirements.txt
CMD /bin/bash