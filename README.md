# This is created by me, taking inspiration from [Aareez Asif](https://youtu.be/tJxmN_nN__Y?si=EDfXoumrRuZtEWBL).

docker build -t thanksimage .
docker run --name thankscontainer -itd -p 27016:80 thanksimage
