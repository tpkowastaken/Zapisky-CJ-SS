# Zapisky-CJ-SS

Zápisky z Češtiny na střední škole od prváku až do čtvrťáku pomocí GFM (Github Flavored Markdown)

# [Verze na webu](https://tpkowastaken.github.io/Zapisky-CJ-SS/)

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
## <span style="margin-left: 40px;"> odsazeno o jeden tab</span>
```
jak to vypadá můžete vidět v example.md (barvičky jsou vidět až při konverzi do html)

# Jak přispět?

1. Nainstalujte si [Visual Studio Code](https://code.visualstudio.com/Download)

2. Nainstalujte si [git](https://git-scm.com/download/win)

3. Poté ve VS code zmáčkněte ctrl+shift+p a napište tam: gitcl, zkopírujte tam link: https://github.com/tpkowastaken/Zapisky-CJ-SS a vyberte si lokaci ve které nic nemáte (nová složka ideální)

4. Nyní máte staženy zápisky. Teď je pro editaci potřeba vytvořit "branch"
    * vlevo source control (3 kolečka spojená klikatou čárou) 
    * tam tři tečky u source control -> branch -> create branch from 
    * potom zadáte váš jakýkoliv název - např. tpkowastaken-hell 
    * vyberete "main"

5. publish branch a přihlásíte se do githubu - v prohlížeči kliknete na open

6. teď kliknete na "create fork" a všechno povolíte

7. teď můžete editovat jak se vám zlíbí. změny provedete tím, že v source control zadáte jméno změny a pak commit, push changes. Tyto změny jsou pouze ve vaší verzi zápisků.

## Extensiony 
pro lepší práci jsem si připravil extensiony:

* Github pull request and issues

* Markdown All in One

* (Markdown Paste)

* **insert-color-span** od PavelDobCZ23 - instalace není přes marketplace, ale manuální - stáhnete si [vsix soubor](https://mega.nz/file/ms5SgBbS#evWf4CNwX8oW5fwYs2-RPlyZPtHE7wmPWJQGZ3Ccgf4), otevřete si složku stažené (nebo kam jste si dali soubor) a nahoru do navigačního řádku napíšete "cmd". Poté do příkazového řádku vložite: 
```
code --install-extension ./insert-color-span-1.0.0.vsix
```
## Nahrání do hlavní verze zápisků
 - Po nahrání do vaší verze zápisků si můžete otevřít github extension (vlevo ve vs code logo github, poprvé je potřeba se přihlásit)
 - kliknete na první tlačítko v pravo od pull Requests (create a pull request) - vyberete vaší verzi zápisků nahoře a dole vyberete tento repozitář (v základu předvyplněné)
 - Pak pojmenujete titulek, co jste změnili, popisek a kliknete na create.
-  Nyní se změny nahrají do hlavních zápisků - **Děkujeme!**

## Zhlédnutí aktuálně psaného textu

při čtení textu v .md souborech můžete zmáčknout ctrl+shift+p a markdown: open preview to side - to vám ukáže jak soubor bude vypadat

insert-color-span přidá do menu pravého tlačítka stilizační nabídky pro text (barvičky a odsazení - Trebesin Čj -- Formátování )

Pokud chcete exportovat do html přidejte tyto dva řádky kódu do ```body``` v ```style``` elementu pro dark mode
```
background-color: #1e1e1e;
color: #c4c4c4;
```
