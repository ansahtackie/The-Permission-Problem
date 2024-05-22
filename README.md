# The Permission Problem

## Objective

The aim of this project was to leverage expertise in the CIA triad, vulnerability assessments, and Linux command line to resolve a configuration issue and produce a comprehensive report. The learning objectives encompassed asset and inventory management, risk management, digital forensics, system administration, interpersonal skills, problem-solving, and technical writing.


## Skills Learned

#### CIA Triad Expertise
- Understanding and application of the principles of Confidentiality, Integrity, and Availability.

#### Vulnerability Assessment
- Identifying, evaluating, and prioritizing security vulnerabilities in systems and networks.

#### Linux Command Line Proficiency
- Advanced skills in using the Linux command line for system configuration and troubleshooting.

#### Configuration Management
- Solving configuration issues and ensuring systems are set up securely and efficiently.

#### Asset and Inventory Management
- Tracking and managing hardware and software assets within an organization.

#### Risk Management
- Identifying, assessing, and mitigating risks to the organization’s information systems.

#### Digital Forensics
- Conducting investigations and analyzing digital evidence to understand security incidents.

#### System Administration
- Managing and maintaining computer systems and networks.

#### Interpersonal Skills
- Collaborating effectively with team members and stakeholders.

#### Problem-Solving
- Analyzing complex issues and developing practical solutions.

#### Technical Writing
- Creating detailed reports that document the problem-solving process, findings, and recommendations.

#### Research and Analysis
- Conducting thorough research to understand problems and apply best practices for resolution.

#### Attention to Detail
- Ensuring accuracy and thoroughness in all aspects of the project.

#### Communication
- Clearly conveying technical information to both technical and non-technical audiences.





## Tools Used

- Kali Linux Machine
- Linux Command Line Tools


## Steps Used

####  Identifying The Config.conf File
- Locate the config.conf file from the system using Linux commands. The following screen shots show how the config,conf file was located.
  

   ![image](https://github.com/ansahtackie/The-Permission-Problem/assets/148600552/2d319b09-2dbb-49b7-a86e-8548ebf0de55)



   ![image](https://github.com/ansahtackie/The-Permission-Problem/assets/148600552/9480da1a-4c78-444b-ad83-0a8c7ab05bb3)


   ![image](https://github.com/ansahtackie/The-Permission-Problem/assets/148600552/405de728-3c39-4384-b2e6-135deda58946)


####  Analyzing File Permissions
- Use the cd, ls - l commands to change directory and list the content and file permission of config.conf file.

   ![image](https://github.com/ansahtackie/The-Permission-Problem/assets/148600552/79531fcd-513b-4fac-9758-c648f053a7d1)

- Interprete the file permission
  

####  Analyzing MD5 Hash Values

- Use the md5sum command to analyze the MD5 has value of the file to check for the intergrity of the file.

  ![image](https://github.com/ansahtackie/The-Permission-Problem/assets/148600552/8107d991-ef70-4484-b445-f844886fd62f)

- Use the vim editing tool to edit the config.conf file and check the MD5 hash value again.

   ![image](https://github.com/ansahtackie/The-Permission-Problem/assets/148600552/6777fc7e-036d-4648-9df4-50337eb0864b)

- Check the MD5 hash value of the config.conf file and compare the hash value to the first hash value. If there is a change in the hash values that indicates that the file has been compromised. Below is the second MD5 hash value.

  ![image](https://github.com/ansahtackie/The-Permission-Problem/assets/148600552/b7fddc20-946a-4d50-92e4-fd95cfa6387f)










