
# Networking in Azure and GCP - IPs and Domain Management

## Azure

### 1. Creating a Virtual Private Cloud (VNet)
Below are the steps to create a Virtual Network (VNet) in Azure, along with the screenshots showing each step:

1. Navigate to the Azure portal and create a new Virtual Network.
2. Choose an IP address range and subnet configuration.
3. Reserve a static public IP address for a virtual machine.
4. Map the reserved IP address to a domain using Azure DNS.

#### Screenshots:
![Azure Screenshot 1](./screenshots/1.png)
![Azure Screenshot 2](./screenshots/2.png)
![Azure Screenshot 3](./screenshots/3.png)
![Azure Screenshot 4](./screenshots/4.png)
![Azure Screenshot 5](./screenshots/5.png)
![Azure Screenshot 6](./screenshots/6.png)
![Azure Screenshot 7](./screenshots/7.png)
![Azure Screenshot 8](./screenshots/8.png)
![Azure Screenshot 9](./screenshots/9.png)
![Azure Screenshot 10](./screenshots/10.png)
![Azure Screenshot 11](./screenshots/11.png)
![Azure Screenshot 12](./screenshots/12.png)

## Google Cloud Platform (GCP)

### 2. Creating a Virtual Private Cloud (VPC)
The steps to create a VPC in GCP are similar to Azure, but specific to GCP's interface:

1. Access the Google Cloud Console and create a new VPC network.
2. Configure the IP address range and subnets similarly to the Azure setup.
3. Reserve a static external IP address for a Compute Engine instance.
4. Map the reserved IP address to a domain using Google Cloud DNS.

#### Screenshots:
![GCP Screenshot 1](./screenshots/13.png)
![GCP Screenshot 2](./screenshots/14.png)
![GCP Screenshot 3](./screenshots/15.png)
![GCP Screenshot 4](./screenshots/16.png)

## Optional: VPN and Tunnels
Both platforms offer VPN services that allow secure tunnels between networks. These features are optional for this assignment.

### Azure VPN Setup:
1. Use the VPN Gateway service.
2. Set up a site-to-site VPN with a remote network.

### GCP VPN Setup:
1. Use the Cloud VPN service.
2. Create a tunnel between two VPC networks.
