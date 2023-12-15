# Opdrachten

power aps link temp;Webkoppeling
https://apps.powerapps.com/play/e/default-e2940b66-1f59-4d50-9e95-e55f0723c284/a/38c07de1-7a65-48ce-a710-575da74e3160?tenantId=e2940b66-1f59-4d50-9e95-e55f0723c284&hint=37021a9e-7ba9-4448-b6d6-60a9d81b8243&sourcetime=1702641995038



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
  
</details>
