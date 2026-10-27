# Google Search — CS50 Web

Responzivní rozhraní vyhledávače podle [zadání CS50 Web: Search](https://cs50.harvard.edu/web/projects/0/search/). Projekt obsahuje pouze HTML a CSS, bez JavaScriptu, knihoven nebo sestavování.

## Stránky a funkce

- `index.html`: běžné vyhledávání (`q`) a tlačítko **I'm Feeling Lucky** (`btnI`).
- `images.html`: vyhledávání obrázků (`q` a `udm=2`).
- `advanced.html`: všechna slova (`as_q`), přesná fráze (`as_epq`), libovolná slova (`as_oq`) a vyloučená slova (`as_eq`).
- `style.css`: společný vzhled, responzivní rozložení a zvýraznění při ovládání klávesnicí.

Formuláře používají metodu GET a odesílají dotazy na `https://www.google.com/search`. Výsledky zobrazuje Google. U funkce I'm Feeling Lucky může Google zobrazit potvrzení přesměrování; zadání s tím počítá.

## Spuštění

Otevřete `index.html` v prohlížeči. Pro náhled přes lokální server spusťte v této složce:

```sh
python -m http.server 8000
```

Potom otevřete <http://localhost:8000>.

## GitHub Pages

- Repozitář: <https://github.com/VojtechBedan/googlesearch>
- Web: <https://vojtechbedan.github.io/googlesearch/>
- Zdroj publikování: větev `main`, složka `/ (root)`.

Soubor `.nojekyll` umožňuje přímé publikování statických souborů. Odkazy mezi stránkami jsou relativní, takže fungují i v podadresáři GitHub Pages.

## Poznámka

Jde o neoficiální studijní projekt, nikoli službu společnosti Google. Kód byl vytvořen s pomocí AI (OpenAI Codex).
