# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev15.8

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15.8/LAN_Blaster_0.1.0-dev15.8_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev15.8) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15.8/LAN_Blaster_0.1.0-dev15.8_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev15.8

## Nytt

- Personliga kill-utrop: First kill per spelare och runda, samt Multi/Mega/Ultra vid 3/5/7 motståndarkills utan egen eliminering. Utropen hörs hos den berörda spelaren.
- Ny speakermix: E minus två halvtoner med nedtonad klang. Wilhelm spelas vid varje eget förlorat liv, även med liv kvar och vid upprepade Deathmatch-dödsfall.
- Ny grafisk F1-hjälp med Weapons & bonuses och Game modes, alla 25 pickups plus normalbomben, riktiga ikoner, aktuella regler och dina valda tangenter. Matchen fortsätter när hjälpen är öppen.
- Nya sammanhängande eldstrålar med kort kosmetisk efterglöd. Räckvidd, utbredning och skadefönster är oförändrade. Classic explosion graphics kan väljas lokalt i Audio / Menu.

## Provspela

Använd samma Dev15.8 på alla datorer. Prova flera liv, Deathmatch-respawn, sköld, personliga utrop och volym/mute. Sköldabsorption ska inte utlösa Wilhelm.

Öppna och stäng hjälpen med F1/Escape under match och granska Napalm, Cluster, Confusion och CTF Fortress. Utförlig hjälp och tangentinställningar finns kvar.

Detta är det befintliga interna Dev15.8-paketet, publicerat utan ombyggnad.

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

