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


# ![Screenshot 2024-04-20 204929](https://github.com/DEEPAK22003907/creating-a-backdoor-with-SET/assets/119404520/ede19572-c7bd-4080-afcb-8748ac3a2531)

It displays the following menu and select 2 for Website Attack Vectors: 

# ![Screenshot 2024-04-20 205037](https://github.com/DEEPAK22003907/creating-a-backdoor-with-SET/assets/119404520/47d59582-0678-4351-8325-a7f11536f114)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected: 

# ![Screenshot 2024-04-20 205130](https://github.com/DEEPAK22003907/creating-a-backdoor-with-SET/assets/119404520/46e6fd0a-b7ab-48e6-bdef-93cbe22b3959)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 

# ![Screenshot 2024-04-20 205216](https://github.com/DEEPAK22003907/creating-a-backdoor-with-SET/assets/119404520/123ca549-2b90-4b65-9a5a-7b4303e06641)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

# ![Screenshot 2024-04-20 205314](https://github.com/DEEPAK22003907/creating-a-backdoor-with-SET/assets/119404520/aa25cd1d-1c19-4565-af6a-b71b4c629917)

It shows the following screen in which the option Google can be selected:

# ![Screenshot 2024-04-20 205454](https://github.com/DEEPAK22003907/creating-a-backdoor-with-SET/assets/119404520/851cb131-dca5-4c23-b5ca-241d54086fca)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

# ![Screenshot 2024-04-20 205533](https://github.com/DEEPAK22003907/creating-a-backdoor-with-SET/assets/119404520/e3cc1840-2207-41f2-b81b-74416440134f)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

# ![Screenshot 2024-04-20 205614](https://github.com/DEEPAK22003907/creating-a-backdoor-with-SET/assets/119404520/4a6e98ba-8ccc-4f57-9685-a640606b71be)

SET logs the information regarding the Google credentials:

# ![Screenshot 2024-04-20 205657](https://github.com/DEEPAK22003907/creating-a-backdoor-with-SET/assets/119404520/dfb093b5-d835-4661-b554-5b39d10157e8)

SET logs the information in the xml file under /root/.set directory:

# ![Screenshot 2024-04-20 205746](https://github.com/DEEPAK22003907/creating-a-backdoor-with-SET/assets/119404520/3406e19d-25d0-4c66-9360-b4a7b62b111c)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
