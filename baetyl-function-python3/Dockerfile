FROM --platform=$TARGETPLATFORM python:3-slim-buster
COPY *.py *.txt /bin/
RUN cd /bin/ && chmod +x function-python3.py && pip install -r requirements.txt
ENTRYPOINT ["function-python3.py"]