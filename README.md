# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev12.1

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev12.1/LAN_Blaster_0.1.0-dev12.1_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev12.1) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev12.1/LAN_Blaster_0.1.0-dev12.1_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev12.1

- **Factory: Timebomb följer transportbandet**, även medan bombknappen hålls nere. Den behåller ägare och bombtyp och exploderar när knappen släpps.
- **Factory: en ankommande bomb låser inte längre fast spelaren.** Bomben stannar innan den överlappar spelarens utrymme, så att det går att gå undan. Rättningen gäller normalbomber och Timebombs i alla fyra bandriktningar.
- Botarnas faroprognos tar hänsyn till att en Timebomb kan släppas längs transportbandets färdväg.
- **Rätt versionsnyheter visas först** på nedladdningssidans README och i paketets LAS_MIG.md. Nyhetstexten hämtas automatiskt från den aktuella versionens ändringslista.
- Uppdaterad Factory-beskrivning i spelhjälpen och banförhandsvisningen.

Alla datorer i samma LAN-match måste använda **0.1.0-dev12.1**. Packa upp hela ZIP-filen och behåll LANBlaster.exe och LANBlaster.pck tillsammans.

Detta är en felrättningsversion ovanpå Dev12. Automatiska regel- och nätverkstester är genomförda; fortsatt provspelning på fysiska Windows-datorer behövs för spelkänsla och balans. Internetspel, återanslutning mitt i matchen och automatiskt värdbyte ingår inte.

## Kom igång

1. Ladda ner och packa upp hela ZIP-filen till en vanlig mapp.
2. Behåll `LANBlaster.exe` och `LANBlaster.pck` tillsammans. Starta `LANBlaster.exe`.
3. Ange **PLAYER NAME**, välj bana och **2–16 players**, och tryck **Practice** för att testa själv med 1–15 botar. Nio banfamiljer finns, inklusive **Factory, Portals och Switchyard**. Förhandsvisningen visar vald bana. Namnet sparas på datorn. **Practice with coins and shop** provar butiken; handla och tryck Done shopping för start.
4. För LAN: en person väljer **2–16 slots** och **Host LAN game**, sedan rätt nätkort under **HOST ADDRESS TO SHARE** och **Copy IP**. Övriga väljer matchen i listan eller ansluter till värdens lokala IP och samma UDP-port.
5. Alla använder **samma version**. Värden kan lägga till botar, välja två/fyra lag, liv, banlista och banomröstning i Match settings. Alla människor ska vara Ready; botar blir redo automatiskt. Minst två deltagare räcker och alla slots behöver inte fyllas. Butiken erbjuder tio köp för mynt och startar rundan när alla är klara eller efter 30 sekunder. Läs regler och föremål i How to play / F1.

Styr med WASD/piltangenter och använd bomber med mellanslag. Q byter bombtyp och WEAPON-panelen visar valet. E / handkontroll Y använder Bomb throw när förmågan finns. Tangentbordet kan bindas om i hjälpen. Escape öppnar menyn. M tystar eller återupptar musiken. Tangentbord och handkontroll stöds. Musik och ljudeffekter har separata reglage.

Standardportar: UDP **24560** för match och **24561** för lokal upptäckt. Windows kan behöva tillåta spelet på det privata nätverket. En utförligare svensk guide och motorns licenstexter ingår i ZIP-filen.

## Hjälp oss testa

Detta är en utvecklingsversion. Fysiska Windows- och LAN-tester återstår. Rapportera versionsnummer, antal spelare, vad som hände och hur felet går att upprepa. Skicka återkoppling till personen som bjöd in dig till testet.

Spelet använder egen kod, grafik, ljudeffekter och musik. Ursprungliga MasterBlaster-resurser ingår inte. Godot och dess beroenden har separata licenser som följer med paketet.

