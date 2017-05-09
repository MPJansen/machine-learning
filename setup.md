# Cuda
 1. Install CUDA 
 2. Check createion of symlink to cuda install
    /usr/local/cuda -> /usr/local/cuda-<#>
 3. install cudnn to /usr/local/cuda-<#>/include /lib64
 4. create environment vars.
 5. install nvidia-smi and nvidia-modprobe
 6. run CUDA samples
 
# Keras
pip install keras #installs tensorflow cpu

## tricks
 1. Use workers with generators to speed up training [1]
 
 
 [1]: https://github.com/kzuiderveld/deeplearning1/blob/master/Improving%20training%20speeds%20using%20Keras%202.ipynb
 

# Tensorflow
  1. pip install tensorflow-gpu
  2. run and check output 
      sess = tf.Session(config=tf.ConfigProto(log_device_placement=True))

# Theano

# Various

## BColz
## Pandas
## TQDM
TQDMNotebookCallback for progressbars!
