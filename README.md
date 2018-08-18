
Build:
```bash
docker build -t macflecknoe/deep-learning .
```

Run:
```bash
docker run --name deep-learning -v "$local_repo:/home/jupyter/code" -p 8888:8888 -it macflecknoe/deep-learning
```
