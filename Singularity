Bootstrap: docker
From: tensorflow/tensorflow:1.12.0-devel-gpu-py3

%post
# default mount paths, files
mkdir /scratch /data /secure /seq
  
# install other packages you want
pip install --upgrade pip
pip install --no-cache-dir seaborn
pip install --no-cache-dir Pillow
pip install --no-cache-dir keras
pip install --no-cache-dir sklearn
