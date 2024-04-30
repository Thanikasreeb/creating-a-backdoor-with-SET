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
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to 
the attackers. The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/Thanikasreeb/creating-a-backdoor-with-SET/assets/119557910/a4cb5f26-623b-4b0c-8187-c98cc4914206)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/Thanikasreeb/creating-a-backdoor-with-SET/assets/119557910/e2be36d5-024c-47ef-9f09-5dce9e1875fe)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected

![image](https://github.com/Thanikasreeb/creating-a-backdoor-with-SET/assets/119557910/bd81a014-8357-4f45-a0c7-f2f3b83aedf1)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![326256891-d10a55ea-dbd5-41d4-ac19-a9e8a0dd927d](https://github.com/Thanikasreeb/creating-a-backdoor-with-SET/assets/119557910/7d84af71-e521-4ad4-9532-6be6a5167fcd)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/Thanikasreeb/creating-a-backdoor-with-SET/assets/119557910/b3abadcf-6a50-4cbb-847b-d957daa35380)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/Thanikasreeb/creating-a-backdoor-with-SET/assets/119557910/a29b0a66-4b1c-4cd6-8ba9-c8f32bdf7a7d)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/Thanikasreeb/creating-a-backdoor-with-SET/assets/119557910/9fecfa51-7a1e-4b83-b4bf-a15bb96208ed)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the 
username and password

![image](https://github.com/Thanikasreeb/creating-a-backdoor-with-SET/assets/119557910/f5cc1237-051c-4623-a1e7-c3550294ad16)

SET logs the information regarding the Google credentials:

![image](https://github.com/Thanikasreeb/creating-a-backdoor-with-SET/assets/119557910/18d0e0ec-7f5d-482a-817a-b1980d01ceed)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/Thanikasreeb/creating-a-backdoor-with-SET/assets/119557910/b6ba1ce3-6f77-4861-814a-8ddd57707d32)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
