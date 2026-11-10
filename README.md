# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev15

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15/LAN_Blaster_0.1.0-dev15_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev15) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15/LAN_Blaster_0.1.0-dev15_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev15

- **Capture The Flag i Practice och på LAN:** två lag, normalt tre flaggpoäng eller tio minuter. Stjäl motståndarens flagga och ta hem den medan din egen är hemma. Lika vid tiden ger oavgjort.
- Flaggor tappas vid död/frånkoppling, återtas genom beröring och går hem automatiskt efter 20 sekunder. Tydliga baser, bärarflaggor och lag-/flaggstatus.
- **BUILD:** ny bonus med egen bild och Q/pad X-val i inventory. Tre laddningar per fynd, max sex. Bomb bygger framför dig efter 0,5 sekunder; två sekunders cooldown. Grön/röd förhandsvisning visar om placeringen går.
- Byggda block tål en träff och ligger kvar tills de sprängs. Laddningar försvinner vid död. Ogiltiga placeringar kostar inget; flaggor, spawnplatser och flyktvägar skyddas.
- **Rules** styr CTF, flaggmål/tid, BUILD Off/Low/Normal/High, valbar startbutik, bonuspåfyllning och återbildning av originalblock. Respawn och startbutik använder samma grund som Deathmatch.
- Resultatet visar figurer, vinnande lag, erövrade/återtagna flaggor, bomber, kills, deaths, pickups, förstörda och byggda block. Ommatch nollställer statistiken.
- Alla tidigare 19 figurer inklusive de elva vännerna, nio banteman, Quantum och musikprovet finns kvar i samma vanliga Windows-paket. Oförändrad Godot-programfil, egen fönsterikon och separat LANBlaster.ico.

Prova: Rules → Presets → Capture The Flag → Load selected preset → Apply settings. Välj åtta deltagare för 4v4 eller sexton för 8v8.

Utvecklingsversion: mänskligt Windows-/LAN-provspel, slutlig balans och långtidstest återstår. Alla datorer behöver samma version. Fyra lags CTF, Håll kronan och revansch ingår inte ännu.

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

