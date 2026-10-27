# Citace a zdroje – Google Search

Autor projektu: Vojtěch Bedan. Doplnění zadání: 27. 10. 2026.

## Použité zdroje

1. HARVARD UNIVERSITY. *CS50 Web: Search* [online]. Dostupné z: https://cs50.harvard.edu/web/projects/0/search/. Zadání původního projektu uvedené v existujícím README; vyhledávání, obrázky a pokročilé dotazy.
2. MDN CONTRIBUTORS. *<input>: The HTML Input element* [online]. [cit. 2026-10-27]. Dostupné z: https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/input. Referenční přehled typů vstupů a jejich atributů při doplnění formulářové ukázky.
3. WORLD WIDE WEB CONSORTIUM. *Markup Validation Service* [online]. [cit. 2026-10-27]. Dostupné z: https://validator.w3.org/. Služba pro kontrolu HTML; odkazy předávají adresu konkrétní stránky.
4. WORLD WIDE WEB CONSORTIUM. *CSS Validation Service* [online]. [cit. 2026-10-27]. Dostupné z: https://jigsaw.w3.org/css-validator/. Služba pro kontrolu CSS; odkazy předávají HTML stránku, aby se kontrolovaly všechny její připojené styly.
5. OPENAI. *Codex* [generativní AI, 2026]. Nástroj použitý k přípravě a úpravě HTML, CSS, JavaScriptu, SVG a dokumentace podle pokynů autora. Nejde o lidského spoluautora ani nezávislý zdroj ověřující správnost kódu.

## Vzhled a podklady

Rozhraní je školní napodobenina vyhledávače Google. Projekt není oficiální službou společnosti Google. Název Google a jeho barevné provedení odkazují na předlohu. Nápis je složen z HTML textu, nejsou použity stažené obrázky loga. Písmo tvoří systémové Arial, Helvetica a sans-serif. Ikona hledání a nová ikona `send.svg` jsou zapsané přímo jako SVG. Nové fotografie ani externí knihovny nejsou použity.

## Rozsah použití AI

Existující README uvádí pomoc OpenAI Codex při původní tvorbě projektu. Při doplnění 27. 10. 2026 AI vytvořila `forms.html`, `forms.css`, `forms.js`, `send.svg`, tuto citaci a návod k videu. Do stávajících stránek doplnila navigaci, odkaz na portfolio a citace a upravila cíle CSS validace. Zachovala vyhledávací formuláře odesílané Googlu. Ukázkový formulář údaje neodesílá ani neukládá.

V samostatném portfoliu AI opravila nefunkční náhled a přejmenovala projekt zpět na Google Search. Náhled je ilustrační SVG vytvořené kódem, nikoliv snímek obrazovky. Autor dodal zadání a rozhoduje o zveřejnění a odevzdání. Nahrání videa a sdílení v Teams zůstává na autorovi.

## Použité prompty

Následná úprava podle pokynu „dont use javascript“ odstranila `forms.js`. Aktuální projekt používá pouze HTML a CSS: nativní validaci a reset, rozbalovací nápovědu a statickou ukázku výstupu.

Níže jsou dostupné pokyny z této konverzace. Starší prompty k původnímu vyhledávači nebyly v dostupných podkladech uvedeny; jejich přesné znění proto není rekonstruováno.

### Požadavek autora (27. 10. 2026)

> 1. fixni náhled na google search, prejmenuj ho zpatky na google search.
>
> dostal jsem zadani na

### Zadání předané AI (27. 10. 2026)

> 1. Vytvořte další stránku v rámci výše uvedeného projektu, která bude obsahovat co největší množství formulářových prvků (input, select, checkbox, radio, textarea, button, …). Formulářové prvky nemusí být funkční. Cílem je ukázat, že umíte vytvořit různé typy formulářů.
> 2. Na všech stránkách projektu budou 2 odkazy na validaci HTML a CSS. Odkazy budou směřovat na validátory: https://validator.w3.org/ a https://jigsaw.w3.org/css-validator/ nastavené tak, aby validovaly kód dané stránky.
> 3. Na všech stránkách projektu bude odkaz na soubor obsahující citace a zdroje, které jste použili při tvorbě projektu. Cílem je ukázat, že umíte správně citovat a uvádět zdroje. Odkaz bude na github.com/vášúčet/googlesearch/citace.md. Citace obsahují použité prompty (nechte to generovat AI, co vám generuje kód).
> 4. V rámci google search projektu budete mít i odkaz na své portfolio.
> 5. Vytvořte video (např. 🪟 + g), ve kterém ukážete, že jste splnili všechny body zadání. Ukazujte web i kód, který se jednotlivých bodů týká. Video sdílejte v rámci zadání v Teams. Pro sdílení videa můžete použít i nástroje ve vašem účtu Microsoft365.

Toto školní zadání autor v konverzaci předal dvakrát; výše je uvedeno jednou bez změny věcného obsahu. Dále poskytl obecné instrukce AGENTS.md: zachovat funkčnost projektu, používat přístupné a responzivní HTML/CSS, nevymýšlet výsledky ověření a omezit nesouvisející změny. Tento odstavec je shrnutí těchto instrukcí, nikoliv doslovný prompt.
