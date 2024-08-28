# this is create by me.
docker build -t thanksimage .
docker run --name thankscontainer -itd -p 27016:80 thanksimage
