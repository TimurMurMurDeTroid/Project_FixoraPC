# FIXORA PC — Style Guide

Vizuálne pravidlá pre web servisu a čistenia počítačov. Smer vychádza z tmavého, minimalistického rozhrania s jemnými linkami, veľkorysým priestorom a jasnou typografickou hierarchiou. Referenčné screenshoty slúžia len ako inšpirácia pre vizuálny štýl; značka, texty a grafické prvky FIXORA PC musia byť vlastné.

## Vizuálny smer

Web má pôsobiť precízne, dôveryhodne a technicky, no nie chladne. Rozhranie necháva vyniknúť reálnym fotografiám počítačov a práci technikov. Dekoratívne prvky používame striedmo: jemné mriežky, tenké deliace čiary a decentné svetelné akcenty sú vhodnejšie než výrazné gradienty alebo množstvo efektov.

## Farebná paleta

| Úloha | Farba | Použitie |
| --- | --- | --- |
| Hlavné pozadie | `#090A0B` | Pozadie stránky a veľkých plôch |
| Sekundárne pozadie | `#101214` | Navigácia, formuláre a zvýraznené sekcie |
| Povrch karty | `#15181A` | Karty a interaktívne bloky |
| Jemný povrch | `#1B1F21` | Hover, vybrané prvky a vnútorné plochy |
| Hlavný text | `#F2F4F3` | Nadpisy a primárny obsah |
| Sekundárny text | `#A1A7A5` | Odseky, popisy a navigácia |
| Tlmený text | `#707875` | Pomocné informácie a metadáta |
| Hranice | `#292E2C` | Okraje kariet, polí a oddeľovače |
| Primárny akcent | `#B7F36B` | Hlavné CTA, odkazy a stavové zvýraznenia |
| Sekundárny akcent | `#7CC7B2` | Jemné technické detaily a doplnkové stavy |
| Chybový stav | `#F07878` | Chyby formulárov a upozornenia |

Akcentné farby majú zvýrazňovať interakciu, nie pokrývať veľké plochy. Na texty a ikony na akcentnom pozadí použi tmavú farbu s dostatočným kontrastom. Stav nikdy neoznačuj iba farbou; doplň ho textom alebo ikonou.

## Typografia

Použi moderné bezpätkové písmo s dobrou čitateľnosťou, napríklad **Manrope** alebo **DM Sans**. Ak externé písmo nie je dostupné, použi systémové bezpätkové písmo. Text má byť kompaktný, prirodzený a bez zbytočne dekoratívnych rezov.

| Prvok | Veľkosť na desktope | Odporúčaný rez |
| --- | --- | --- |
| H1 | `48–64 px` | 600–700 |
| H2 | `32–40 px` | 600 |
| H3 | `22–28 px` | 600 |
| Bežný text | `16–18 px` | 400 |
| Pomocný text | `13–14 px` | 400–500 |
| Štítky a navigácia | `13–15 px` | 500–600 |

Nadpisy drž v krátkych riadkoch s tesnejším riadkovaním. Odsekom nastav riadkovanie približne `1.5–1.7`. Na mobile zmenši H1 približne na `36–44 px`, H2 na `28–32 px` a zachovaj pohodlnú veľkosť bežného textu aspoň `16 px`.

## Navigácia

Navigácia je nízka, nenápadná a prilepená k hornej hrane stránky. Použi tmavý podklad, jemný spodný okraj a vnútornú šírku zarovnanú s obsahom stránky. Vľavo umiestni vlastné logo FIXORA PC; napravo hlavné odkazy, výrazné tlačidlo na objednanie servisu a najužitočnejšie kontaktné údaje.

Na desktope zobraz odkazy v jednom riadku s dostatočnými rozostupmi. Aktuálnu alebo hoverovanú položku odlíš farbou textu alebo jemným akcentom, nie výrazným podčiarknutým blokom. Na mobile ponechaj logo a tlačidlo menu; po otvorení menu sprístupni odkazy aj kontaktné CTA. Každý ovládací prvok musí mať jasný názov a pohodlnú dotykovú plochu.

## Tlačidlá

- **Primárne tlačidlo:** plná akcentná plocha `#B7F36B`, tmavý text, stredne tučný rez. Používaj ho pre hlavné akcie, napríklad objednanie čistenia alebo servisnej diagnostiky.
- **Sekundárne tlačidlo:** priehľadná alebo tmavá plocha, jemný okraj `#383E3B` a svetlý text. Je určené pre doplnkové akcie, napríklad zobrazenie služieb.
- **Hover a focus:** zmeň jas alebo odtieň pozadia a pridaj zreteľný, prístupný focus obrys. Interakcia nesmie závisieť len od zmeny farby.
- Používaj výstižné slovesá, napríklad „Objednať servis“ alebo „Pozrieť služby“. Tlačidlá majú mať výšku približne `44–52 px` a horizontálny padding `18–24 px`.

## Karty a interakcie

Karty služieb, cenníka a referencií používajú povrch `#15181A`, tenký okraj `#292E2C` a vnútorný padding `24–32 px`. Obsah štruktúruj nadpisom, krátkym opisom a prípadne cenou alebo odkazom. Fotografie techniky majú byť ostré, dobre nasvietené a orezané konzistentným spôsobom.

Pri hoveri môže karta mierne zosvetlieť, jej okraj sa môže zvýrazniť a obsah sa môže posunúť najviac o `2–3 px`. Prechody drž krátke, približne `160–220 ms`; vyhni sa prudkému zväčšovaniu a silným žiarivým tieňom. Klikateľná karta musí byť klikateľná celá alebo musí mať jasne označený odkaz.

## Okraje, zaoblenie a tiene

- Štandardný radius kariet a polí: `8–12 px`.
- Radius tlačidiel: `6–8 px`; plne zaoblený tvar používaj iba pre malé štítky alebo kompaktné stavové prvky.
- Okraje: tenké, zvyčajne `1 px`, s nízkym kontrastom voči povrchu.
- Tiene: jemné a široké, napríklad `0 12px 36px rgba(0, 0, 0, 0.24)`, iba ak treba odlíšiť vrstvu od pozadia.
- Vizuálnu hĺbku vytváraj prednostne rozdielom povrchov a okrajov, nie množstvom tieňov.

## Rozostupy a rozloženie

Používaj konzistentnú škálu rozostupov založenú na násobkoch `4 px`: `8`, `12`, `16`, `24`, `32`, `48`, `64` a `96 px`. Medzi väčšími obsahovými sekciami nechaj približne `88–128 px` na desktope a `56–80 px` na mobile. Obsah zarovnaj do spoločného kontajnera so šírkou približne `1120–1240 px`; na menších obrazovkách zachovaj bočné okraje aspoň `20–24 px`.

## Formuláre

Polia formulára majú tmavú plochu `#101214`, okraj `#343A37`, svetlý text a tlmený zástupný text. Použi výšku aspoň `48 px`, radius `8 px` a zreteľný štítok nad poľom. Focus stav zvýrazni akcentným okrajom alebo obrysom. Chybu zobraz pri konkrétnom poli zrozumiteľným textom a farbou pre chyby.

Formulár objednávky má pýtať len údaje potrebné na kontakt a pochopenie problému: napríklad meno, telefón alebo e-mail, typ zariadenia a stručný opis závady. Pri odosielaní zobraz stav potvrdenia alebo chyby; nevymaž vyplnené údaje pri neúspešnom odoslaní. Polia musia mať programovo priradené štítky a byť ovládateľné klávesnicou.

## Responzívne správanie

- Navrhuj najprv pre menšie obrazovky a rozloženie postupne rozširuj pre tablet a desktop.
- Na mobile zmeň viacstĺpcové sekcie na jeden stĺpec; karty a formuláre nech majú plnú dostupnú šírku.
- Zmenši veľkosť nadpisov a vertikálne rozostupy, ale zachovaj čitateľné písmo, dostatočný kontrast a klikateľné plochy aspoň približne `44 × 44 px`.
- Dôležité CTA umiestni tak, aby sa dalo nájsť bez prechádzania dlhým textom. Nedovoľ, aby navigácia, texty alebo tlačidlá spôsobovali horizontálne posúvanie.
- Fotografie používaj v primeranom pomere strán a orež ich tak, aby zostal viditeľný podstatný detail zariadenia.

## Zásady pre jednotlivé časti stránky

### Hero

Hero sekcia má okamžite vysvetliť, že FIXORA PC ponúka servis a čistenie počítačov. Použi vlastný, konkrétny nadpis, krátky podporný text a jedno primárne CTA; sekundárny odkaz môže viesť na zoznam služieb. Vizuálnym ťažiskom môže byť kvalitná fotografia počítača alebo reálnej práce technika. Nezahlcuj prvý pohľad dlhým textom, dekoráciami ani viacerými rovnocennými tlačidlami.

### Obsahové sekcie

Informácie rozdeľ do jasných celkov, napríklad služby, priebeh opravy, cenník, referencie a často kladené otázky. Používaj krátke nadpisy a skenovateľné odseky; technické pojmy vysvetli jednoducho. Pri cenách alebo rozsahu služby jasne uveď, čo je zahrnuté a čo sa určuje až po diagnostike. Výzvu na objednanie zopakuj po prirodzených rozhodovacích bodoch.

### Footer

Pätička má na tmavom podklade prehľadne uvádzať vlastné logo, kontaktné údaje, lokalitu alebo oblasť pôsobenia, otváracie hodiny, odkazy na služby a právne informácie. Dôležitý kontakt, najmä telefón alebo e-mail, musí zostať čitateľný a ľahko dostupný aj na mobile. Použi jemný deliaci okraj a vizuálne pokojnejšiu hierarchiu než v hlavnom obsahu.