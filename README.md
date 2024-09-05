# MYDFIR-30-Day-SOC-Analyst-Challenge

Learnings and insights from the 30-Day SOC Analyst Challenge, a self-paced program simulating a Security Operations Center (SOC) analyst experience. This repository tracks my progress, including notes and key takeaways from challenges and exercises in threat detection, incident response, and security analysis.

# How To Create a Logical Diagram | Day 1

## Objective

To understand the fundamentals of creating logical diagrams to visualize network infrastructure and create a basic logical diagram for a sample network.

### Skills Learned

- Logical Diagram Creation: Learned the fundamentals of creating logical diagrams for network infrastructure.
- Network Visualization: Developed an understanding of how to represent various network components, such as firewalls, routers, servers, and endpoints.
- Draw.io Proficiency: Gained hands-on experience using draw.io for creating network diagrams.
- Network Infrastructure Knowledge: Gained insight into network topologies and how different components interact within a SOC environment.
- Visualization of Security Architectures: Learned to visualize secure communication paths and segmentations in a network.

### Tools Used

- draw.io for creating network diagrams

## Summary of Achievement

The diagram depicts a network architecture with a SOC Analyst laptop connecting to an Elastic and Kibana stack, a Windows server, a Flee server, and an Ubuntu server.

![MYDFIR 30 DAY SOC challenge  drawio (1)](https://github.com/user-attachments/assets/c107ad73-8cb0-4f4a-a94c-31f56965c353)
*Ref 1: Network Diagram*

Components

- SOC Analyst Laptop: The entry point for monitoring and managing the network. It's used to connect to the Elastic & Kibana stack for centralized log analysis and incident response.
- Elastic & Kibana: A powerful log analysis and visualization tool. It receives logs forwarded from the managed agents (Windows and Ubuntu servers) and provides an interface for security analysts to investigate potential threats.
- VLTR (Virtual Local Area Network): A private network segment that isolates and secures the managed agents.
- Windows Server: An example of a managed agent, potentially running a critical application or service. It forwards its logs to Elastic & Kibana for monitoring.
- Flee Server: Another example of a managed agent, potentially used for specific tasks or services. It also forwards its logs to Elastic & Kibana.
- Ubuntu Server: Another managed agent, potentially serving as a web server or application server. It forwards logs for analysis and security monitoring.
- OS Ticket Server: A system that handles the creation and tracking of tickets related to potential security incidents or technical issues detected by Elastic & Kibana.
- Attacker Laptop: Represents an external attacker attempting to compromise the network. This laptop is running a Kali Linux distribution, a popular tool for penetration testing and security assessments.
- C2 (Command & Control) Server: A server used by the attacker to manage and control compromised systems. This C2 server uses the 'Mythic' framework, a popular framework for building and managing C2 infrastructures.
