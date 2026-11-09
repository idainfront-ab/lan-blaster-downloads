# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev14.2

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14.2/LAN_Blaster_0.1.0-dev14.2_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev14.2) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14.2/LAN_Blaster_0.1.0-dev14.2_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev14.2

- **Valbar butik före Team Deathmatch:** Rules → Match → Shop before match slår på/av en gemensam startbutik. Starting coins väljer 0/3/5/10 mynt. Gäller både Practice och LAN.
- **Aktiv Practice-knapp:** när Deathmatch är valt heter valet Practice with pre-match shop och går att använda. Samma val kan göras i Rules. På LAN väljer värden reglerna, och gäster trycker Ready igen.
- **Handla tillsammans:** matchen börjar när alla är klara eller efter 30 sekunder. Botar handlar och blir redo automatiskt. Ingen shoppingpaus läggs in under pågående Deathmatch.
- **Köpt startutrustning återkommer vid respawn:** uppgraderingar och förmågor du köpt före matchen återställs vid återkomst, inklusive en köpt Shield. Vanliga fynd och laddningar du samlar på banan återställs som tidigare.
- **Rätt grundpaket och köpgränser:** Deathmatch börjar fortfarande med två bomber, räckvidd två och fart fem. Köp läggs ovanpå; max fem bomber, räckvidd sex och fart sju. Inga pengar tas för köp över maxgränsen.
- **Ren ekonomi vid ny match:** nästa Deathmatch ger ny startkassa och nya köpval. Startbutiken använder endast startkassan; mynt och Lucky coin wheel används inte under Deathmatch. Klassiska rundors mynt och mellanrundsbutik finns kvar.
- **Tydligare butik:** startpaketet visas med rätt värden för valt spelläge. De sex nya musikspåren och arsenalen från Dev14.1 finns kvar.

Prova: **Practice rules → Presets → Team Deathmatch → Load selected preset → Match → Shop before match: On → Starting coins → Apply settings**. Starta Practice, eller låt LAN-värden välja motsvarande inställningar före matchen.

Alla i samma LAN-match behöver **0.1.0-dev14.2**. Packa upp hela ZIP-filen och behåll EXE och PCK tillsammans. Automatisk verifiering sker i GitHub Actions; mänskligt LAN-/handkontrollprov och balansbedömning återstår.

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

