# CI-CD-Security-Posture-Management-or-CCSPM
Implementing Continous Security in the CI/CD Toolchain

The rise of security in the cloud and cloud native archirtecture, it is important how to architect continuous security in all the perimeters.
These perimeters have evolves into 3 main categories*
1- Data Plane
2- Identity
3- Control Plane
These 3 categories are also covered with the combination of the 3 security standards with CSPM, CWP and CASB.
the Data Plane covers the security risks from the apps and networks which could be IaaS or SaaS and Posture Management covers Related to Identity and Access Mgmt, 
Resource configurations and standards like CIS, NIST, PCI etc...Identity is also critical as identity and access applies to more than users but ressources such as S3, EC2 via roles.
On premise and private cloud have very strict guardrails where changes are not driven by users but rather by the IT teams. However with the cloud and devops environment where changes are very dynamic and contiuous, it is impoortant
to implement an adaptive and continuous security modei that can be superposed to the CI/CD toolchain. This in turn merges security with devops and leads
to the creation of secdevops.

With secdevops, it starts with the code with SAST/DAST by static or dynamically securing the code. it is then important to have a policy with which apps are being deployed and implementing security to detect any policy violations, block source 
of policy violation and remedy to those
policy violations. 
- The workflow would look like this+
- Establish golden policy to continoulsly deploy code/apps
- Create rule to detect policy or configuration drift
- Block and prevent drift when detected
- Remedy to config drift by manually or dynamically modifying drift to golden config or policy
- Notify users and relevant party of policy violation and remediation and audit changes.

With SecDevOPs, the goal is to implement security checks and balances in the CI?CD Toolchain. This will allow the CI/CD toolchain Security Posture Management


