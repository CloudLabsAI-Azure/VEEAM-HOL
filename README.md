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

## Add the Workers to Workspace
1. Go to **Getting Started page** and **click on Review workers configuration**
![veeam14](./images/veeam14.jpg)
2. Click on **+Add**
![veeam15](./images/veeam15.jpg)
3. Click on **region** and select the region of the resource group and **Apply** and Click **Next**
![veeam16](./images/veeam16.jpg)
4. Select the **Virtual Network**, **Subnet** and **Network security Group** and **Next**
![veeam18](./images/veeam18.jpg)
5. Click on **Finish**
![veeam19](./images/veeam19.jpg)
6. Click on **profile** and **+Add**
![veeam20](./images/veeam20.jpg)
7. Select the **Region**, select the proper region and click on **add** and click on **Next**
![veeam21](./images/veeam21.jpg)
8. Move to the **worker profile** and click **Next**
![veeam22](./images/veeam22.jpg)
9. Go to **summary** and click **Finish**
![veeam23](./images/veeam23.jpg)
10. Move to **instance** tab and verify instance is created if it is still in creating state wait till it move to created state
![veeam24](./images/veeam24.jpg)

## Add the repository
1. Move to **Getting Started** page and click on **Add repository**
![veeam25](./images/veeam25.jpg)
2. Click on **+Add**
![veeam26](./images/veeam26.jpg)
3. Enter the **Name** and **Discription** and Click **Next**
![veeam27](./images/veeam27.jpg)
4. Select the **storage account**, **Conatiner** and create the **NewFolder** and **Next**
![veeam28](./images/veeam28.jpg)
5. Select the **Option** and click **Next**
![veeam28](./images/veeam29.jpg)
6. Click on **Summary** and **Finish**
![veeam30](./images/veeam30.jpg)
7. Verify that the repository is creation in success state.
![veeam31](./images/veeam31.jpg)

## Create Backup policy for Virtual Machines
1. Move to **Getting started page** and **Create your first policy**
![veeam32](./images/veeam32.jpg)
2. Click on **+Add**
![veeam33](./images/veeam33.jpg)
3. Click on **PolicyInfo** enter the **Name** and **Description** and click **Next**
![veeam34](./images/veeam34.jpg)
4. Select the **Azure Active Directory**, select the directory which is given in the azure and select the **Region**
![veeam35](./images/veeam35.jpg)
5. Select the  **All resource**
![veeam36](./images/veeam36.jpg)
6. Select the **protect the following resources** and **Browse to select the specific resource from the global list**
![veeam37](./images/veeam37.jpg)
7. Select the checkbox for virtual machine and click on **ADD**
![veeam38](./images/veeam38.jpg)
8. Click on **APPLY**
![veeam39](./images/veeam39.jpg)
9.Click on **Next**
![veeam40](./images/veeam40.jpg)
10. Move to **Guest processing** and **Enable application aware snapshots** and click **Next**
![veeam41](./images/veeam41.jpg)
11. Select the **Targets** and **Enable Backup:on** click **Next**
![veeam42](./images/veeam42.jpg)
12. Select the **Schedule**, **Daily Retension:On** and **Edit Daily Settings**
![veeam43](./images/veeam43.jpg)
13. Select the **Repository** : **Azure Backup**, Click on **Apply** and Click **Next**
![veeam44](./images/veeam44.jpg)
14. Select the **Settings** click **Next**
![veeam45](./images/veeam45.jpg)
