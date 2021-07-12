```
sudo docker build . -t gpu:withouttmp -f Dockerfile.gpu
sudo docker  run -it  --gpus all gpu:withouttmp /bin/bash
```