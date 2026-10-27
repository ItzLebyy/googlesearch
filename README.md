# Google Search — CS50 Web

Responzivní rozhraní vyhledávače podle [zadání CS50 Web: Search](https://cs50.harvard.edu/web/projects/0/search/). Celý projekt používá pouze HTML a CSS, bez JavaScriptu, knihoven a sestavování.

## Stránky a funkce

- `index.html`: běžné vyhledávání (`q`) a odkaz **I'm Feeling Lucky** na Google Doodles.
- `images.html`: vyhledávání obrázků (`q` a `udm=2`).
- `advanced.html`: všechna slova (`as_q`), přesná fráze (`as_epq`), libovolná slova (`as_oq`) a vyloučená slova (`as_eq`).
- `forms.html`: ukázka všech 22 typů input, select, datalist, textarea, output, meter a progress.
- `forms.css`: vzhled formulářové ukázky.
- `citace.md`: zdroje, rozsah použití AI a dostupné prompty.
- `VIDEO.md`: scénář pro vlastní nahrání a odevzdání videa.
- `style.css`: společný vzhled, responzivní rozložení a zvýraznění při ovládání klávesnicí.

Vyhledávací formuláře používají metodu GET a odesílají dotazy na `https://www.google.com/search`. Výsledky zobrazuje Google. Odkaz I'm Feeling Lucky otevírá `https://doodles.google/` nezávisle na obsahu vyhledávacího pole.

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

## Školní zadání

Všechny čtyři stránky odkazují na své HTML a CSS validátory, [citace](citace.md) a portfolio. Validátory pracují s veřejnou verzí na GitHub Pages, proto se nové změny projeví po publikování. Ukázka ve `forms.html` neposílá data: formulář s `method="dialog"` mimo dialog pouze ověří pole a dále nic neprovede. Reset obnoví výchozí hodnoty, nápověda používá `details` a `summary`. Prvek `output` je statická ukázka. [Scénář videa](VIDEO.md).
