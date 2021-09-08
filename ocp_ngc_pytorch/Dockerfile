FROM nvcr.io/nvidia/pytorch:20.12-py3

WORKDIR /ocp

COPY env.yml env/

# install ocp dependencies 
RUN conda env update --name base --file ./env/env.yml

WORKDIR code
RUN git clone https://github.com/Open-Catalyst-Project/ocp.git
ENV PYTHONPATH="${PYTHONPATH}:/ocp/code/ocp:/ocp/code/ocp/ocpmodels/"
