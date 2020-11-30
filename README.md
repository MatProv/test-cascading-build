docker build -t matprov/base-img-test ./base
docker build -t matprov/real-img-test ./real


docker run -it --rm matprov/real-img-test sh -c "ls -la *test"