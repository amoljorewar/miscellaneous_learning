# Routing vs Switching

| **Aspect**             | **Routing**                                         | **Switching**                                     |
|-------------------------|-----------------------------------------------------|--------------------------------------------------|
| **Definition**          | Forwarding data between different networks.         | Forwarding data within the same network.         |
| **Device Used**         | Router.                                             | Switch.                                          |
| **Primary Identifier**  | IP Address (Layer 3 - Network Layer).               | MAC Address (Layer 2 - Data Link Layer).         |
| **Scope**               | Inter-network communication (connects networks).    | Intra-network communication (connects devices).  |
| **Protocol**            | Uses routing protocols like OSPF, RIP, BGP.         | Uses no protocols or VLANs for segmentation.     |
| **Table Used**          | Routing Table (stores network paths).               | MAC Address Table (stores device addresses).     |
| **Functionality**       | Determines the best path for packet forwarding.     | Directly connects devices and forwards frames.   |
| **Speed**               | Generally slower due to complex path calculations.  | Faster as it deals with local communication.     |
| **Layer**               | Operates at Layer 3 (Network Layer).                | Operates at Layer 2 (Data Link Layer).           |
| **Example**             | Sending data between two offices via the internet. | Sharing files between computers in the same LAN. |
