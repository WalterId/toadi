# eeve_maaier_wilg
HomeAssistant-integratie voor het bedienen van een EEVE Willow grasmaaier.
# EEVE Mower Willow-integratie voor Home Assistant

![ Integratievoorbeeld ] ( https://github.com/flame4ever/eeve_mower_willow/blob/main/Example.png )

Met deze integratie kunt u uw EEVE Mower Willow rechtstreeks vanuit Home Assistant verbinden en bedienen. Door uw EEVE Mower Willow te integreren met Home Assistant, kunt u de status ervan controleren, de locatie ervan volgen en de werking ervan op afstand bedienen.

## Functies

-  ** Accubewaking ** : Controleer het huidige accuniveau van uw grasmaaier.
-  ** Activiteiten volgen ** : Houd de huidige activiteit van uw grasmaaier in de gaten, bijvoorbeeld of deze aan het maaien is, aan het docken is of in het laadstation staat.
-  ** Scheduler Status ** : Bekijk de geplande activiteiten van de maaier.
-  ** GPS-tracking ** : Volg de realtimelocatie van de maaier met breedtegraad, lengtegraad en nauwkeurigheid.
-  ** Netwerkinformatie ** : Krijg gedetailleerde informatie over de netwerkstatus van de grasmaaier, inclusief de sterkte van het wifi-signaal, SSID en verbindingsstatus.
-  ** Mobiele netwerkstatus ** : Controleer de mobiele netwerkstatus en de redenen voor verbroken verbindingen.
-  ** Bedieningsknoppen ** : Gebruik de knoppen om de maaier opnieuw op te starten of te stoppen.
-  ** Schakelaars ** : Bedien de functies van de maaier, zoals het starten en stoppen van het maaien en het terugsturen van de maaier naar het dok.

## Installatie

### Handmatige installatie

1. **  Download de integratie ** : Download de integratiebestanden uit de GitHub-repository.
2. ** Toevoegen aan aangepaste componenten ** : Plaats de gedownloade bestanden in de map  ` custom_components/eeve_mower_willow` in uw Home Assistant-configuratiemap.
3. **  Home Assistant configureren ** : Voeg de EEVE Mower Willow-integratie toe aan uw Home Assistant-configuratie .

### HACS-installatie

1. **  Open HACS ** : Ga naar de Home Assistant Community Store (HACS) in uw Home Assistant-gebruikersinterface.
2. ** Aangepaste repository toevoegen ** : Klik op het menu met  de drie puntjes in de rechterbovenhoek en selecteer "Aangepaste repositories".
3. **  Voer de URL van de repository in ** : Voeg de volgende URL toe: ` https://github.com/flame4ever /eeve_mower_willow` en selecteer de categorie als "Integratie".
4. ** Integratie installeren ** : Nadat u  de aangepaste repository hebt toegevoegd, zoekt u in HACS naar "EEVE Mower Willow" en installeert u deze.
5. ** Start Home Assistant opnieuw op ** : Start Home Assistant na de installatie opnieuw op om de wijzigingen toe te passen . 

## Configuratie

Volg deze stappen om de EEVE Mower Willow-integratie te configureren:

1. **  Integratie toevoegen ** : Ga naar de Home Assistant UI en navigeer naar ` Configuratie` > ` Integraties` . Klik op de ` + ` knop om een ​​nieuwe integratie toe te voegen en zoek naar "EEVE Mower Willow".
2. ** IP-adres invoeren ** : Voer het IP -  adres van uw EEVE Mower Willow en andere vereiste configuratiegegevens in.
3. ** Opslaan  en opnieuw opstarten ** : Sla de configuratie op en start Home Assistant opnieuw op om de wijzigingen toe te passen.

## Sensor-entiteiten

De integratie biedt de volgende sensorentiteiten:

-  ` sensor.<mower_name>_battery ` : Batterijniveau van de maaier.
-  ` sensor.<mower_name>_activities ` : Huidige activiteit van de maaier.
-  ` sensor.<mower_name>_scheduler ` : Scheduler-status van de maaier.
-  ` sensor.<maaier_naam>_gps ` : GPS-coördinaten van de maaier.
-  ` sensor.<mower_name>_network_state ` : Netwerkverbindingsstatus van de maaier.
-  ` sensor.<mower_name>_network_default ` : Standaard netwerkverbinding van de maaier.
-  ` sensor.<mower_name>_network_mobile_reason ` : Reden voor het verbreken van de verbinding met het mobiele netwerk.
-  ` sensor.<mower_name>_network_mobile_state ` : Status van de mobiele netwerkverbinding.
-  ` sensor.<mower_name>_network_wifi_local_ip ` : Lokaal IP-adres van de maaier.
-  ` sensor.<mower_name>_network_wifi_reason ` : Reden voor het verbreken van de WiFi-verbinding.
-  ` sensor.<maaier_naam>_network_wifi_signal ` : WiFi-signaalsterktepercentage.
-  ` sensor.<mower_name>_network_wifi_ssid ` : SSID van het aangesloten WiFi-netwerk.
-  ` sensor.<mower_name>_network_wifi_state ` : Status van de WiFi-verbinding.

## Controlerende entiteiten

De integratie biedt ook controle-entiteiten:

-  ` button.reboot_mower` : Start de maaier opnieuw op .
-  ` button.stop_mower` : Stop de huidige werking van de maaier .
-  ` switch.start_mowing` : Start het maaien.
-  ` switch.dock_mower` : Stuur de maaier terug naar het dockingstation.

## Bijdragen

Bijdragen zijn welkom! Als u problemen vindt of suggesties voor verbeteringen hebt, open dan een probleem of dien een pull-aanvraag in op GitHub.

## Licentie

Dit project is gelicentieerd onder de GNU General Public License. Zie het [ LICENSE ] ( LICENSE ) bestand voor details.

## Steun

Voor ondersteuning en vragen kunt u een probleem openen in de GitHub-repository.

---

Door uw EEVE Mower Willow te integreren met Home Assistant, kunt u uw smart home-installatie verbeteren en profiteren van naadloze bediening en bewaking van uw maaier via één enkele interface.
