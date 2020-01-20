
![gRPC Up and Running - Cover](https://raw.githubusercontent.com/grpc-up-and-running/samples/master/images/grpc-cover.png)

## Welcome
Welcome to the resource repository of the book "gRPC - Up and Running". 

All the samples of this repository require to have the accompanying book [gRPC Up and Running](https://www.amazon.com/gRPC-Running-Building-Applications-Kubernetes/dp/1492058335/). Each sample is based on a real-world use case and details of the use case can be found in the respective chapter of the book. 


## Don't have _gRPC Up and Running_ book yet? 

You can purchase it from following book sellers worldwide.  

* [Amazon](https://www.amazon.com/gRPC-Running-Building-Applications-Kubernetes/dp/1492058335/)
* [Barns and Nobel](https://www.barnesandnoble.com/w/grpc-kasun-indrasiri/1132647211?ean=9781492058335#/) 

## Prerequisites

* Installing *Go*    
    Download the latest Go distribution file from [Go’s official download page](https://golang.org/dl/) and follow the steps to install Go language.
 
* Installing *Java*    
    Samples are tested in JDK 1.8 version. Recommended to install JDK 1.8 version. [Java official downland page](https://www.java.com/en/download/)

* Installing *Gradle*  
    [Gradle](https://gradle.org/) is required for builing and running all the Java samples. So, please install Gradle if you plan to try out Java samples of the book. 

* Installing *protoc*  
    [protoc](https://developers.google.com/protocol-buffers/docs/downloads) is required for generating code for your protocol buffer based gRPC service definitions (IDLs). Hence please install if you plan to use code generation. 


  
## Samples from the _gRPC Up and Running_ Book

- Chapter 01 - Introduction to gRPC
    - No code samples required for this chapter. 
- Chapter 02 - Getting Started with gRPC
    - Getting Started with gRPC [[Go]](https://github.com/grpc-up-and-running/samples/tree/master/ch02/README.md) [[Java]](https://github.com/grpc-up-and-running/samples/tree/master/ch02/README.md) 

- Chapter 04 - gRPC Under the Hood
    - No code samples required for this chapter. 
    
- Chapter 03 - gRPC Communication Patterns
    - Communication patterns [[Go]](https://github.com/grpc-up-and-running/samples/tree/master/ch03/README.md) [[Java]](https://github.com/grpc-up-and-running/samples/tree/master/ch03/README.md) 

- Chapter 05 
    - Interceptors [[Go]](https://github.com/grpc-up-and-running/samples/tree/master/ch05/README.md) [[Java]](https://github.com/grpc-up-and-running/samples/tree/master/ch05/README.md) 
    - Deadline
    - Cancellation 
    - Compression 
    - Keepalive 
    - Metadata 
    - Error Handling
    - Load Balancing
    - Multiplexing

- Chapter 06
    - Secure Channel
    - Mutual TLS Channel
    - Basic Authentication
    - Token Based Authentication
    
- Chapter 07
    - Continuous Integration
    - Deploy in Docker
    - Deploy in Kubernetes
    - OpenCensus metrics
    - OpenCensus tracing
    - OpenTracing
    - Prometheus
    
- Chapter 08
    - gRPC Gateway
    - Server Reflection
    
## Authors 
### Kasun Indrasiri
![Kasun](https://raw.githubusercontent.com/grpc-up-and-running/samples/master/images/kasun.jpg)

Kasun Indrasiri is an author and an evangelist of microservices and enterprise integration architecture with over ten years of experience in building distributed systems. He is the director of Integration Architecture at WSO2 and the product manager of the WSO2 Enterprise Integrator. He has authored [Microservices for Enterprise](https://www.amazon.com/Microservices-Enterprise-Designing-Developing-Deploying/dp/1484238575) (Apress, 2018) and [Beginning WSO2 ESB](https://www.amazon.com/Beginning-WSO2-ESB-Kasun-Indrasiri/dp/148422342X) (Apress, 2017) and has spoken at several conferences, including the O’Reilly Software Architecture Conference 2019 in San Jose and GOTO Con 2019 in Chicago, and WSO2 Conferences in San Francisco, London, and Barcelona. Kasun lives in San Jose, California, and has founded the “Silicon Valley Microservices, APIs and Integration” Meetup, which is one of the largest microservices meetups in the San Francisco Bay area..


### Danesh Kuruppu 
![Danesh](https://raw.githubusercontent.com/grpc-up-and-running/samples/master/images/danesh.jpg)

Danesh Kuruppu is an associate technical lead at WSO2 with expertise in microservices, messaging protocols, and service governance. Danesh has spearheaded the development
of gRPC language implementation and microservices framework.
