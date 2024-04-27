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

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_24_47](https://github.com/Aishwarya-TM/EH-Ex-7/assets/127846109/17153b77-24d6-440d-9f73-3322158bd004)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_26_14](https://github.com/Aishwarya-TM/EH-Ex-7/assets/127846109/6808c98e-5541-4d30-b6f8-935f9269ce82)

It displays the following menu and select 2 for Website Attack Vectors:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_26_42](https://github.com/Aishwarya-TM/EH-Ex-7/assets/127846109/70fd4900-ab97-4e3e-af6e-43d08c284245)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_27_19](https://github.com/Aishwarya-TM/EH-Ex-7/assets/127846109/aa79af96-d2de-4edf-a4e2-83c9436adcc3)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_27_55](https://github.com/Aishwarya-TM/EH-Ex-7/assets/127846109/18375214-a670-49e8-b1d4-96b093296c0a)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_28_55](https://github.com/Aishwarya-TM/EH-Ex-7/assets/127846109/96070939-01cd-4cf9-9ba0-28cd094c5683)

It shows the following screen in which the option Google can be selected:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_30_00](https://github.com/Aishwarya-TM/EH-Ex-7/assets/127846109/fd90640f-94c9-485e-96eb-399c3a2b258d)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_30_38](https://github.com/Aishwarya-TM/EH-Ex-7/assets/127846109/0e3a4458-01d0-481a-813e-27ad1aa129be)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![VirtualBox_Windows 7_17_04_2024_10_56_06](https://github.com/Aishwarya-TM/EH-Ex-7/assets/127846109/6f650845-ff51-4b08-9713-d2c620f48f48)

SET logs the information regarding the Google credentials:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_38_46](https://github.com/Aishwarya-TM/EH-Ex-7/assets/127846109/460c8252-041e-417d-af93-239dccc8a28c)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/Aishwarya-TM/EH-Ex-7/assets/127846109/d91dbfdf-5df3-44f5-a342-86399a9ddb1d)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
