# RosettaHomeServices

Rosetta Home services are the back end applications needed to run [Rosetta Home](https://github.com/NationalAssociationofRealtors/LabLog).

The entire ecosystem currently includes 4 different repositories, one of which is optional*. 
### The Platform:

  * [Lab Log] (https://github.com/NationalAssociationofRealtors/LabLog)
  * [Node Bucket] (https://github.com/NationalAssociationofRealtors/node_bucket)
  * [CRTLab] (https://github.com/NationalAssociationOfRealtors/CRTLab)  
  * [SensorNode*] (https://github.com/NationalAssociationOfRealtors/SensorNode)


### Prerequisites:
* [Docker Toolbox] (https://www.docker.com/products/overview#/docker_toolbox)



### Running the services:

2. Run the following command from the terminal making sure to choose the correct configuration file depending on your operating system.

```
$ docker-compose -f docker-compose-macOS.yml up
```
