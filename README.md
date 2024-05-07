# The Permission Problem

## Objective

The goal of this project was to utilize knowledge of the CIA triad, vulnerability assessments, and the Linux command line to solve a configuration problem and create a detailed report. The learning objectives include asset and inventory management, risk management, digital forensics, system administration, interpersonal skills, problem solving, and writing.


### Skills Learned

- Using appropriate Linux commands to locate a named config.conf file.
- Checking the permissions of a given file and interpreting the permissions.
- Ability to check the MD5 hash of a given file.
- Ability to edit a file using vim and nano.
- Creating a backup of a given file into the home directory using Linux commands.


### Tools Used

- Kali Linux machine was used to run all the Linux commands. This was the main tool used to solve the task.


## Steps

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










