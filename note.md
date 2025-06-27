## Install

https://github.com/KaiyangZhou/Dassl.pytorch?tab=readme-ov-file

```shell
# Clone this repo
git clone https://github.com/KaiyangZhou/Dassl.pytorch.git
cd Dassl.pytorch/

# Create a conda environment
conda create -y -n dassl python=3.8

# Activate the environment
conda activate dassl

# Install torch (requires version >= 1.8.1) and torchvision
# Please refer to https://pytorch.org/ if you need a different cuda version
conda install pytorch torchvision cudatoolkit=10.2 -c pytorch

# Install dependencies
pip install -r requirements.txt

# Install this library (no need to re-build if the source code is modified)
python setup.py develop

# Graph Adapter
pip install pickle5
```

## Download datasets

https://github.com/KaiyangZhou/CoOp/blob/main/DATASETS.md


## Train

```

```
