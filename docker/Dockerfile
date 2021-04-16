FROM python:3.8-slim

ENV PATH=/root/.local/bin:$PATH

# Install the required stack
RUN pip install --user pandas \
    numpy \
    matplotlib \
    torch==1.8.1 \
    torchvision \
    torchaudio

EXPOSE 8888
