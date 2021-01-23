FROM nvcr.io/nvidia/tensorflow:20.12-tf2-py3
COPY requirements.txt requirements.txt
RUN pip install --upgrade pip && \
    pip install --no-cache-dir -r requirements.txt
