# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev15.6

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15.6/LAN_Blaster_0.1.0-dev15.6_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev15.6) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15.6/LAN_Blaster_0.1.0-dev15.6_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev15.6

- LAN Lab öppnar nu en lobby där värden själv väljer alla tillgängliga banor, Classic, Deathmatch eller Capture The Flag och spelets vanliga Match settings.
- Open lobby ansluter valda laptoppar. De blir Ready automatiskt, även när värden ändrar regler. Matchen startar först när värden väljer Start match.
- Back to lobby avbryter matchen och samlar samma anslutna spelare för nya banor och regler. Resultatrutan startar inte längre om matchen automatiskt.
- Autopiloterna köper ett tillgängligt föremål i butiken när de har råd, blir klara och deltar i banröstningen. Värdens spelare styrs manuellt tills F8 används.
- Tiominutersgränsen är borttagen. Testet kör tills det stoppas med Stop all eller programmet stängs ordnat.
- Parkoppling sparas skyddat för Windows-användaren på båda datorerna. Laptoppar återansluter med samma parkoppling efter omstart. Forget selected tar bort kopplingen.
- Status och rapporter visar valda regler och aktuell bana. Normal spelstart och möjligheten att bygga helt utan labbstöd bevaras.

Uppdatera LANBlasterLab.exe på både värddatorn och laptopparna genom att packa upp det nya paketet. Gör en första sparad parkoppling i Dev15.6, välj Update selected, invänta Ready och klicka Open lobby. Välj sedan Match settings i värdens spelfönster och Start match. Back to lobby finns i kontrollpanelen.

Autopiloten är en testspelare som rör sig, använder vanliga bomber och följer CTF-mål. Den aktiverar inte alla specialvapen/förmågor själv; använd F8 för riktade manuella prov. Alla tillåtna banor och regelval kan köras, men det är ingen garanti för taktiskt bra spel eller full automatisk täckning av varje föremål.

Laptoppar behöver vara inloggade med styrprogrammet öppet. För stängda lock måste datorerna fortsätta vara vakna på nätström; fysisk funktion, bilddrivrutiner och kylning behöver provas på varje laptop.

## Kom igång

1. Ladda ner och packa upp hela ZIP-filen till en vanlig mapp.
2. Behåll `LANBlaster.exe` och `LANBlaster.pck` tillsammans. Starta `LANBlaster.exe`.
4. För LAN: en person väljer **Host LAN**, anger matchnamn och **2–16 slots**, och trycker **Create LAN lobby**. Välj sedan rätt nätkort under **HOST ADDRESS TO SHARE** och **Copy IP**. Övriga väljer **Join LAN** och matchen i listan eller ansluter till värdens lokala IP och samma UDP-port.
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

