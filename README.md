
Build:
```bash
docker build -t macflecknoe/jupyter .
```

Run:
```bash
docker run --name jupyter -v "$local_repo:/home/jupyter/code" -p 8888:8888 -it macflecknoe/jupyter
```
