# pytorch + jupyter in a docker

usage:

```bash
docker build --tag pytorch_jupyter . 
docker run -p 8888:8888 --gpus all -i -t pytorch_jupyter:latest  
```
