# This is created by me, taking inspiration from [Aareez Asif](https://youtu.be/tJxmN_nN__Y?si=EDfXoumrRuZtEWBL).

docker build -t thanksimage .


docker run --name thankscontainer -itd -p 27016:80 thanksimage


## Note 
1- open port 27016

2- http://publicIP:27016/thanks.html
