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

[WPL2PresentatieTeam08.pdf](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/15476188/WPL2PresentatieTeam08.pdf)

[WPL2PresentatieTeam08.odp](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/15476201/WPL2PresentatieTeam08.odp)


Voor Werkplekleren 2 was alles ingedeeld in sprints.
![alt text](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/assets/116820758/7586c2a0-863a-43ec-bd34-c2ed9b36dcf6)

### Sprint 1 - Week 1 & 2
Sprint 1, waar we 2 weken de tijd voor kregen bestond uit een individuele opdracht in Amazon Web Service (AWS)

Hier was het de bedoeling dat we in de AWS cloud een server starten met Ubunu Server op geïnstalleerd.
Deze moest een website hosten voor een fictieve school van onze keuze.
Deze website moest dan ook met realistische data voorzien zijn, en publiek toegangkelijk zijn met een SSL geëncrypteerde verbinding (HTTPS in plaats van HTTP)

Deze cloud based webserver moest ook toegangkelijk zijn via een SSH verbinding.
Hier moesten ook manueel SSH keys voor aangemaakt worden.

En het cloudbased netwerk gedeelte moest ook volledig ingesteld worden.
    - Virtuele switches
    - Virtuele router

### Sprint 2 - Week 3 & 4
Vanaf Sprint 2 begon het echte werk.
Hier was het de bedoeling om in groepsverband samen met mede collega studenten een volledig (fictief) school netwerk op poten te zetten van A tot Z.
Vanaf Sprint 2 tot en met Sprint 5 konden we hier dus aan werken. En alles volgens de Agile Scum methode afwerken.

Alles moest ook gedocumenteerd worden in een algemeen [opleverdocument.](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-RobinLambrighsPXL/blob/main/Opdrachten/2023-2024_SNE_WPL2_Team08_Oplevering-compressed.pdf)


Sprint 2 was een vrij korte sprint, en bestond uit 2 weken.


Hier moesten wij volgende punten in orde brengen:
 - Product backlog
 - Trello board
 - Naam vinden voor de fictieve school
 - Logo uitwerken voor de fictieve school
 - Plan van aanpak opstellen in teamverband
 - Sprint backlog
 - Taakverdeling en sprintplanning

Het gehele project moest gemaakt worden in VSphere op de server van PXL zelf.
Hier konden wij dan via een VPN verbinding altijd toegang tot krijgen.

Voor het technische gedeelte bestond sprint 2 uit:
 - VPN en vSphere-connectie installeren
 - Realistische data uitwerken voor in de infrastructuur
 - Netwerkschema uitwerken
    - Subnets en IP-schema's van servers, administratie en leslokalen
    - Overzicht van Firewall-netwerken en interfaces
    - Graphisch uitwerken met duidelijke network ID's
 - Installatie en configuratie van de virtuele machines
    - Windows Server
       - Server 2022 standard met GUI - Engelstalig
    - Windows Desktop
       - Windows 11 - Engelstalig
    - Linux Server
       - Ubuntu Linux Server - Engelstalig
    - Linux Desktop
       - Ubuntu Linux Desktop - Engelstalig
- *Password vault* aanmaken waarin alle wachtwoorden van alle server/*services* systemen en sites in zitten.
 - Templates aanmaken van alle VM's
    - Windows
       - Sysprep
       - Convert to template
 - Firewall installeren
     - Internet toegang op alle netwerken (surfen)
     - DHCP op alle netwerken behalve voor de Servers
        - DHCP voor Reserverd IP adressen
 - ICT-Linux Desktop voor de eerste ICT medewerker

 

### Sprint 3 - Week 5 & 6 & 7

Voor sprint 3 worden volgende punten gevraagd:

1. Een *domain controller*
    - Met als naam WPL08-DC01
    - Vast IP adres
    - *Domain* naam KHH.local
    - Tweede *domain* administrator
    - Windows-klaslokaalpc's op het *domain*
2. Een *secondary domain* controller
    - Windows Server zonder CLI
    - Vast IP adres
    - *Domain controller* in hetzelfde *domain*
    - Installatie door middel van een *PowerShell* script
3. Fileserver op de *secondary domain controller*
    - Met AGDLP
    - Op de Windows clients een schijf (F:) die wijst naar de fileserver
      - Onderverdeling per klas (1A,1B,1C,2A,...) en per vak (Wiskunde, Aardrijkskunde,...)
      - ICT en Leerkrachten hebben schrijfrechten
      - Leerlingen hebben enkel leesrechten
      - Een veilige security configuratie: leerlingen kunnen folders niet verwijderen en kunnen geen beveiligingsinstellingen lezen of wijzigen.
      - Plaats er wat cursusmateriaal en een ISO van *Damn Small Linux* (DSL) op. De ISO is voor de leerlingen voor het maken van VMs
      - Zorg er voor dat op de Windows clients een schijf (Z:) wijst naar een persoonlijke map voor iedere Windows-gebruiker (student, leerkracht, secretariaatsmedewerker, …)
4. Users aanmaken
    - Excel-lijst of een .csv bestand van 200 gebruikers
    - Maak een powershell script dat users uit de lijst gebruikt om automatisch gebruikers aan te maken in het Domein
    - Zorg dat de gebruikers 
      - worden aangemaakt met <voornaam>.<achternaam>@<domainnaam>.local
      - automatisch ingedeeld worden in OU’s en groepen
        - lectoren
        - studenten 1A,1B,1C,2A,2B,...
          - of nog misschien nog een realistischere indeling
        - De ICT-mensen moeten Admin-rechten hebben in het domein
      - Al onmiddellijk een share krijgen (homefolder) met hun login-naam waar enkel zijzelf rechten in hebben (bestanden/mappen toevoegen, wijzigen en deleten)
        - idem ook de ict-mensen
        - idem ook de lectoren
      - een vast wachtwoord “Sne2324!” krijgen en dat de users dit wachtwoord tijdens de eerste login dienen aan te passen. 
        - Het wachtwoord moet complex zijn.
>- EXTRA: Het script genereert een random paswoord met 8 karakters, incl. Minimum 1 hoofdletter, speciaal karakter en cijfer. 
>     - Extra: De gegenereerde paswoorden worden ook automatisch aangevuld in het Excel bestand. 
5. Zorg dat de Linux Desktops van de klaslokalen gekoppeld zijn aan Active Directory
    - Zorg er voor dat de studenten kunnen inloggen op alle Linux Desktops via hun Active Directory account
      - Zorg er ook voor dat ze bij het inloggen op Linux geen domain moeten meegeven
      - tip: sssd  
    - Zorg er ook voor dat er automatisch een homefolder wordt aangemaakt op de Linux Desktop voor die AD-gebruiker tijdens de eerste login
    - Zorg er voor dat de Z-schijf van die gebruiker ook automatisch gemount wordt als directory ergens in de homefolder van de user
      - tip: libpam-mount en cifs-utils
      - tip: werkt waarschijnlijk pas vanaf tweede login met een bepaalde user

6. Zoek uit wat bginfo is en implementeer op alle Windows machines. 
    - Zorg ervoor dat de informatie op de achtergrond wordt vernieuwd telkens een (nieuwe) user opnieuw inlogt.

7. Zorg voor Roaming profiles voor de leerkrachten, de mensen van het secretariaat en de directeur.

8. Zorg er voor dat game-,gamble- en porn-sites geblokkeerd worden 
Gebruik hiervoor Pi-hole

9. Implementeer LAPS. 
    - Zorg er voor dat het paswoord van de local administrators van Windows clients dagelijks gewijzigd worden naar een nieuw random paswoord. 

10. Cisco opdracht:
    - Je creëert een grondplan van je schoolgebouw op basis van je reeds ontvangen opdracht van WPL2. 
      - Hierop baseer jij je fysiek netwerkplan.
    - Je krijgt heel wat voorwaarden waaraan je oplossing moet voldoen. Bij elke voorwaarde die niet voldoet worden punten afgetrokken. 
    - Je werkt je fysiek netwerkplan uit tot een logisch netwerkplan in Packet Tracer. 
    - Je krijgt 1 netwerkID toegewezen (172.16.0.0/16) en door middel van VLSM zorg je dat elk lokaal een eigen network ID heeft. 
    - Je gebruikt technologieën zoals VLANs, routing en eventuele andere technologieën om een zo sterk mogelijke oplossing te brengen. 
    - Deze oplossing licht je toe in een apart opleverdocument “GroepX- Cisco Assignment.docx” en verdedig je via een demo op het einde van week 9.

### Sprint 4 - Week 8 & 9 & 10

Opgave sprint 4:
1. Zorg voor een Windows-DNS server die een forward- en reverse- lookupzone hebben met records van alle PC's
    - Zorg dat je intranet-website bereikbaar is via de url intra.domeinnaam.local

2. Zorg op een Linux-server voor een Publieke Website om de school bekend te maken aan de buitenwereld
    - Zorg dat de website bereikbaar is 
      - via een DNS naam (in jouw DNS-server)
      - over SSL/TLS
    - Dit puntje heb je reeds individueel verwezenlijkt in AWS Cloud, MAAR nu
      - kopieer je de code van de AWS-webserver naar deze webserver
      - Probeer je de beste website van jullie team zo volledig mogelijk aan het werk te krijgen over SSL/TLS op een Oracle-Linux in de vSPhere-omgeving
      - De Webserver mag je zelf kiezen
      - De website-data moet staan in de map  /data/websites/(naam van de school)
      - Zorg dat SELinux en Firewalld nog steeds actief zijn en correct ingesteld!

3. Zorg op de klaslokaalpcs voor een Personal Firewall
    - In Linux met ufw/firewalld en in Windows via Defender Firewall zodat
      - studentenpc's onderling niet naar elkaar kunnen communiceren
      - studentenpc's wel kunnen communiceren naar de leerkrachtenpc
        - voor ftp

4. Zowel de Windows-leerkrachtenpcs als de Linux-leerkrachtenpc moeten voorzien worden van een FTP-server waar studenten enkel files kunnen van downloaden en de leerkrachten ook kunnen naar uploaden.

5. Zorg voor (harde) quota's op de homefolders (Z-schijf), zodanig dat de homefolder van een leerling beperkt wordt. Gebruik File Server Resource Manager om volgende instellingen toe te passen op de fileserver:
    - Elke student kan max 100MB opslaan op de fileserver, leerkrachten hebben onbeperkte opslag
      - Geef een melding aan de student wanneer hij 90% van zijn opslag bereikt heeft via een melding
      - Sta niet toe om meer dan 100% op te slaan
    - Beperk alle gebruikers tot het uploaden van video en audiobestanden. Test dit door een mp3 en mp4 bestand te proberen uploaden. Geef een melding aan de gebruiker en plaats een entry in het logboek. Zoek deze melding en documenteer dit.

6. Zorg voor een LMS dat gekoppeld is aan de Active Directory. Op dit LMS systeem moeten de lectoren cursusmateriaal kunnen plaatsen en de punten kunnen bijhouden van de leerlingen. De leerlingen moeten dan het cursusmateriaal en hun punten kunnen raadplegen.

>Extra: Zorg er voor dat de klaslokaalpc's zichzelf uitzetten om 18:00 s' avonds

### Sprint 5 - Week 11 & 12 & 13

1. Gebruik een monitoring tool die alle servers en services monitort. 
    - Alles moet degelijk gemonitord worden zodat direct kan worden ingegrepen bij problemen. 
    - Zorg dus voor een monitorsysteem dat via een Dashboard alles duidelijk toont.
    - Je mag kiezen uit een aantal monitoring tools zoals 
      - Paessler PRTG 
      - Datadog
      - Nagios
      - …. (vergelijkbaar met bovenstaande tools)

2. Kies een backup tool die je vm’s backupt. Met deze tool kan je volledige virtuele machines backuppen. Gebruik deze tool om slechts 1 vm te backuppen (wegens plaatsgebrek), maar zorg wel dat je je voorziet op een geheel backup van alle vm’s. Zorg dat deze backup tool exporteert naar een ander station (D-schijf op backup-server). Enkele interessante backup tools zijn
    - Veeam Backup & Replication
    - Solarwinds Virtualization manager
    - Altaro VM Backup
    - ….

3. Zorg op een Windows-server voor een intranet-site voor alle gebruikers waarop ze moeten inloggen bij het surfen naar de pagina. Na controle van hun username en wachtwoord via Active Directory komen ze op de homepage terecht van de intranet-site. Maak gebruik van een HTML/CSS-template site om deze intranet-site authentiek te laten lijken. Zorg dat deze website over SSL/TLS bereikbaar is via de link intranet.schoolnaam.be. Gebruik hiervoor een nieuwe Forward Lookup Zone.
Zorg er voor dat deze site niet toegankelijk is voor studenten, wel voor het andere personeel!

4. Zorg voor onderstaande instellingen via Group Policies voor de Windows-leslokaalpc's
Vaste achtergrond van de school
Blokkeren van alle mogelijke aanpassingsmogelijkheden van het besturingssysteem voor leerlingen.
Toegang ontzeggen tot C-schijf en control panel voor elke leerling.
Koppelen van persoonlijke folder 
Leerkrachten en personeel zijn altijd lokale admin, maar GEEN domeinadmin! 
Homepagina instellen voor de webbrowsers
Leerlingen kunnen enkel tijdens de schooluren inloggen
Zorg dat alle profielen automatisch gewist worden na afloggen (non-cached roaming profile).

5. De ICT-dienst wil ook een HelpDesk-ticketing-systeem
Zorg dat de website bereikbaar is 
    - via een DNS naam
    - over SSL/TLS

Download  [hier](https://github.com/PXL-Digital-SNE-Werkplekleren/portfolio-froidmontaaron/files/15474914/2023-2024_SNE_WPL2_Team08_Oplevering-compressed.pdf)het volledige opleverdocument.

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


