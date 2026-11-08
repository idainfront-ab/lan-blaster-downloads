# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev12

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev12/LAN_Blaster_0.1.0-dev12_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev12) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev12/LAN_Blaster_0.1.0-dev12_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev12

- Tydlig WEAPON-panel med stor ikon, NORMAL/TIMEBOMB/REMOTE, markerat val och kontroller. Q ger återkoppling och förklarar när bytet är spärrat. Släppt bombknapp behandlas före vapenbyte även när det sker mellan två fysiksteg.
- Bomb kick och Bomb throw som bonusar och butiksköp. Sparka genom att gå mot en normalbomb; E / handkontroll Y kastar en egen normalbomb upp till två rutor. Stubin och ägare behålls; landningen markeras.
- Tre mekanikbanor i alla tre storlekar: Factory (transportband), Portals (parade portaler), Switchyard (knappar/portar).
- Botarnas första spark-/kasttaktiker och terränganpassade vägval/prognoser.
- Välj vilka banor som ingår i rotation/röstning och rösta under den befintliga resultatpausen. En röst per människa, inga botröster.
- Levande förhandsvisning av valt Practice-banval på startsidan, med storlek, beskrivning, startplatser och mekanik.
- THE BLAST LIST visar utslagningar denna runda och totalt i matchen bredvid rundvinster. Ledande total markeras; själv-/lagutslagningar ger ingen positiv kredit.
- Fjorton bonusar, tio butiksköp, uppdaterad hjälp och Throw-knapp som kan bindas om. Dev11-regelpaket migreras automatiskt.

Alla datorer behöver Dev12. Packa upp hela ZIP-filen och behåll exe/pck tillsammans. F1 öppnar instruktionerna.

Testversion: mänsklig Windows-/LAN- och balansprovning återstår. Botar kan fortfarande göra misstag, särskilt när andra spelare ändrar en planerad flyktväg. Kast nekas vid för kort kvarvarande stubin och gäller bara egna normalbomber. Internet, återanslutning under match och värdbyte ingår inte.

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

