(This project is currently in development. I ll add the regex later..
# harbor-metrics
Prometheus level metrics of harbor with mtail 

# Mtail 

mtail is the library provided by the Google Inc. 

# Install the mtail into destination Harbor instance 

Please follow the instruction from official mtail repo. 
https://github.com/google/mtail

#Clone this repo

I have added the regex for the components for the harbor. 

To run it 

```
mtail --progs adminserver/adminserver.mtail --logs /var/log/harbor/adminserver.log 
```

You can see the metrics: 

```
http://harbor-instance:3903/metrics
```
