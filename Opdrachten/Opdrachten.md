# Opdrachten




<details>
<summary>opdrachten wpl 1</summary>



<details>
<summary>POP reflectie opdracht</summary>
[Froidmont_Aaron_reflectie (1).pdf](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/13684123/Froidmont_Aaron_reflectie.1.pdf)
</details>



<details>
<summary>POP takenlijst opdracht</summary>
[Froidmont_Aaron_takenlijst.pdf](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/13684133/Froidmont_Aaron_takenlijst.pdf)
</details>



<details>
<summary>carrièrekompas opdracht</summary>
[Froidmont_Aaron_carrièrekompas.pdf](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/13684141/Froidmont_Aaron_carrierekompas.pdf)
</details>



<details>
<summary>zelfstandig Werk Linux opdracht</summary>
  [WPL1_Zelfstandig_Werk_Linux.pdf](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/13684166/WPL1_Zelfstandig_Werk_Linux.pdf)

</details>



<details>
<summary>basis netwerk config code  </summary>

power aps link temp;Webkoppeling
https://apps.powerapps.com/play/e/default-e2940b66-1f59-4d50-9e95-e55f0723c284/a/38c07de1-7a65-48ce-a710-575da74e3160?tenantId=e2940b66-1f59-4d50-9e95-e55f0723c284&hint=37021a9e-7ba9-4448-b6d6-60a9d81b8243&sourcetime=1702641995038

```
  
# Cisco Router Configuratie

enable
configure terminal

# Hostnaam instellen
hostname Router

# Wachtwoord voor privileged EXEC-modus instellen
enable secret <jouw_geheim_wachtwoord>

# Wachtwoord voor console-toegang instellen
line console 0
password <jouw_console_wachtwoord>
login
exit

# Wachtwoord voor vty (SSH) toegang instellen
username <gebruikersnaam> privilege 15 secret <jouw_ssh_wachtwoord>
line vty 0 4
transport input ssh
login local
exit

# Interface configureren
interface GigabitEthernet0/0
ip address <router_ip> <subnet_mask>
no shutdown
exit

# Cisco Switch Configuratie

enable
configure terminal

# Hostnaam instellen
hostname Switch

# Wachtwoord voor privileged EXEC-modus instellen
enable secret <jouw_geheim_wachtwoord>

# Wachtwoord voor console-toegang instellen
line console 0
password <jouw_console_wachtwoord>
login
exit

# Wachtwoord voor vty (SSH) toegang instellen
username <gebruikersnaam> privilege 15 secret <jouw_ssh_wachtwoord>
line vty 0 4
transport input ssh
login local
exit

# Interface configureren
interface range GigabitEthernet0/1 - 2
switchport mode access
exit

# Cisco PC Configuratie

enable
configure terminal

# Hostnaam instellen
hostname PC

# Wachtwoord voor console-toegang instellen
line console 0
password <jouw_console_wachtwoord>
login
exit

# Wachtwoord voor vty (SSH) toegang instellen
username <gebruikersnaam> privilege 15 secret <jouw_ssh_wachtwoord>
line vty 0 4
transport input ssh
login local
exit

# Interface configureren
interface GigabitEthernet0/0
ip address <pc_ip> <subnet_mask>
no shutdown
exit

# Cisco Server Configuratie

enable
configure terminal

# Hostnaam instellen
hostname Server

# Wachtwoord voor console-toegang instellen
line console 0
password <jouw_console_wachtwoord>
login
exit

# Wachtwoord voor vty (SSH) toegang instellen
username <gebruikersnaam> privilege 15 secret <jouw_ssh_wachtwoord>
line vty 0 4
transport input ssh
login local
exit

# Interface configureren
interface GigabitEthernet0/0
ip address <server_ip> <subnet_mask>
no shutdown
exit

# Opslaan van de configuratie
write memory
```

</details>

<details>
<summary>opdracht gastseminarie "hacking" presenteren </summary>
[hacking.pptx.pdf](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/13702585/hacking.pptx.pdf)

</details>

</details>

***
<details>
<summary>opdrachten wpl 2</summary>

</details>

***
<details>
<summary>opdrachten wpl 3</summary>

</details>

***
<details>
<summary>opdrachten wpl 4</summary>
  
![ezgif com-video-to-gif](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/assets/116820758/dee269b5-7bfb-4674-92ea-2017640211db)
  
</details>

### certificaten

![Screenshot 2023-11-12 183015](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/assets/116820758/0d62e806-4f38-40be-a9d1-6f382244f525)



![Screenshot 2023-11-12 174659](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/assets/116820758/ab7ae9ff-dab8-4fe1-92fa-31e4451324e6)



![Screenshot 2023-11-12 174102](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/assets/116820758/878a05ea-8588-4102-b87c-df5f05834ab7)



![Screenshot 2023-11-12 172349](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/assets/116820758/bde5e5e3-1c4c-4f32-aadb-3e589f6b7e60)



![Screenshot 2023-11-12 165825](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/assets/116820758/d705e288-9066-430d-9794-59731131d1e0)



![Screenshot 2023-11-12 184042](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/assets/116820758/377d46c9-90c6-4e78-8f57-f7bea71d39f3)



</details>




<details>
<summary>individuele certificaten</summary>

  
[English certificate C1-Advanced English](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/13329874/English-certificate_C1-Advanced-English-Level_aaron-froidmont.pdf.1.pdf)



[Diploma in Cyber Security](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/13328765/doc.2.pdf)



[cisco Ethical Hacker](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/13328816/Ethical_Hacker_Badge20231112-29-4gocjk.pdf)



[microsoft certificaat](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/13328764/Coursera.HV84GCDS5F2S.pdf)



[google cyber security certificaat](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/13328767/Coursera_33BULV2ZZBEC.1.pdf)

</details>



<details>
<summary>tryhackme certificaten</summary>

[web fundamentals certificaat](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-ADYYMZEOB4.png)


[jr penetration tester certificaat](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-AVC9WYAXL4.png)


[intro to cyber cecurity certificaat](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-RAVM42RHVU.png)


[pre security certificaat](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-EDKMFWZE57.png)


</details>



<details>
<summary>toekomstige certificaten</summary>


https://www.eccouncil.org/train-certify/certified-ethical-hacker-ceh/


https://www.offsec.com/courses/pen-200/


https://www.isc2.org/Certifications/CCSP


https://www.isaca.org/credentialing/cism?cid=sem_2002363&Appeal=sem


https://www.isc2.org/Certifications/CISSP


https://www.giac.org/certifications/security-essentials-gsec/


https://www.comptia.org/landing/securityplus/index.html


https://www.coursera.org/

</details>


