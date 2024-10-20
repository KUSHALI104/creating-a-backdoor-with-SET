# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/user-attachments/assets/6985c430-9c39-4d6d-87e3-7c60819d2522)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/user-attachments/assets/843026b1-a4fd-45f2-8682-cfe6b725abc8)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:


![image](https://github.com/user-attachments/assets/052c4250-a5d2-459a-9e13-4704b7b2a4a8)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:


![image](https://github.com/user-attachments/assets/ab19281c-043f-4733-a778-97aa7116d5a3)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:


![image](https://github.com/user-attachments/assets/57daf147-d95e-4314-8aa2-4d00e5f180f4)

It shows the following screen in which the option Google can be selected:


![image](https://github.com/user-attachments/assets/a003a6db-5d22-40f3-8daf-e188cf29493e)


![image](https://github.com/user-attachments/assets/eafda7f0-83d2-49bb-9245-308a8c334829)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:


![image](https://github.com/user-attachments/assets/8c2078ff-f325-48fc-99fd-f1c4e11276a4)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password


![image](https://github.com/user-attachments/assets/eba75ec2-5e97-436c-83c8-0281cb910a9a)

SET logs the information regarding the Google credentials:


![image](https://github.com/user-attachments/assets/c67dfb3e-0067-4a38-868e-69ce0fde004c)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
