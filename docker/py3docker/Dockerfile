FROM python:3.10.0b2

RUN pip install pandas && \
    pip install numpy && \
    pip install PyYAML && \
    pip install matplotlib && \
    pip install pyyaml

RUN mkdir /src
COPY . /src

CMD python /src/numpy-sum.py
