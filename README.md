# Government Department - Higher and Technical Education

The Higher & Technical Education department is responsible for steering and supporting the development and growth of quality Higher and Technical Education that meets educational and social objectives of the state.
The Department continues to promote relevant, accessible, high quality and inclusive Higher and Technical education in accordance with Maharashtra’s development goals and priorities.
The ideal network for such an organization therefore must be straightforward and easily managed.
This Department Network Scenario is about designing a topology of a network that is a LAN (LocalAreaNetwork) for a government department in which various computers of different departments are set up so that they can interact and communicate with each other by interchanging data.

# Objective
The Project calls for the implementation of a network for the Department of Higher and Technical Education in which we maintain security, quality and simplicity of Systems. The objectives of the project are:
1. The network should reliably deliver applications and provide reasonable response time.
2. The network should be easy to modify to adapt to network growth and general changes.
3. Finding and fixing a problem should not be too time-consuming if the network follows a simple structure.
4. Firewall to avoid malicious packets.

# Network Requirements
Few of the basic network requirements for the given enterprise network are follows:
1. IP addresses
2. DHCP server
3. Routing protocol - Static RIP
4. ACL ( AccessControlLists )
5. Hierarchy - Core, Distribution, Access
6. Basic Security

# Major Design Areas and Functional Areas
1. The Department of Higher and Technical Education consists of four departments, Technical, Higher Education, Arts and Libraries. All the departments are connected to different network. For e.g.on ground floor there is department of Technical Education.
2. Each department network are inter-connected via 2621XM routers.
3. The routers are then further connected to 2950-24 switches which will be the Head office switches for Regional, Autonomous, Divisional and District of the respective departments.
4. Each department has its own DHCP server with basic configuration of firewall.
5. These switches will be then connected to the end devices.

# Routing Protocol Plan
<img width="428" alt="Static" src="https://user-images.githubusercontent.com/52970601/116002941-963e7180-a619-11eb-9f71-37e08599d532.png">

<img width="529" alt="topology" src="https://user-images.githubusercontent.com/52970601/116002998-d998e000-a619-11eb-836f-5c8b7f461220.png">

# Summary
This project is focused on the security, quality and inter-connectivity aspects that can be provided to any Government Department network. Therefore,the project integrates multiple areas in the networking field to introduce the best technical options available. The main aim has been achieved by designing a network for enterprise with minimal cost.The most common problem that arises in any Governing body is tampering of data.The Confidentiality and Integrity of the data is a very important aspect for Government.To resolve this,the network has been designed and configured to provide a high quality of service. The network topology is designed in way that will manage communication between inter-connected devices with ease and efficiency. The firewall and backup devices used in this network are of good quality.

