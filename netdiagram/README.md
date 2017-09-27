## netDiagram1
## Description of Diagram 
* my assumption while keeping a varnish cache server between the load balancer and the apps but doesnot looks good and seems like no use of the ELB.

* Here i have started with a route 53 which is highly available and scalable cloud Domain Name System (DNS) web service.
* I have used a 2 ELB and 2 apps for the high availability and ELB helps to balance the traffic load 
* we have a varnish cache center which caches the files, that is needed frequently
* we have a 2 mysql db[master/slave] synced.
* we have a CDN which delivers a static-contents like images,pdf files which is stored in the s3.

## netDiagram2
## Description of the diagram without varnish cache server

*  The ELB will distribute the load in the round-robin fashion to app1 and app2.
