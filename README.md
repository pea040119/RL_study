STUDY

Check versions
 - python
 python --version

 - cuda
 nvidia-smi
 nvcc --version

Check version in .py__
import sys__
import torch__

print(sys.version)__
print(torch.__version__)__
print(torch.version.cuda)__
print(torch.cuda.is_available())__
print(torch.cuda.get_device_name())__
print(torch.cuda.device_count())__