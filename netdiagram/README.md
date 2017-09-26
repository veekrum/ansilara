## Description of Diagram 

-> Here i have started with a route 53 which is highly available and scalable cloud Domain Name System (DNS) web service.
-> I have used a 2 ELB and 2 apps for the high availability and ELB helps to balance the traffic load 
-> we have a varnish cache center which caches the files neede frequently
-> we have a 2 mysql db[master/slave] synced.
-> we have a CDN which delivers a static-contents like images,pdf files.
