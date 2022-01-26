ARG BASE_IMAGE=ghcr.io/pyvista/pyvista:latest
FROM $BASE_IMAGE

COPY . ${HOME}
WORKDIR ${HOME}
RUN pip install -r requirements.txt
