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
## OUTPUT
<img width="643" height="880" alt="Screenshot 2025-11-19 213906" src="https://github.com/user-attachments/assets/9543add0-a034-4394-ba51-f0311f19ed4f" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT
<img width="553" height="227" alt="Screenshot 2025-11-19 213945" src="https://github.com/user-attachments/assets/f792d983-4f42-4b10-b891-33c337356648" />



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="456" height="272" alt="Screenshot 2025-11-19 214009" src="https://github.com/user-attachments/assets/8ee4aba1-30f8-409c-9188-b2c1eec0825f" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="393" height="184" alt="Screenshot 2025-11-19 214224" src="https://github.com/user-attachments/assets/c07c5f9f-809e-401d-b75f-f2a4fad0c393" />



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
<img width="259" height="126" alt="image" src="https://github.com/user-attachments/assets/73e5c706-7e21-402e-a857-72f7975e8c1a" />




It shows the following screen in which the option Google can be selected:
## OUTPUT
<img width="724" height="421" alt="image" src="https://github.com/user-attachments/assets/3998521e-99c6-4261-bd89-48bf0890c221" />





SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
<img width="948" height="175" alt="image" src="https://github.com/user-attachments/assets/a76cb164-21e3-43b7-9446-c9a72193f8d6" />




In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="960" height="515" alt="image" src="https://github.com/user-attachments/assets/665f6abb-9cc2-419a-9f83-15da18fe4b5d" />


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
