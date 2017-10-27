Dockerfile for Elastic Search
=============================

### To build image
	docker build -t elasticsearch:2.3 .

### To run the container
	docker run -p 29200:9200 -p 29300:9300  -d -it elasticsearch:2.3

### To Connect the head plugin of elasticsearch
	http://localhost:29200/_plugin/head/

 

