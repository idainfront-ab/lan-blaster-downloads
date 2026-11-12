# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev16

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev16/LAN_Blaster_0.1.0-dev16_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev16) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev16/LAN_Blaster_0.1.0-dev16_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev16

- **Hold the Crown:** nytt spelläge för alla mot alla eller två/fyra lag. Håll kronan för att samla tid. Standard är tre minuter, 75 procent bärarfart, tappad krona vid oskyddad träff och obegränsade respawns. Rules har poängmål, fart, tappregel, respawntid/skydd och återställning av lös krona. Kronstatistik visas efter matchen.
- **Deathmatch alla mot alla:** individuell poäng, utspridda starter och säkra respawns. Lagvarianten finns kvar. Play style ändrar lagindelningen inom valt spelläge.
- **CTF Standard använder Fortress:** befästa baser, BUILD-reparation, långsammare flaggbärare och stillastående stöld. Vanlig CTF finns kvar som preset och Fortress-delarna kan ändras i Rules.
- **Normal som itemstandard:** nya standardregler har Normal på alla tillåtna föremål. Grundbonusar är fortfarande vanligare än specialvapen. Low/High är relativa frekvenser, inte garantier. Sparade egna frekvenser bevaras.
- **Starkare Cluster och Napalm:** Cluster har större sekundära explosioner som påverkas av Flame. Napalm ger fem laddningar, större räckvidd med Flame och cirka fyra sekunders kvarliggande eld. Befintliga CTF-skydd behålls.
- **Separat detonering:** Space placerar, vänster Ctrl detonerar Time/Remote och Q växlar vapen. Att släppa Space detonerar inte längre. Remote med Fast ignition av börjar sin vanliga stubin vid detonering. Tangenter och handkontroll kan konfigureras; hjälpen är uppdaterad.
- **Mer block:** 75 procent som standard och 90 procent som alternativ. Desert Ruins använder samma täthetsval; centralruin, gångring och startytor bevaras.
- **Tydligare menyer:** fyra spellägeskort, lägesspecifika Rules, Starting health i respawnlägen och en riktig How to play-knapp. Hälsa begränsar inte antalet respawns.
- **Ljud:** separat Test sound effects och Test announcer, enkel Announcer-etikett och fungerande röstförhandsvisning i menyn. Musik är på i nya profiler; egna sparade ljudval respekteras.
- **Ny startsekvens:** godkänd D&J Game Studio-logga i tre sekunder, mjuk övertoning till LAN BLASTER och separat Continue-knapp. Fulla bilder med bevarade proportioner. Mus, Enter/Space och bekräftelse på handkontroll stöds. Introt visas en gång per programstart.
- **Deltagarpresentation:** alla spelare visas före rundan med valda figurer, namn, egen markering och lag. Get ready och Fight använder den valda speakerriktningen. Ingen presentation vid vanlig respawn.
- **LAN-lista:** automatisk sökning och Refresh visar namn, spelläge, bana, platser samt ledig/full/pågående status. Fulla och pågående matcher visas utan Join. Manuell IP och port finns kvar som reserv.
- **Practice-rättning:** Tab följt av Space ska inte kunna aktivera Leave game av misstag. Privat lokal händelselogg hjälper vid fortsatta rapporter om återgång till menyn.

Utvecklingsbygge. Alla datorer i en LAN-match behöver samma version. Balansvärdena är startvärden för provspelning; automatiska kontroller ersätter inte upplevd spelbalans eller ett fysiskt nätverks-/handkontrollprov.

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

