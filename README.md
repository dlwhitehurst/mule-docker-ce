# mule-docker-ce

This Docker build is attributed to Manik Magar and found on Github. I did not fork Manik's repo because
my ultimate goal is a higher architecture where Mule can be used to still employ best practice in-house,
on-premise, or even in the cloud. This architecture intends to lower the overall total cost of ownership
or TCO for using MuleSoft's infrastructure platform as a service (IPaaS).

My longer term goal here is create a re-useable model for containerized Mule to be run on Kubernetes with 
fully automated CI/CD at least for the Dev and Test environments. The cost of Mule in Production today
is taxing on the Enterprise's IT budget. Information Technology (IT) as a community should stand for 
best-practice software development and integration but when we allow quality and security to suffer due
to the high cost of ownership in any one technology, we fail our community by skirting quality behavior
and even shorting security well-knowns.
 
These shortcuts range from software module unit testing to end-user testing. Many times the end users of
Enterprise services are global. Must we host licensed Mule servers on staging environments and provide 
public endpoints that are licensed (paid for) similar to production?


