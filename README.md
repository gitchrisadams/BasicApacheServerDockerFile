# Building an Apache image

docker build -t apacheserver:0.1 .

# Container based off above image:

docker run -it --name my_apache-container -d -p 1337:80 IMAGEID_HERE
