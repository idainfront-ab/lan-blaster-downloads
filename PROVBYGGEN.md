# LAN Blaster — separat provbygge

Ordinarie nedladdning finns i [README](README.md). Detta provbygge ersätter inte den ordinarie versionen.

# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev15.3

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15.3/LAN_Blaster_0.1.0-dev15.3_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev15.3) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15.3/LAN_Blaster_0.1.0-dev15.3_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev15.3

Detta är ett provbygge för **Ökenruinen** och **CTF Fortress**. Den ordinarie nedladdningssidan fortsätter länka till Dev15.2.

- Ny egen banfamilj **Ökenruinen** (desert_ruin), med originalpaketets 26 sprites och fasta layouter för 2–4, 5–8 och 9–16 spelare. Välj Ökenruinen och åtta deltagare för huvudprovet 23×17.
- Centralruinen blockerar nio fasta rutor och ritas som ett gemensamt landmärke. Ringen runtom är fri i layouten. Statyhuvudet ligger ovanför/toppen av banan; markmosaik och skärvor saknar kollision.
- Murar och urnor använder ordinarie förstöring, bomber och bonusregler med ett träffsteg. Inga nya fällor, sandbromsning eller miljöförmågor. Den fasta provlayouten ersätter slumpmässig hinderfyllning på just Ökenruinen; brick density ändrar inte dess grundlayout.
- Alla tidigare banor finns kvar. Respawn- och CTF-lägen anpassar basområden enligt vanliga lägesregler; Classic är närmast paketets exakta grundlayout.
- Nytt CTF-regelpaket **CTF Fortress**, tillgängligt via CTF → My presets. Flaggbäraren begränsas till 75 procent av grundfarten, två sprängbara portar skyddar varje flaggrum, och flaggan tar 1,5 sekunder att stjäla från hemmabasen.
- Försvarare kan reparera portarna med befintliga BUILD-laddningar. Det sista utloppet får inte stängas när en spelare står inne i rummet. Spawnplatser är separata från portarna.
- Alla fyra Fortress-inställningar finns separat i Rules: fartbegränsning (Off/75/50%), befästa flaggbaser, portreparation med BUILD och stöldtid (0/1/1,5/2 s). Det tidigare Capture The Flag-paketet behåller de tidigare reglerna.
- Egna regler, gamla regelpaket, figurer, ljud, tangenter, Practice och LAN behålls. Alla datorer behöver samma provversion. Windows-programfilen är fortfarande oförändrad.

Provspela särskilt: kollision vid urnor/murar, rörelse och eld runt centralruinens fyra sidor, spawn och tidig flykt, kontrast för bonusar/eld på sand, botarnas anfall/portreparation samt flaggbärarens fart och lagspel. Alla tidigare specialförmågor finns kvar; deras taktiska balans i Fortress behöver mänskligt provspel. Mänskliga Windows-/LAN- och handkontrollsprov återstår.

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

