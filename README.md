# Active Directory Project

## Objective
This Active Directory project is aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus is to setup an Acitve Directory environment, setup Splunk to detect unauthorized logins, and setup automated responses to the alert using Shuffle as our main Securtiy Orchestration, Automation, Response (SOAR) Tool. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.



## Tools Used
<p>
  <img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/-Windows%20Server-737373?&style=for-the-badge&logo=Microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/-Ubuntu%20Server-E95420?&style=for-the-badge&logo=Ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/-Slack-4A154B?&style=for-the-badge&logo=Slack&logoColor=white" />
  <img src="https://img.shields.io/badge/-Azure-0078D4?&style=for-the-badge&logo=Microsoft%20Azure&logoColor=white" />


</p>

## Table of Contents
- <a href="https://github.com/jonasm2-cs/Active-Directory-Project/blob/main/README.md#p1-logical-diagram">P1. Logical Diagram</a>
- <a href="https://github.com/jonasm2-cs/Active-Directory-Project/blob/main/README.md#p2-setting-up-our-cloud">P2. Setting up our Cloud</a>
- <a href="https://github.com/jonasm2-cs/Active-Directory-Project/blob/main/README.md#p3-install-and-setup-active-directory">P3. Install and Setup Active Directory</a>
- <a href="https://github.com/jonasm2-cs/Active-Directory-Project/blob/main/README.md#p4-configuring-splunk">P4. Configuring Splunk</a>
- <a href="https://github.com/jonasm2-cs/Active-Directory-Project/blob/main/README.md#p5-integrate-slack--shuffle-for-automation">P5. Integrate Slack & Shuffle for Automation</a>
- <a href="https://google.com">Demo</a>



## P1. Logical Diagram
<p><b>Objective:</b> Create a Logical Diagram using <a href ="https://app.diagrams.net/">draw.io </a> to visualize what our project will look like.</p>
<img width="1027" height="642" alt="Active Directory Project drawio" src="https://github.com/user-attachments/assets/6511a62c-539d-4b23-9382-dd63854f7ee5" />
<b>Watch Tutorial:</b> <a href="https://www.youtube.com/watch?v=1nX6_Nlly-4&ab_channel=MyDFIR"> Cybersecurity Project: Active Directory 2.0 | Part 1 </a>

## P2. Setting up our Cloud Environment
<p><b>Objective: </b> Create 3 Virtual machines using Azure (Cloud platform) and ensure VMs can communicate with each other. By the end we will have 2 Windows Servers (1 Domain Controller, 1 Test machine) and 1 Ubuntu Server which will be hosting our Splunk SIEM.</p><strong>Note: This can be done on-prem but there will be more steps involved</strong>

### Step 1: Sign-up for Azure
1. Go to [Azure](https://azure.microsoft.com/en-ca/pricing/purchase-options/azure-account) - If you are a student go [here](https://azure.microsoft.com/en-us/free/students).
3. Fill-in fields 
4. Click-on **Sign Up**

### Step 2: Creating our Virtual Machines
1. Once you are in - click on the "Hamburger" Icon on the top left corner - Then Click on **Virtual Machines**
2. Click **Create** > **Virtual Machine**
3. 
4. 
5. 


### Step 3: Configuring Network Settings
1. 
2. 
3. 

### Step 4: Configuring the Servers
1. 
| Machine | Spcifications |
|-------------------|--------------------|
| Domain Controller | <ul><li>CPU: 1vCPU</li><li>RAM: 2GB</li><li>Storage: 64GB</li><li>Operating System: Windows Server 2022</li></ul> |
| Testing Machine   | <ul><li>CPU: 1vCPU</li><li>RAM: 2GB</li><li>Storage: 64GB</li><li>Operating System: Windows Server 2022</li></ul> |
| Splunk Server     | <ul><li>CPU: 1vCPU</li><li>RAM: 3.5GB</li><li>Storage: 128GB</li><li>Operating System: Ubuntu 22.04</li></ul> |

## P3. Install and Setup Active Directory
## P4. Configuring Splunk 
## P5. Integrate Slack & Shuffle for Automation

## Demo

## Skills Learned
[Bullet Points - Remove this afterwards]

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.
