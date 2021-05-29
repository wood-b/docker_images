FROM nvcr.io/nvidia/pytorch:21.05-py3

# install other python stuff necessary
RUN apt-get update && apt-get install -y rsync && \
    pip install --no-cache-dir \
    ruamel.yaml pyyaml cmake ipympl pillow wandb torchsummary \
    jupyter-server-proxy requests tabulate ray ray[tune] ray[rllib] \
    git+https://github.com/NERSC/nersc-tensorboard-helper.git

