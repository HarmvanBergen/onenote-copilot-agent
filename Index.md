## 1. Chocolatey (Choco) – Applicatiebeheer via CMD of RMM

1. 1. Open de opdrachtprompt (CMD) op het systeem van de gebruiker of via RMM > Tools >
1. Command Prompt.
1. 2. Voer één van de onderstaande commando’s uit, afhankelijk van de gewenste actie.
1. Voorbeelden van Choco-commando’s
1. Choco List – Toont een lijst van geïnstalleerde applicaties.
1. Choco install [Applicatie] – Installeert de opgegeven applicatie.
1. Choco uninstall [Applicatie] – Verwijdert de opgegeven applicatie.


## 2. AUTHENTICATOR APP TOKEN

1. 1. Selecteer klant - klant opzoeken.
1. 2. Ga naar 'Gebruikers en groepen' en klik op het account (linker groene veld).
1. 3. Zoek de gebruiker en klik erop.
1. 4. Ga naar '2FA tokens' en klik op het papiertje met pennetje.
1. 5. Gebruik @=mail en i=mail voor tokeninstellingen.
1. 6. Klik op het plusje om de token te verzenden (1 dag geldig).


## 3. WW reset

1. 1. Selecteer klant - klant opzoeken.
1. 2. Ga naar 'Gebruikers en groepen' en klik op het account.
1. 3. Zoek de gebruiker en klik erop.
1. 4. Klik op het tandwiel bij de gebruikersnaam.
1. 5. Selecteer 'Reset password' en kies de gewenste methode.


## 4. WW reset Indien de gebruiker al is ingelogd

1. 1. De gebruiker drukt op Ctrl + Alt + End.
1. 2. Selecteer 'Wachtwoord wijzigen'.


## 5. Wachtwoord wijzigen via link (Cloud klanten)

1. 1. Open een browser (bij voorkeur Chrome of Edge).
1. 1.
1. 2. Ga naar de volgende link: https://cloudadfs.ict-concept.nl/adfs/portal/updatepassword
1. 2.
1. 3. Voer je gebruikersnaam in (bijvoorbeeld: voornaam.achternaam@bedrijf.nl).
1. 3.
1. 4. Voer je huidige wachtwoord in.
1. 4.
1. 5. Voer je nieuwe wachtwoord in en bevestig dit.
1. 5.
1. 6. Klik op 'Submit' of 'Verzenden' om het wachtwoord te wijzigen.
1. 6.
1. 7. Je ontvangt een bevestiging zodra het wachtwoord succesvol is aangepast.
1. 7.
1. Voorbeeldlink
1. https://cloudadfs.ict-concept.nl/adfs/portal/updatepassword


## 6. Email Alias toevoegen

1. 1. Selecteer klant - klant opzoeken.
1. 2. Ga naar 'Gebruikers en groepen' en klik op het account.
1. 3. Zoek de gebruiker en klik erop.
1. 4. Ga naar 'E-mail aliassen' en voeg een alias toe.
1. 5. Pas de primaire alias aan door op het vlaggetje te klikken.


## 7. Iemand rechten geven voor mailadressen

1. 1. Ga naar 'Cloud' en zoek de klant.
1. 2. Ga naar 'Gebruikers' > 'Accounts' (rechts groen).
1. 3. Zoek het profiel van de gebruiker.
1. 4. Klik op het papiertje met pennetje.
1. 5. Zoek de persoon en vink FA/SA/AM aan.
1. 6. Klik op de diskette om op te slaan.


## 8. Server herstarten

1. 1. Ga naar 'Servers en werkplekken' > 'Server overzicht'.
1. 2. Klik op de gewenste server (TS).
1. 3. Klik op 'Pas server aan'.
1. 4. Ga naar 'Power Opties' en kies 'HERSTART'.


## 9. DHCP Command

1. 1. Open de opdrachtprompt (CMD) als administrator.
1. 2. Voer het volgende commando uit:
1. ipconfig /release && ipconfig /renew
1. 3. Controleer of het IP-adres opnieuw is toegewezen.
1. Voorbeeld:
1. ipconfig /release && ipconfig /renew


## 10. Opgeslagen gebruikersnamen en wachtwoorden

1. 1. Open de opdrachtprompt (CMD).
1. 2. Voer het volgende commando uit:
1. rundll32.exe keymgr.dll, KRShowKeyMgr
1. 3. Een venster opent waarin opgeslagen gebruikersnamen en wachtwoorden worden
1. weergegeven.
1. Voorbeeld:
1. rundll32.exe keymgr.dll, KRShowKeyMgr


## 11. Net User Command

1. 1. Open de opdrachtprompt (CMD).
1. 2. Voer een van de volgende commando's uit:
1. - net user
1. - net user "Gebruikersnaam" ""
1. - net user "Gebruikersnaam" "wachtwoord"
1. 3. Controleer of het wachtwoord is aangepast of de gebruiker is weergegeven.
1. Voorbeelden:
1. net user
1. net user "Gebruikersnaam" ""
1. net user "Gebruikersnaam" "Welkom123!"


## 12. EnterpriseDrive – Inloggen op ED

1. Log in op de server.
1. 1.
1. Open een browser.
1. 2.
1. Ga naar localhost:45454.
1. 3.
1. Log in met de bekende gebruikersgegevens (vaak te vinden onder Bijzonderheden >
1. Inloggegevens).
1. 4.
1. Alternatief 1: via online portal
1. Open je browser.
1. 5.
1. Ga naar: https://driveportal.ict-concept.nl/
1. 6.
1. Log in met de bekende gebruikersgegevens (vaak te vinden onder Bijzonderheden >
1. Inloggegevens).
1. 7.


## 13. ESET – Wachtwoord Reset

1. 1. Druk op F1.
1. 2. Gebruik de pijltjestoetsen om "Password Recovery" te selecteren.
1. 3. Voer het recovery-wachtwoord in.
1. 4. Kies een nieuw wachtwoord.
1. Voorbeeld
1. Workstation ID staat onderin het scherm van de gebruiker. Gebruik deze ID in de Encryption
1. Recovery-tool.


## 14. FSLogix – Virtuele Schijven



## 15. Doel



## 16. GateKeeper – Authenticator versturen

1. Open GateKeeper.
1. 1.
1. Gebruik het volgende commando om een Authenticator te versturen:
1. 2.
1. authenticator-add -e 1440 -t Leo@dejongcheese.nl Leo@dejongcheese.nl ""
1. 3.
1. Let op: vervang de e-mailadressen met de juiste ontvangers.
1. 4.
1. Voorbeeld
1. authenticator-add -e 1440 -t richard@prive.nl rhuveneers@ict-concept.nl ""


## 17. GateKeeper – Tunnel opzetten voor MRTG en ConnProbe

1. 1. Klik met de rechtermuisknop op de witte balk in GateKeeper.
1. 2. Kies "Change settings".
1. 3. Klik op het "+" teken bij SSH.
1. 4. Selecteer "Tunnels".
1. 5. Stel de volgende waarden in:
1. - Source: 8888
1. - Destination: localhost:80
1. 6. Voor ConnProbe voeg je "/connprobe" toe achter poort 80.
1. GateKeeper – Tunnel opzetten voor MRTG en ConnProbe
1. dinsdag 2 september 2025
1. 06:00


## 18. 7. Voor MRTG gebruik je alleen poort 80.



## 19. GateKeeper – Netwerksnelheid controleren

1. Open GateKeeper.
1. 1.
1. Voer het commando uit: /operator/milf.
1. 2.
1. Bekijk de netwerksnelheid per aansluiting zoals weergegeven op de pagina.
1. 3.
1. Commando
1. /operator/milf


## 20. Intune – Applicaties installeren via Intune

1. 1. Voeg de gebruiker toe aan de SG 'applicatienaam'. Include vereist.
1. 1.
1. 2. Voor een snelle installatie kan je via Chocolatey (choco) het programma installeren.
1. 2.
1. 3. Zoek de applicatie op in CDB onder het kopje Intune > Applicaties.
1. 3.
1. 4. Daar vind je de install code.
1. 4.
1. Alternatief
1. Indien de installatie via Intune niet werkt, kan handmatige installatie via Chocolatey worden
1. uitgevoerd met behulp van de install code uit CDB.


## 21. 1. Controleer of er een actieve MSI-installatie hangt



## 22. Outlook Agenda synchroniseerd niet in Applicatie

1. Kijk eerst of alle mailboxen en agenda's bijgewerkt zijn in de outlook applicatie
1. onder : Verzenden/ontvangen > Alle mappen verzenden/ontvangen. (Mocht dit
1. niet werken dan > Map Bijwerken.
1. 1.
1. Als stap 1 niet helpt de webmail openen via https://outlook.office.com
1. 2.
1. Open de gedeelde Agenda / Mailbox
1. 3.
1. Zijn hier de wijzigingen wel zichtbaar? Dan ligt het probleem bij Outlook
1. applicatie.
1. 4.
1. Als de mailbox geopend is via de webmail en deze synchroniseert op het
1. moment van openen, eerst kijken of het in de outlook applicatie nu ook
1. synchroniseert.
1. 5.
1. Zo niet : Sluit Outlook
1. 6.
1. Ga naar Configuratiescherm > Mail > Profielen > E-mailaccounts
1. 7.
1. Haal het  vinkje weg bij "Gedeelde mappen in Cache opslaan"
1. 8.
1. Herstart outlook en controleer de agenda
1. 9.

