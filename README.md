# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev13.1

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev13.1/LAN_Blaster_0.1.0-dev13.1_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev13.1) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev13.1/LAN_Blaster_0.1.0-dev13.1_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev13.1

- **Större startknappar längst ned.** Host LAN game och Practice har större text och 64 pixlar höga knappar i botten av startpanelen. Ready och Start match ligger längst ned i lobbyn, med plats för hela deltagarlistan.
- **Mer driv i banmusiken.** Neon Circuit går i 152 BPM och Pixel Rush i 160 BPM, med tätare trummor, extra baspulser och fullt komp genom hela loopen.
- **Musiken ökar när tiden rinner ut.** Under sista minuten stiger tempot gradvis upp till 25 procent. Tonhöjden kompenseras separat från ljudeffekterna. Nästa runda börjar i grundtempo; rundor utan tidsgräns behåller grundtempot. Ökningen följer rundklockan även när du tittar på efter att ha blivit utslagen.
- README och paketets startguide visar den här versionens nyheter. Alla spelregler och Factory-fixar från Dev13 finns kvar.

Alla datorer i samma LAN-match måste använda **0.1.0-dev13.1**. Packa upp hela ZIP-filen och behåll LANBlaster.exe och LANBlaster.pck tillsammans.

Detta är en utvecklingsversion. Musikens tempo och ljudbalans är första provvärden att lyssningstesta på Windows. Respawn och Team Deathmatch planeras till Dev14; Capture The Flag kommer därefter.

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

