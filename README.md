# 🏠 UniFi Home Network

A fully designed and deployed home network using the UniFi ecosystem. This project focuses on network segmentation, device security, and privacy enhancements. The main goal was to create a robust, secure, and manageable home network environment.

## 📦 Technologies

- `Ubiquiti UniFi Controller`
  
- `UniFi Access Points`
  
- `UniFi Security Cameras`
  
- `UniFi Door Access Controllers`
  
- `VLANs and network segmentation`
  
- `VPN (with DNS-level ad blocking)`
  
- `Firewall and routing configurations`

## 🦄 Features

Here's what you can do with the network I built:

- **Wireless Coverage:** Seamless Wi-Fi throughout the house using multiple UniFi access points with optimized placement and channels.

- **Device Segmentation:** Network is divided into VLANs to isolate IoT devices, guest networks, and sensitive personal devices, preventing lateral movement in case of compromise.

- **Security Cameras:** Full IP camera coverage with remote monitoring capabilities. Motion alerts and recording configurations provide home security.

- **Door Access Control:** Centralized management of door controllers for keyless entry and access logging.

- **VPN with Privacy:** A router-wide VPN protects traffic from external threats. Integrated DNS-level ad blocking reduces unwanted tracking and improves browsing privacy.

- **Network Monitoring:** Centralized monitoring of devices, bandwidth usage, and network health through the UniFi Controller dashboard.

## 🎯 Key Benefits:

- **Privacy & Security:** Reduced attack surface by isolating devices and enforcing network policies.

- **Manageability:** Easy monitoring and control from a single interface.

- **Scalability:** Designed to expand with more devices or new VLANs if needed.

## 👩🏽‍🍳 The Process

I started by planning the network layout and identifying the devices I needed, including access points, IP cameras, and door access controllers. I mapped out where each device would go to ensure coverage and functionality across the home.

Next, I deployed the hardware. I installed the access points for Wi-Fi coverage, mounted security cameras in strategic locations, and configured door controllers for secure entry and logging. Device placement was planned to balance performance, coverage, and convenience.

Once the devices were in place, I configured the network. I segmented it into VLANs to isolate guest devices, IoT devices, and sensitive personal devices, preventing lateral movement and protecting critical systems. I also set up a router-wide VPN with DNS-level ad blocking to improve privacy and reduce the attack surface for all connected devices.

I tested network connectivity, Wi-Fi coverage, VPN access, and camera feeds, making adjustments to channels, firewall rules, and device settings to ensure everything ran smoothly.

Along the way, I documented each step, from VLAN configurations to device settings, so the network could be replicated or troubleshot in the future. Documenting the process helped me understand the network more deeply and ensured nothing was missed.

By the end, I had a fully functional, secure home network and a much better understanding of network design, device integration, and system management. Planning, implementing, testing, and documenting each step helped me see how everything works together.

<img width="3838" height="1459" alt="image" src="https://github.com/user-attachments/assets/4aa0378b-f1f5-4a0b-b330-ca0d8525a618" />

## 📚 What I Learned

### 🧠 VLANs and Segmentation

- **Logical Isolation:** Learned how to separate network traffic to protect sensitive devices.

- **Lateral Movement Prevention:** Gained insight into how attackers move across networks and how segmentation mitigates this risk.

### 🔒 Security & VPN

- **Network Hardening:** Configuring router-level VPN and DNS-level ad blocking enhanced my understanding of privacy and threat mitigation.

### 🎛 UniFi Ecosystem

- **Device Management:** Learned to manage multiple UniFi devices through a single controller interface.

- **Integration Skills:** Connected cameras, access points, and door controllers seamlessly on a unified network.

### 📈 Overall Growth

- **Networking Knowledge:** This project strengthened my understanding of home network design, device security, and centralized management.

- **Problem-Solving:** Optimized Wi-Fi coverage, resolved connectivity issues, and fine-tuned firewall rules for maximum performance.

### 💭 How it can be improved

- Integrate additional smart home devices with VLAN isolation.

- Set up automated alerts for unusual network activity.

- Expand VPN and ad-blocking rules for mobile devices outside the home.

- Implement redundant internet connectivity for failover.

## 🚦 Running / Accessing the Network

To manage or replicate the network setup:

1. Access the UniFi Controller via browser or mobile app.

2. Navigate to the Devices tab to view access points, cameras, and door controllers.

3. Configure VLANs and firewall rules under Settings → Networks.

4. Enable VPN and DNS-level ad blocking under Settings → Internet / Security.

5. Monitor device health and alerts in the Dashboard.

![Censor](https://github.com/user-attachments/assets/2c992400-40dc-4b60-927f-78e6c9d24a50)


