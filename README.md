STUDY

Check versions
 - python  
 python --version  

 - cuda  
 nvidia-smi  
 nvcc --version  

Check version in .py  
import sys  
import torch  

print(sys.version)  
print(torch.&#95;&#95;version&#95;&#95;)  
print(torch.version.cuda)  
print(torch.cuda.is_available())  
print(torch.cuda.get_device_name())  
print(torch.cuda.device_count())  