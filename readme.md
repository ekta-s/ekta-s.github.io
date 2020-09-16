# Create a VCN in OCI

## Launch a web browser and navigate  to <https://console.us-ashburn-1.oraclecloud.com/>  ![Image of Login Screen](./media/Capture.jpg)

## On the sign in page, enter your account information, and click “Sign In” ![Image of Sign-In Page](./media/Image2.jpg)

## Now, you are logged in to Oracle Cloud Infrastructure (OCI) Dashboard ![Image of OCI Console](./media/Image3.jpg)

## In the web console, click Navigation Menu > Networking > Virtual Cloud Networks ![Navigating to VCN](./media/Image4.jpg)

## In the networking page, select your compartment name from the drop-down list 

![Image of Login Screen](./media/Image5.jpg)

## On the Virtual Cloud Networks page, click Start VCN Wizard ![Image of Login Screen](./media/Image6.jpg)

## In the dialog box, choose VCN with Internet Connectivity, and click Start VCN Wizard. ![Image of Login Screen](./media/Image7.jpg)

## Provide the basic information

## •VCN Name – ocilabs-network

## •Compartment – <your_compartment>

## •VCN CIDR Block – Enter 10.0.0.0/16

## •Public Subnet CIDR Block – Enter 10.0.1.0/24

## •Private Subnet CIDR Block – Enter 10.0.2.0/24

## •Select the check box for - Use DNS Hostnames in this VCN

## •Click Next

![Image of Login Screen](./media/Image8.jpg)

## Review and click Create  

![Image of Login Screen](./media/Image9.jpg)

## The VCN is created along with Private and Public Subnets.

![Image of Login Screen](./media/Image10.jpg)

# Launch Cloud shell

1.  Click the **Cloud Shell icon** on the top right of the screen

![](./media/image11.png)

2.  This will launch the Cloud Shell in a "drawer" at the bottom of the
    console

![](./media/image12.png)

3.  Display the name space of your OCI tenant

**oci os ns get**

![](./media/image13.png)
