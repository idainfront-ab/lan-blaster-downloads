# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev11

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev11/LAN_Blaster_0.1.0-dev11_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev11) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev11/LAN_Blaster_0.1.0-dev11_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Kom igång

1. Ladda ner och packa upp hela ZIP-filen till en vanlig mapp.
2. Behåll `LANBlaster.exe` och `LANBlaster.pck` tillsammans. Starta `LANBlaster.exe`.
3. Ange **PLAYER NAME**, välj bland **Classic, Crossroads, Rings, Docks, Garden, Cavern** och **2–16 players**, och tryck **Practice** för att testa själv med 1–15 botar som planerar flykt från bomber och söker användbara bonusar. Namnet sparas på datorn. **Practice with coins and shop** provar den nya butiken; handla och tryck Done shopping för start.
4. För LAN: en person väljer **2–16 slots** och **Host LAN game**, sedan rätt nätkort under **HOST ADDRESS TO SHARE** och **Copy IP**. Övriga väljer matchen i listan eller ansluter till värdens lokala IP och samma UDP-port.
5. Alla använder **samma version**. Värden kan välja bland sex banfamiljer och Cycle all maps under Match settings; förhandsvisningen visar layouten för aktuellt spelarantal. Namn kan ändras med Save name i lobbyn. Minst två anslutna och alla Ready räcker för start; alla slots behöver inte fyllas. Välj Basic/Mixed och Between-round shop i Match settings. Butiken erbjuder åtta köp för mynt och startar rundan när alla är klara eller efter 30 sekunder. Läs regler och föremål i How to play / F1.

Styr med WASD/piltangenter och använd bomber med mellanslag. Q byter bombtyp; tangentbordet kan bindas om i hjälpen. Escape öppnar menyn. M tystar eller återupptar musiken. Tangentbord och handkontroll stöds. Musik och ljudeffekter har separata reglage.

Standardportar: UDP **24560** för match och **24561** för lokal upptäckt. Windows kan behöva tillåta spelet på det privata nätverket. En utförligare svensk guide och motorns licenstexter ingår i ZIP-filen.

## Hjälp oss testa

Detta är en utvecklingsversion. Fysiska Windows- och LAN-tester återstår. Rapportera versionsnummer, antal spelare, vad som hände och hur felet går att upprepa. Skicka återkoppling till personen som bjöd in dig till testet.

Spelet använder egen kod, grafik, ljudeffekter och musik. Ursprungliga MasterBlaster-resurser ingår inte. Godot och dess beroenden har separata licenser som följer med paketet.

## Nytt i dev10

- Mjukare svängar mellan block, efter feedback om att figuren fastnade i hörn.
- **How to play / F1** med regler, alla föremål och omställbara tangentbordsknappar.
- Timebomb och Remote: håll bombknappen, släpp för att spränga. **Q / handkontroll X** byter bombtyp.
- Ghost och Superman, åtta butiksköp, lyckohjul, lag A/B och valbara monster.
- Practice rules / teams / monsters ger tillgång till de nya reglerna vid övning.

Alla i samma LAN-match måste använda dev10. Det är fortfarande en testversion; internetspel och återanslutning mitt i matchen ingår inte.
