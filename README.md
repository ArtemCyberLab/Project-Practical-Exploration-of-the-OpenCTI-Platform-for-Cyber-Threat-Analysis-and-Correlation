Project Objective

The goal of this project is to study the OpenCTI platform and apply its tools to analyze, visualize, and identify relationships between malware, attack techniques, and threat actor groups.

Project Description

During this project, I explored the OpenCTI platform, which is designed for managing and correlating cyber threat intelligence data. My focus was on hands-on interaction with the system — navigating the interface, searching for entities, building relationship graphs, and interpreting analytical results.

In practice, I examined two main entities: the CaddyWiper malware and the APT37 threat actor group.
Through my analysis, I determined that the earliest recorded activity of CaddyWiper dates back to March 15, 2022, and that it uses the Native API execution technique — a low-level method that helps it evade traditional antivirus detection. I also discovered 113 related malware samples using the same execution technique, indicating its widespread use among attackers.

Next, I analyzed APT37, a group associated with North Korea. The investigation revealed that this actor commonly uses the T1189 (Drive-by Compromise) and T1566 (Phishing) techniques for initial access. The graph visualization clearly showed the correlation between this group, phishing campaigns, and related malware loaders.

Working with OpenCTI proved to be highly effective — the platform successfully aggregates intelligence from multiple sources, maps interconnections, and significantly speeds up threat analysis. The visualization of entity relationships helped me better understand attack structures and identify behavioral patterns used by adversaries.

Conclusion

As a result of this research, I concluded that OpenCTI is a powerful and practical tool for cyber threat intelligence and investigation. The platform not only stores information but also builds logical connections between incidents, actors, and attack techniques.
Analyzing real-world examples such as CaddyWiper and APT37 demonstrated how OpenCTI can be used to quickly gather context around an attack and visualize the entire chain of compromise.

This experience proved the platform’s value in SOC and DFIR environments, enhancing the efficiency of analytical workflows. The project allowed me to gain a deeper understanding of how threat intelligence data is structured, correlated, and used to support proactive defense.
