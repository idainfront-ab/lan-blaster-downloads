# LAN Blaster för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator, med Practice och botar. Internet behövs inte när spelet är nedladdat.

## Senaste version: 1.1.0

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v1.1.0/LAN_Blaster_1.1.0_Windows.zip)**

[Versionsnyheter](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v1.1.0) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v1.1.0/LAN_Blaster_1.1.0_Windows.zip.sha256) · [Tidigare versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 1.1.0

- Välj Warm Up, Power Rush, Mayhem, Total Chaos, Fortress Siege eller Crown Rush under **Presets**. Valen anpassas efter spelläget.
- Power Rush, Mayhem och Total Chaos kan spelas på alla tretton banor i Practice och LAN. Hög täthet ger fler block och kompaktare säkra startöppningar.
- I **Customize rules → Match** kan du ställa in täthet upp till 100 %, bonuschans i startblock, återbyggnadstid och intervall för bonuspåfyllning. Bonuschans −1 använder spelarantalets ordinarie chans. Noll stänger av bonusar i startblock. Alla lägen kan använda återbyggnad och påfyllning.
- Värden väljer reglerna för LAN-matchen. Använd samma 1.1.0-paket på alla datorer.

## Kom igång

1. Ladda ner och packa upp hela ZIP-filen till en vanlig mapp. Starta `LANBlaster.exe`; behåll PCK-filen och övriga filer i samma mapp.
2. Välj Practice, eller låt en person skapa en lobby med Host LAN. Övriga väljer Join LAN och matchen i listan. Värdens lokala IP-adress och UDP-port fungerar som reservväg.
3. Alla använder samma version och paketvariant. Välj Match settings, lägg vid behov till botar och gör alla spelare Ready innan matchen startas.

WASD/piltangenter flyttar. Space placerar bomber, Q byter vapentyp och vänster Ctrl detonerar Time/Remote-bomber. E kastar bomber när förmågan finns. F1 öppnar den grafiska hjälpen; tangentbord och handkontroll stöds. Alt+Enter växlar fullscreen. Musik och ljudeffekter har separata reglage.

Standardportar: UDP **24560** för match och **24561** för lokal upptäckt. Tillåt spelet på Windows privata nätverk. Guide och motorns licenstexter finns i ZIP-filen. Denna utgåva innehåller inget Lab-program.

## Ikon på skrivbordet

Skapa en genväg till LANBlaster.exe och välj den medföljande LANBlaster.ico under Egenskaper → Genväg → Byt ikon. Programfilen är den oförändrade Godot-exportmallen; spelets fönster har LAN Blaster-ikonen.

## Återkoppling

Ange version, spelläge, bana, antal spelare och vad som hände när du rapporterar ett problem. Källkod och privata byggloggar publiceras inte här. Godot och dess beroenden har separata licenser som följer med spelet.
