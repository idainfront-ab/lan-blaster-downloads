# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev14.3

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14.3/LAN_Blaster_0.1.0-dev14.3_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev14.3) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14.3/LAN_Blaster_0.1.0-dev14.3_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev14.3

- **Första spelbara grafiksteget för Classic:** lugnare grönt gräs, låga grå stenpelare med ljus ovansida, varmt tegel och låg yttermur med sparsam mossa.
- **Tydliga blocktillstånd:** förstärkt tegel är rött; skadat grått tegel har murfogar, stor spricka och kantflisa. Vanligt tegel har en egen varm ton.
- **Sex nya bonusbilder:** Extra bomb, Flame, Speed, Shield, Coin och Mystery har silvergrå ram och enkla starka symboler. Samma bilder används på banan, i butik och guide.
- **Fyra tydliga bombidentiteter:** Normal med reflex/stubin, Timebomb med guldband och timglas, Remote med cyan band/antenn/pil och röd nitförstärkt Superbomb med explosionssymbol. Hållen Timebomb har otänd stubin. Q-inventory visar samma identiteter.
- **Gemensam grafik i hela spelet:** preview och spelvy använder samma resurser. De nya bonusarna och bomberna används på alla nio banor; övriga åtta banors miljöer följer i senare grafiksteg.
- **Dev14.2:s spel kvar:** valbar startbutik i Deathmatch, köpt utrustning vid respawn, bonuspåfyllning, fem specialbomber, Slow, Q-växling och de sex Pulse/Rush-spåren finns kvar.

Prova **Classic** med 2–4, 5–8 och 9–16 deltagare och jämför läsbarheten. Köp och samla förmågor, växla med Q och prova både klassiska rundor och Team Deathmatch.

Byggning, regel-/nätverkstester och bildrendering sker i GitHub Actions. Mänskligt Windows-/LAN-speltest, handkontrollprov, prestandaprov på referensdator och slutlig stilbedömning återstår. Alla i samma LAN-match behöver **0.1.0-dev14.3**. Packa upp hela ZIP-filen och behåll EXE och PCK tillsammans.

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

