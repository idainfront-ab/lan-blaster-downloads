# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev17

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev17/LAN_Blaster_0.1.0-dev17_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev17) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev17/LAN_Blaster_0.1.0-dev17_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev17

- Ny bana: **LAN Party**, med sex datorgrupper, serverrack och LAN-inredning i tre banstorlekar. Fungerar med ordinarie regler, densitet och CTF.
- **Booze Bottle / Tipsy:** 0,5 sekunders varning, fyra sekunders vinglig gång och trögare svängar, därefter sex sekunders flaskimmunitet. Slow finns kvar. Slow, Confusion och Tipsy kombineras eller köas inte.
- **Blast Frenzy:** valbar slutspurt med dubbel/tredubbel bombräckvidd och normal/dubbel skada. Kan användas separat eller tillsammans med Arena collapse. Bara nytillkomna bomber får förstärkningen.
- Egen matchtid och eget positivt Deathmatch-poängmål. Unlimited tar bort tidsgränsen; poängmålet finns kvar.
- **Fullscreen** via inställningarna eller Alt+Enter.
- **Chille och Kim** som valbara karaktärer.
- THE BLAST LIST och resultat visar placeringar, delade placeringar och tydliga lagställningar.
- Förbättrade säkra respawns och återhämtning när botar/autopiloter fastnar.
- Lab: test-/matchtimer, automatisk incident- och rapportinsamling, mer historik, snabbare resursmätning, direkt status-/rapportåtkomst och korrekt status vid avsiktligt stopp.
- Förbättrad Audio/Game menu på mindre skärmar och banomröstning där alla tretton val får plats.

## Testat och kvar att provspela

Det kompletta automatiska byggflödet är godkänt: alla tretton banor i fem lägen både i källspelet och Windows-exporten, nätverksstörningar, start/hjälp/bildformat, automatisk Lab-insamling samt exporter med och utan Lab. Ett nytt fysiskt långtidsprov med åtta datorer, handkontrollskänsla och balansbedömning återstår.

För Lab måste nya **LANBlasterLab.exe** kopieras till värden och varje klient en gång. Sparade parkopplingar behålls. **Update selected** uppdaterar spelfilerna, inte Lab-programmet självt. Låt kontrollprogrammen vara öppna för automatisk övervakning; ständig AI-analys ingår inte.

Detta är samma ZIP och kontrollsumma som det godkända interna Dev17-bygget. Ingen ombyggnad, ompaketering eller ny speltestomgång har gjorts för delningen.

## Kom igång

1. Ladda ner och packa upp hela ZIP-filen till en vanlig mapp.
2. Behåll `LANBlaster.exe` och `LANBlaster.pck` tillsammans. Starta `LANBlaster.exe`.
4. För LAN: en person väljer **Host LAN**, anger matchnamn och **2–16 slots**, och trycker **Create LAN lobby**. Välj sedan rätt nätkort under **HOST ADDRESS TO SHARE** och **Copy IP**. Övriga väljer **Join LAN** och matchen i listan eller ansluter till värdens lokala IP och samma UDP-port.
5. Alla använder **samma version**. Värden kan lägga till botar, välja två/fyra lag, liv, banlista och banomröstning i Match settings. Alla människor ska vara Ready; botar blir redo automatiskt. Minst två deltagare räcker och alla slots behöver inte fyllas. Butiken erbjuder tio köp för mynt och startar rundan när alla är klara eller efter 30 sekunder. Läs regler och föremål i How to play / F1.

Styr med WASD/piltangenter och använd bomber med mellanslag. Q byter bombtyp och WEAPON-panelen visar valet. Vänster Ctrl detonerar Time/Remote-bomber. E / handkontroll Y använder Bomb throw när förmågan finns. Tangentbordet kan bindas om i hjälpen. Escape öppnar menyn. M tystar eller återupptar musiken. Tangentbord och handkontroll stöds. Musik och ljudeffekter har separata reglage.

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

