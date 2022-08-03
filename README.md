![veeam1](./images/veeam1.jpg)
#  Veeam Hands-on Lab for Microsoft Azure
## Login to Veeam VM
1. Copy the Public IP address from the VM and Note the **Username** and **Password** from the azure portal
2. Open the new browser and paste the value copied below and replace the **IPADDRESS** with the Veeam VM IP address
  `````
  https://IPADDRESS
  `````
![veeam2](./images/veeam2.jpg)
3. Click on the **advance**
![veeam3](./images/veeam3.jpg)
4. Click on the **click on processed to IP**
![veeam4](./images/veeam4.jpg)
5. Enter the **Username** and **Password** and click on Login
![veeam5](./images/veeam5.jpg)
6. Check all the check boxes in the licence agreement and click on **Accept** and login into the VM
![veeam6](./images/veeam6.jpg)

## Add a Microsoft azure account
1. Click on add a microsoft azure account first
![veeam7](./images/veeam7.jpg)
2. Click on **Add**
![veeam8](./images/Veeam8.jpg)
3. Enter the **Name**, **Description** and click on the **Next**
![veeam9](./images/veeam9.jpg)
4. In the **Service Account Type** click on **Specify the exisiting service account**
![veeam10](./images/veeam10.jpg)
5. Copy the **TenantID**, **Application ID** and **Secret** of service principal from environment details Tab
![veeam11](./images/veeam11.jpg)
6. Paste the Copied values in the respective fields and click **Next**
![veeam12](./images/veeam12.jpg)
7. Move to the **Summary** and click **Finish** to setup the microsoft account
![veeam13](./images/veeam13.jpg)
