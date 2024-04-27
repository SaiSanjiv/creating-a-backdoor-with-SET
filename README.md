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

![image](https://github.com/MARXINLIJO/creating-a-backdoor-with-SET/assets/145742540/477ee989-8938-495c-aece-8e05fac13fda)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/MARXINLIJO/creating-a-backdoor-with-SET/assets/145742540/ed813e63-6668-4e76-b046-0af8c2a26445)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/MARXINLIJO/creating-a-backdoor-with-SET/assets/145742540/c7cb205b-1fe0-4f35-9cbc-005623064083)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/MARXINLIJO/creating-a-backdoor-with-SET/assets/145742540/94959fe0-5cbb-4322-a78d-6811dc3d06a6)

 It shows the following screen in which the ip address of the attacker need to be given which is the default value:


![image](https://github.com/MARXINLIJO/creating-a-backdoor-with-SET/assets/145742540/72c3b51b-f4dd-44e6-9969-5899679d2115)

It shows the following screen in which the option Google can be selected:


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 

![image](https://github.com/MARXINLIJO/creating-a-backdoor-with-SET/assets/145742540/df1475b7-df8e-4bcb-9ac2-b4eb730c72da)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

SET logs the information regarding the Google credentials:

![image](https://github.com/MARXINLIJO/creating-a-backdoor-with-SET/assets/145742540/7ac54101-51b4-4a45-ac61-92b0b2336568)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/MARXINLIJO/creating-a-backdoor-with-SET/assets/145742540/ae90cd90-259b-46f5-947b-69533bbf951c)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
