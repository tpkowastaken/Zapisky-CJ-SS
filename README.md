# Zapisky-CJ-SS
Zápisky z Češtiny na střední škole od prváku až do čtvrťáku pomocí GFM (Github Flavored Markdown)

# Format
```
# Témata
## <span style="color: #327DC3">**Dělení**</span>
### <span style="color: #6CAA46">**Autoři**</span>

<span style="color: #EC7627">**Díla**</span>

<span style="color: #8422ce">**Pojmy**</span>

<span style="color: #FF6363">**Hodně zmiňované**</span>

<span style="color: #FF0505">**Maturitní četba (doporučená)**</span>

<span style="color: #DBA400">Data</span>

* První bullet
  * Druhý bullet
    * Třetí bullet...

Nadpisy jsou vždy bez bulletů, odsazení posle předchozího obsahu

odsazení u Nadpisů:
## <span style="margin-left: 40px;"> odsazeno o jeden tab
```
jak to vypadá můžete vidět v example.md

# Jak přispět?

Nainstalujte si [Visual Studio Code](https://code.visualstudio.com/Download)

Nainstalujte si [git](https://git-scm.com/download/win)

Poté ve VS code zmáčkněte ctrl+shift+p
a napište tam: gitcl

a poté zkopírujte link: https://github.com/tpkowastaken/Zapisky-CJ-SS, vyberte si lokaci ve které nic nemáte (nová složka ideální)

Nyní máte staženy zápisky. Teď je pro editaci potřeba vytvořit "branch" - vlevo source control (3 kolečka spojená klikatou čárou), tam tři tečky u source control -> branch -> create branch from - potom zadáte váš jakýkoliv název - např. tpkowastaken-hello a vyberete "main"

nyní publish branch a přihlásíte se do githubu - v prohlížeči kliknete na open

teď kliknete na "create fork", allow, open, open

teď můžete editovat jak se vám zlíbí. změny provedete tím, že v source control zadáte jméno změny a pak commit, push changes. Tyto změny jsou pouze ve vaší verzi zápisků.

Extensiony - pro lepší práci jsem si připravil extensiony:

Github pull request and issues

Markdown All in One

(Markdown Paste)

**insert-color-span** od PavelDobCZ23 - instalace není přes marketplace, ale manuální - stáhnete si [vsix soubor](https://mega.nz/file/ms5SgBbS#evWf4CNwX8oW5fwYs2-RPlyZPtHE7wmPWJQGZ3Ccgf4), otevřete si složku stažené (nebo kam jste si dali soubor) a nahoru do navigačního řádku napíšete "cmd". Poté do příkazového řádku vložite: 
```
code --install-extension ./insert-color-span-1.0.0.vsix
```
použití - Po nahrání do vaší verze zápisků si můžete otevřít github (vlevo ve vs code, poprvé je potřeba se přihlásit) a kliknete na první tlačítko v pravo od pull Requests (create a pull request) - vyberete vaší verzi zápisků nahoře a dole zadáte tpkowastaken/Zapisky-CJ-SS
a main (v základu by to mělo být předvyplněné). Pak pojmenujete titulek, co jste změnili, popisek a kliknete na create. Nyní se změny nahrají do hlavních zápisků - Děkujeme!

insert-color-span přidá do menu pravého tlačítka stilizační nabídky pro text (barvičky a odsazení - Trebesin Čj -- Formátování )


Do branche main už musí být všechno odsuď hotovo, v branchi no-colors stačí jen text

Pokud chcete exportovat do html přidejte tyto dva řádky kódu do ```style``` elementu pro dark mode
```
background-color: #1e1e1e;
color: #c4c4c4;
```
