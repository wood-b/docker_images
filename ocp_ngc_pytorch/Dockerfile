FROM nvcr.io/nvidia/pytorch:20.12-py3

# install other python stuff necessary
RUN apt-get update && apt-get install -y rsync && \
    pip install --no-cache-dir \
    numpy \ 
    scipy \
    ase>=3.21 \
    black \
    matplotlib>=3.3 \
    nbsphinx \
    pandoc \
    pre-commit>=2.10 \
    pymatgen==2020.12.31 \
    ruamel.yaml \
    pyyaml \
    sphinx \
    tensorboard>=2.4 \
    tqdm>=4.58 \
    cmake \
    ipympl \
    pillow \
    demjson \
    lmdb==1.1.1 \
    pytest==6.2.2 \
    sphinx-rtd-theme \
    wandb \
    torchsummary \
    jupyter-server-proxy \
    requests \ 
    tabulate \
    ray \ 
    ray[tune] \ 
    ray[rllib] \
    -f https://pytorch-geometric.com/whl/torch-1.8.0+cu111.html \
    torch-cluster \
    torch-scatter \
    torch-sparse \
    torch-spline-conv \
    git+https://github.com/rusty1s/pytorch_geometric.git \
    wandb \
    git+https://github.com/NERSC/nersc-tensorboard-helper.git

