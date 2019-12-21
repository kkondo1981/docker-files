
```
git clone https://github.com/kkondo1981/docker-files.git
cd actuaryR
docker build -t actuaryr .
cd ../aglm
docker build -t aglm .
docker run -e PASSWORD=password --rm -p 8787:8787 aglm
```
