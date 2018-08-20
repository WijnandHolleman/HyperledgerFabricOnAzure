# HyperledgerFabricOnAzure
Setup an VM on Azure wth Hyperldger Fabric and Composer and Playground

Install Hyperledger on Azure 

1. Create a resource in Azure portal
2. Choose Ubuntu 17.04 server
3. Choose Standard B2ms (2 vcpus, 8 GB memory)
4. Select public inbound ports: HTTP, HTTPS, SSH, RDP
5. Add inbound ports: 8080 (for website) and 3000 (for rest server)
6. Set static IP address
7. SSH into VM
8. Execute commands from Install Hyperledger on Azure.txt file
9. run playgound: http://<azure dns>:8080
10. Rest server: http://<azure dns>:3000
  

