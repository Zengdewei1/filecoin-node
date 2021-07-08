```
sudo docker build . -t gpu -f Dockerfile.gpu
sudo docker  run -it --gpu all gpu /bin/bash 
```