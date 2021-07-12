```
sudo docker build . -t gpu:withouttmp -f Dockerfile.gpu
docker-compose up
sudo docker  run -it  --gpus all gpu:withouttmp /bin/bash
```