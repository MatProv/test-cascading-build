docker build -t matprov/base-img-test ./base <br>

docker build -t matprov/eo-img-test ./eo <br>
docker build -t matprov/nlp-img-test ./nlp


docker run -it --rm matprov/eo-img-test sh -c "ls -la *test" <br>
docker run -it --rm matprov/nlp-img-test sh -c "ls -la *test"


