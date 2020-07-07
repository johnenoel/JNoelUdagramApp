## John Noel ##

## Project 2 - Deploy a High-Availability Web App using CloudFormation 


This Udagram Application project deploys a web server for a highly available web app using CloudFormation.
The script deploys the networking components followed by servers, security roles and software.

## The files included are:
```sh
 create.sh --- Shell script to create stack. 
 update.sh --- Shell script to update stack.
 destroy.sh --- Shell script to delete stack.
 JNoelUdagram_networkandserver.yml --- Udagram Project's CloudFormation script.
 JNoelUdagram_networkandserver.json  --- Udagram Project's CloudFormation script parameters.
 Udagram_diagram.png ---- the diagram containing the networks and servers
 App_deployed.png --- Screenshot of the url showing the application is deployed successfully
 Config_in_AWS.pdf --- other screenshot of the configuration within AWS
```

## URL to view the running/deploying application 
http://jnoel-webap-4vbnl06tykv0-1184556272.us-west-2.elb.amazonaws.com/

## Instruction to deploy all the configuration within AWS:

Just execute the following command;
```sh
> ./create.sh JNoelUdagramApp JNoelUdagram_networkandserver.yml JNoelUdagram_networkandserver.json
```

## Instruction to delete all the configuration:

Just execute the following command;
```sh
> ./destroy.sh JNoelUdagramApp
