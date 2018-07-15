Now running hello and goodbye services from this service so using 6010 port instead of 6011 and 6012 ports

URLS:
http://localhost:6010/hello
http://localhost:6010/goodbye

WHen we visited to http://localhost:6010/hello, the gateway servide looked up a service with an name 'hello' from service discovery server and then proxy the traffic to to that service, and then proxy the response back to the browser. 


