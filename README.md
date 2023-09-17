# Zapisky-CJ-SS

Zápisky z Češtiny na střední škole od prváku až do čtvrťáku pomocí markdown/html. Stránka je hostovaná pomocí Jekyll a github pages. Source code a theme pro jekyll je v [jekyll-dark-github-theme](https://github.com/tpkowastaken/jekyll-dark-github-theme)

# [Verze na webu](https://tpkowastaken.github.io/Zapisky-CJ-SS/)

# Format
```
# Témata
## Dělení
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

Pokud je další dělení uvnitř Dělení označuje se modrou barvou bez '##':

## Dělení

* text

<span style="color: #327DC3">**Dělení uvnitř dělení**</span>



Postavy a osobnosti jsou zelenou barvou stejně jako Autoři avšak bez nadpisu: <span style="color: #6CAA46">**Kain**</span> a <span style="color: #6CAA46">**Ábel**</span>



odsazení u Nadpisů:
## <span style="margin-left: 2em"> odsazeno o jeden tab</span>
```
v .md souborech můžete využívat i syntaxu html pro pokročilejší stylizaci
jak to vypadá můžete vidět v [example](https://cj.trebesin.fun/example.html) - barvičky nejsou vidět na githubu, jsou vidět pouze na stránce

## Zápisky jsou užitečné i bez stylizace. stylizaci klidně doděláme my, pokud chcete přispět nenechte se tím odradit. editovat můžete přímo i tady v prohlížeči na githubu

# Jak přispět?

Buďto upravujte přimo v prohlížeči a poté postupujte podle instrukcí a vytvořte pull request do 'main'

Nebo

1. Nainstalujte si [Visual Studio Code](https://code.visualstudio.com/Download)

2. Nainstalujte si [git](https://git-scm.com/download/win)

3. Poté ve VS code zmáčkněte ctrl+shift+p a napište tam: gitcl, zkopírujte tam link: https://github.com/tpkowastaken/Zapisky-CJ-SS a vyberte si lokaci ve které nic nemáte (nová složka ideální)

4. Nyní máte staženy zápisky. Teď je pro editaci potřeba vytvořit "branch"
    * vlevo source control (3 kolečka spojená klikatou čárou) 
    * tam tři tečky u source control -> branch -> create branch from 
    * potom zadáte váš jakýkoliv název
    * vyberete "main"

5. publish branch a přihlásíte se do githubu - v prohlížeči kliknete na open

6. teď kliknete na "create fork" a všechno povolíte

7. teď můžete editovat jak se vám zlíbí. změny provedete tím, že v source control zadáte jméno změny a pak commit, push changes. Tyto změny jsou pouze ve vaší verzi zápisků.

8. Pull request do tohoto repozitáře můžete udělat buďto přímo na githubu nebo přímo ve vscode (popis toho je o kousek níže). Děkujeme!

## Jak psát zápisky?

* Pokud si přejete udělat nové téma stačí vytvořit soubor s koncovkou .md ('jmenovasehonovehotematu.md') a první řádek musí být nadpis a jméno vašeho tématu. Zbytek už je na vás.
* Tento soubor musí být buďto v jedné ze složek nebo v nové složce v hlavní directory (/Moderní Literatura/literatura 19.st/renesance.md) 👎 (/Moderní Literatura/Renesance.md) 👍

## Extensiony 
pro lepší práci jsem si připravil extensiony:

* [Github pull request and issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) - obecně se hodí pro práci s githubem a povolí nám vytvořit pull request rovnou z vscode později v textu

* [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) - přidá vám open preview to the side možnost v ctrl+shift+p - tato nabídka vám dovoluje sledovat jak soubor bude vypadat v reálném čase

* [Markdown Paste](https://marketplace.visualstudio.com/items?itemName=telesoho.vscode-markdown-paste-image) - pomocí ctrl+alt+v můžete vkládat obrázky nebo text s formátováním rovnou třeba z onenotu

* [**insert-color-span**](https://github.com/tpkowastaken/Zapisky-CJ-SS/releases/download/v1.0.0/insert-color-span-1.0.0.vsix) od PavelDobCZ23 - instalace není přes marketplace, ale manuální - stáhnete si [vsix soubor](https://github.com/tpkowastaken/Zapisky-CJ-SS/releases/download/v1.0.0/insert-color-span-1.0.0.vsix), otevřete si složku stažené (nebo kam jste si dali soubor) a nahoru do navigačního řádku napíšete "cmd". Poté do příkazového řádku vložíte: 
```
code --install-extension ./insert-color-span-1.0.0.vsix
```
## Nahrání do hlavní verze zápisků
 - Po nahrání do hlavní verze zápisků si můžete otevřít github extension (vlevo ve vs code logo github, poprvé je potřeba se přihlásit)
 - kliknete na první tlačítko v pravo od pull Requests (create a pull request) - vyberete vaší verzi zápisků nahoře a dole vyberete tento repozitář (v základu předvyplněné)
 - Pak pojmenujete titulek, co jste změnili, popisek a kliknete na create.
-  Nyní se změny nahrají do hlavních zápisků - **Děkujeme!**

## Zhlédnutí aktuálně psaného textu

při čtení textu v .md souborech můžete zmáčknout ctrl+shift+p a markdown: open preview to side - to vám ukáže jak soubor bude vypadat

insert-color-span přidá do menu pravého tlačítka stylizační nabídky pro text (barvičky a odsazení - Trebesin Čj -- Formátování ). To použijete tak, že označíte text a poté vyberete stylizaci (například pro autora). Extension vám následně aplikuje stylizaci v podobě <span> elementu.

# Forkování tohoto projektu

Pro Lepší orientaci v souborovém systému jsem se rozhodl jekyll soubory (a soubory související s formátováním markdownu a stránky jako takové) oddělit do [druhého repozitáře](https://github.com/tpkowastaken/jekyll-dark-github-theme). Pokud chcete spustit tuto stránku na své doméně, případně ji upravit nebo vylepšit a udělat pull request musíte se nejdřív držet těmito instrukcemi:

1. Forkněte si oba repozitáře
2. v [config.yml](https://github.com/tpkowastaken/Zapisky-CJ-SS/blob/7bdd493ec43850e70cc17935f842d0efb44ab6ba/_config.yml#L38-L40) v repozitáři se zápisky upravte vaše url pro přístup ke stránce (pokud nemáte vlastní doménu bude vypadat asi takto: https://vasejmenonagithubu.github.io/jmeno_repozitare, odkaz na vas repozitar a branch, kam chcete odkazovat lidi, co kliknou na edit on github
3. v [build.yml](https://github.com/tpkowastaken/Zapisky-CJ-SS/blob/7bdd493ec43850e70cc17935f842d0efb44ab6ba/.github/workflows/build.yml#L102-L106) ve workflows upravte odkaz na repozitář s jekyll soubory
4. v [build.yml](https://github.com/tpkowastaken/Zapisky-CJ-SS/blob/7bdd493ec43850e70cc17935f842d0efb44ab6ba/.github/workflows/build.yml#L93-L99) ve workflows upravte informace na vaše údaje na githubu a odkaz na druhý repozitář (secrets.TOKEN zanechte)
5. v nastavení repozitáře se zápisky přidejte secret v Security->Secrets and variables->actions->new repository secret
6. secret pojmenujte 'TOKEN'
7. do pole Secret vložte token vašeho účtu - ten získáte v nastavení vašeho profilu -> developer settings (uplne dole v menu vlevo) -> personal access tokens -> a vygenerujte si token (token musí mít právo editovat repozitář se zápisky)
8. v nastavení repozitáře vyberte pages a pod build and deployment zvolte github actions
9. Vložte svojí doménu pod nebo nechte prázdné
10. v repozitáři klikněte na actions a spusťte build.yml

Vaše stránka se zkompiluje a bude brzy dostupná na vaši adrese 👍
