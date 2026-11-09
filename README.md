# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev14.8

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14.8/LAN_Blaster_0.1.0-dev14.8_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev14.8) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14.8/LAN_Blaster_0.1.0-dev14.8_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev14.8

- Elva nya valbara vänfigurer ingår i det **vanliga Windows-bygget**: Robert, David, Oskar, Douglas, Jack, Agge, Jimmy, Dennis, Egerborn, Sebbe och Malmsten.
- De åtta tidigare hjältarna finns kvar. Totalt 19 val i Character på startsidan och Player / team i lobbyn. Ditt figurval sparas och fungerar i Practice och LAN. Värden kan även välja figur för botar.
- Varje ny figur har alla fyra riktningar och tre poser per riktning: stillastående och två gångposer. Samma bilder används på banan, i karaktärsvalet och i resultatlistan. Ansikten och kläder behåller sina färger.
- Vänfigurerna är samlade och märkta som ett paket för att kunna tas bort i en senare version. Befintliga vanliga figurer och andra vänners sparade val påverkas inte om en vän tas bort.
- Rundstatistik och seriens totalsiffror från Dev14.7 finns kvar. Den oförändrade Windows-programfilen och separata ikonfilen behålls. Bygge, tester och publicering sker i GitHub.

## Begränsningar

- Utvecklingsversion. Alla LAN-datorer behöver samma version.
- Figurerna är kosmetiska och ger inga egna spelmässiga fördelar.
- En senare borttagning ändrar inte redan nedladdade eller publicerade äldre spelpaket.
- Praktiskt provspel på Windows och ett riktigt LAN återstår.

## Kom igång

1. Ladda ner och packa upp hela ZIP-filen till en vanlig mapp.
2. Behåll `LANBlaster.exe` och `LANBlaster.pck` tillsammans. Starta `LANBlaster.exe`.
3. Ange **PLAYER NAME**, välj bana och **2–16 players**, och tryck **Practice** för att testa själv med 1–15 botar. Nio banfamiljer finns, inklusive **Factory, Portals och Switchyard**. Förhandsvisningen visar vald bana. Namnet sparas på datorn. **Practice with coins and shop** provar butiken; handla och tryck Done shopping för start.
4. För LAN: en person väljer **2–16 slots** och **Host LAN game**, sedan rätt nätkort under **HOST ADDRESS TO SHARE** och **Copy IP**. Övriga väljer matchen i listan eller ansluter till värdens lokala IP och samma UDP-port.
5. Alla använder **samma version**. Värden kan lägga till botar, välja två/fyra lag, liv, banlista och banomröstning i Match settings. Alla människor ska vara Ready; botar blir redo automatiskt. Minst två deltagare räcker och alla slots behöver inte fyllas. Butiken erbjuder tio köp för mynt och startar rundan när alla är klara eller efter 30 sekunder. Läs regler och föremål i How to play / F1.

Styr med WASD/piltangenter och använd bomber med mellanslag. Q byter bombtyp och WEAPON-panelen visar valet. E / handkontroll Y använder Bomb throw när förmågan finns. Tangentbordet kan bindas om i hjälpen. Escape öppnar menyn. M tystar eller återupptar musiken. Tangentbord och handkontroll stöds. Musik och ljudeffekter har separata reglage.

Standardportar: UDP **24560** för match och **24561** för lokal upptäckt. Windows kan behöva tillåta spelet på det privata nätverket. En utförligare svensk guide och motorns licenstexter ingår i ZIP-filen.

## Egen ikon på en Windows-genväg

Spelfönstret använder LAN Blaster-ikonen. Själva `LANBlaster.exe` är den oförändrade Godot-programfilen och visar därför Godot-ikonen i Utforskaren. `LANBlaster.ico` följer med som separat ikonfil.

1. Packa upp hela ZIP-filen till den mapp du vill behålla spelet i.
2. Högerklicka på `LANBlaster.exe` och välj **Visa fler alternativ → Skicka till → Skrivbord (skapa genväg)**.
3. Högerklicka på den nya genvägen och välj **Egenskaper → Genväg → Byt ikon → Bläddra**.
4. Välj `LANBlaster.ico` i spelets mapp och tryck **OK → Verkställ**.

Om du flyttar spelets mapp behöver genvägens sökvägar uppdateras eller genvägen skapas igen.

## Hjälp oss testa

Detta är en utvecklingsversion. Fysiska Windows- och LAN-tester återstår. Rapportera versionsnummer, antal spelare, vad som hände och hur felet går att upprepa. Skicka återkoppling till personen som bjöd in dig till testet.

Spelet använder egen kod, grafik, ljudeffekter och musik. Ursprungliga MasterBlaster-resurser ingår inte. Godot och dess beroenden har separata licenser som följer med paketet.

