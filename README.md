# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev14

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14/LAN_Blaster_0.1.0-dev14_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev14) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14/LAN_Blaster_0.1.0-dev14_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev14

- **Team Deathmatch:** två eller fyra lag, med stöd för fyra lag à fyra människor/botar. Standard är först till 40 poäng eller högst poäng efter åtta minuter. Lag som delar högsta poäng delar segern.
- **Respawn:** fyra sekunder efter sista livet återkommer du på en säker ledig ruta i lagets startområde. Du får två sekunders tydligt markerat skydd. Första Bomb-trycket avslutar skyddet utan bomb; släpp och tryck igen för att anfalla.
- **Nytt startpaket vid återkomst:** två bomber, räckvidd två, grundfart och matchens valda antal liv. Personlig statistik behålls. Tidigare bomber ligger kvar med samma ägare; gamla knapp- och rörelsekommandon får inte styra nästa framträdande.
- **Tydlig lagpoäng:** motståndarutslagning +1, självsprängning −1 och lagkamratsutslagning −1 när friendly fire är på. Skada utan utslagning ger inga poäng. Poängen kan bli negativa.
- **Valbar återbildning av block:** originalblock kan återkomma efter 30 sekunder med två sekunders gul varning. Upptagna eller osäkra rutor väntar. Ursprunglig tålighet återställs, utan nya dolda bonusar. Av som standard.
- **Team Deathmatch-regelpaket** i matchinställningarna, lagkapacitet, botstöd, nedräkning till återkomst och delad seger i resultatrutan. Ingen butik eller kollaps i Deathmatch. Klassisk utslagning finns kvar.
- **README och startguide uppdaterade för Dev14.** Musiken behålls från Dev13.2; mer åtskilda banteman tar vi i en senare lyssningsrunda. Capture The Flag och byggvapnet ligger kvar i Dev15.

För att prova: öppna **Practice rules → Rule presets → Team Deathmatch → Load selected preset → Apply settings**, välj 16 deltagare och starta Practice. Block respawn slås på separat längre ned i reglerna. På LAN väljer värden samma regelpaket, lägger till önskade botar och kontrollerar Auto teams. Gäster trycker Ready igen efter regeländringar.

Alla datorer i samma LAN-match måste använda **0.1.0-dev14**. Packa upp hela ZIP-filen och behåll LANBlaster.exe och LANBlaster.pck tillsammans.

Detta är en utvecklingsversion med automatiska tester i utvecklingsmiljön. Fysisk Windows, handkontroll, ljudbalans och mänskligt LAN-spel behöver provspelas. Om bara ett lag återstår anslutet avbryts Deathmatch till lobbyn utan tilldelad matchvinst.

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

