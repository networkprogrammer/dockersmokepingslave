# dockersmokepingslave
docker build -t smokeping .

docker run -itd --env-file=environment --name=smokepingslave smokepings

