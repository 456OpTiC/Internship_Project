College Campus Network Project README
**Overview**:
This project aims to design and implement a robust network infrastructure for a college campus comprising a five-floor building. The network includes VLANs for different departments, inter-VLAN routing, internet connectivity, security features, and DHCP/DNS configuration.

**Network Architecture:**

**Building Structure:**

The college campus consists of a five-floor building.
Each floor hosts different departments, including CSC, IT, ECE, and EEE, and their respective classrooms.
Hardware:

Cisco 2811 Router with a single LAN port for internet connectivity.
Switches on each floor to connect hosts within departments.
Access point installed on the fourth floor for wireless connectivity.

**Project Requirements:**

**VLAN Configuration:**

Each department is assigned a separate VLAN.
Inter-VLAN communication is enabled for seamless connectivity between departments.

**Internet Connectivity:**

The router is configured for internet access via a 100Mbps connection to the ISP.
Bandwidth is allocated to each department based on requirements.

**Security:**

Secure credentials are set up for router and switch logins.
Port security is implemented to restrict unauthorized access.
Access control lists (ACLs) are configured to control traffic flow and block specific IPs.

**DHCP and DNS:**

DHCP is configured on the router for automatic IP address assignment.
DNS entries are set up for URL resolution.

**Challenges and Solutions:**
**Inter-VLAN Communication:**

Ensure proper router configuration for inter-VLAN routing.
Test routing protocols/static routes for each VLAN.

**Security Risks:**

Regularly update login credentials and wireless passwords.
Monitor switch logs for unauthorized access attempts.

**Bandwidth Allocation:**

Thoroughly test QoS configurations for accurate bandwidth allocation.
Monitor network traffic to identify any bandwidth issues.

**NAT and ACL Configuration:**

Carefully follow configuration steps for NAT and ACLs.
Regularly review and update ACLs based on security requirements.
