STUDY

---check version---
import sys
import torch

print(sys.version)
print(torch.__version__)
print(torch.version.cuda)
print(torch.cuda.is_available())
print(torch.cuda.get_device_name())
print(torch.cuda.device_count())