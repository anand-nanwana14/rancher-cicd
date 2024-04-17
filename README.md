# rancher-cicd    


**Deploying App on rancher through CICD**     

It will deploy a nginx app on rancher k8s cluster with the help of CI/CD


**Prerequisites**
installation of rancher   

Installation Using Docker 

1. sudo docker pull rancher/rancher:latest

2. docker run -d --restart=unless-stopped -p 80:80 -p 443:443 -v /opt/rancher:/var/lib/rancher --privileged rancher/rancher:latest

3. Access Rancher Web Interface:- Once the Rancher container is running, you can access the Rancher web interface by navigating to http://<RANCHER_HOST> or https://<RANCHER_HOST> in your web browser. Replace <RANCHER_HOST> with your server's hostname or IP address.

