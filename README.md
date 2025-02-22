# Deeprod

### Deep learning project for CS-01418364

dependencies
- ultralytics
<code>pip install -U ultralytics</code>

- torch (cuda)
<code>pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118</code>

- torchvision (cuda)
<code>pip install torchvision --index-url https://download.pytorch.org/whl/cu118</code>

- [cuda version 11.8](https://developer.nvidia.com/cuda-11-8-0-download-archive?target_os=Windows&target_arch=x86_64&target_version=11&target_type=exe_local)
### Check if torch works properly
```
print(torch.__version__) # Check PyTorch version

print(torch.version.cuda) # Check the CUDA version PyTorch was built with

print(torch.cuda.is_available()) # Should return True
```
