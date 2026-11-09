# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev14.5

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14.5/LAN_Blaster_0.1.0-dev14.5_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev14.5) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14.5/LAN_Blaster_0.1.0-dev14.5_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev14.5

- Ny illustrerad spelgrafik för Crossroads, Rings, Docks, Garden, Cavern, Factory, Portals och Switchyard. Samma bilder används i spelet och banförhandsvisningarna.
- Transportband visar sin rörelseriktning, portaler sina par och grindar öppet, stängt och väntande stängning.
- Åtta valbara figurer: Ranger, Runner, Knight, Wizard, Engineer, Robot, Astronaut och Pirate. Fyra riktningar, gångsteg och 16 accentfärger. Välj Character i startmenyn eller Player / team i LAN-lobbyn. Valet sparas lokalt. Figurerna har samma spelegenskaper.
- Egen LAN Blaster-ikon för spelfönstret och Windows-programfilen.
- Ditt aktuella antal liv visas tydligt ovanför din figur, även medan figuren blinkar efter skada. Sköld visas separat. Sista livet får en gul markering.
- Player Statistics efter avslutad match visar vinnande lag och figurer samt alla spelares lagda bomber, kills, dödsfall, tagna pickups, förstörda block, självmord och lagträffar.
- Statistikräknarna kommer från värdens spelhändelser, följer med genom Deathmatch-respawn och nollställs vid ny match. Mystery räknas som en pickup; mynt och köp räknas separat. Dödsfall avser utslagning, inte förlust av enskilda hjärtan.
- Quantum Bomb, Q-inventory, bonuspåfyllning, Slow, Rules och förmatchbutiken från tidigare versioner finns kvar.

## Begränsningar

- Utvecklingsversion. Alla datorer behöver samma version. LAN över riktigt hemnätverk och det visuella intrycket behöver fortfarande provas av spelare.
- Banornas planlösning, kollisioner och befintliga specialfunktioner är oförändrade. Vattengolvet i Docks är gångbart.
- Fyra lag och upp till 16 spelare stöds. Matchresultatet grupperas efter lag och behåller tydliga spelarnummer.
- Windows kan ibland behålla en gammal ikon i sin cache för en tidigare genväg. Skapa vid behov en ny genväg till den nya versionens programfil.

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

