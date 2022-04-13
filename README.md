# README

### Jaké druhy dokumentů lze citovat:

Styl je upraven pouze pro typy dokumentů, které nejčastěji citují studenti FTS TUL a které jsou definované v *Metodice zpracování bibliografických citací, 2. vyd.* viz https://publi.cz/download/publication/1514?online=1. Jedná se o:

- knihy

- články

- kapitoly

- kvalifikační práce

- webové stránky <mark>(dodělat)</mark>

- legislativu (vyhlášky, zákony, věstníky, legislativu Evropské unie)

- normy

- patenty a užitné vzory

- přednášky (ústní sdělení)

- e-maily

- obrázky (<mark>dodělat</mark>)

- PDF na webu (příspěvky na webové stránce ve formátu PDF) (<mark>dodělat</mark>)

- postery (<mark>dodělat</mark>)

### Jaké druhy dokumentů (typy položek) citovat nelze:

Pro následující dokumenty není citační styl upraven: audio nahrávka, článek v encyklopedii, článek v magazínu, článek v novinách, dokument, dopis, film, konferenční příspěvek, mapa, nařízení, podcast, pořad v rádiu, pořad v TV, preprint, případ, příspěvek v blogu, příspěvek ve fóru, rozhovor, rukopis, slyšení, software, umělecké dílo, videonahrávka, záznam ve slovníku, zpráva, zpráva IM.

V případě, že potřebujete citovat některý z těchto druhů, pak dodržujte princip toho, že citace by měly dodržovat stejná pravidla a měly by vypadat podobně. Lze použít některý z připravených dokumentů (viz Jaké dokumenty lze citovat).

### Co citační styl neumí a je tedy nutné upravovat ručně:

Některá pravidla v https://publi.cz/books/1514/index.html?secured=false#05 nelze naprogramovat. Proto úprava musí probíhat na úrovni metadat uložených v Zotero nebo až na závěr ve vygenerovaném seznamu literatury.

##### Autoři:

- dodržujte v metadatech mezeru za tečkou mezi více iniciálami, např. Volandes, A. E.

- u tří osob zkracujte v metadatech křesní jména na iniciály

- pokud jsou autoři či editoři uvedeni ve formě "Jan Novák a kol.", pak v metadatech doplňte první osobu a k ní další tři FIKTIVNÍ osoby (např. autor2, autor3, autor4).

- u dvou a více editorů opravujte ed. na eds. - v odkaze v textu i v bibliografické citaci!

##### Názvy:

- u podnázvu mažte v metadatech mezeru před dvojtečkou

- u časopisů mažte v metadatech podnázvy časopisů

- pokud název nebo podnázev končí vykřičníkem nebo otazníkem, doplňujte za ně v metadatech tečku

##### Vydání; místo, nakladatel, rok; standardní čísla a identifikátory:

Vždy metadata měňte podle požadavků v https://publi.cz/books/1514/index.html?secured=false#05.

##### Další údaje, které se budou ukládat při stahování metadat:

Souběžný název, edici (sérii), abstrakt, krátký název, práva, signatura a další údaje, které se budou stahovat do Zotera, můžete, ale nemusíte mazat. Tyto údaje by neměly mít na výslednou citaci vliv. Samozřejmě pokud se s údaji nepracuje, je výhodnější je smazat a udržovat tedy metadata vyčištěná.

### Specifika jednotlivých druhů dokumentů:

##### Knihy:

Používejte typ položky "kniha". Dodržujte všechna pravidla viz sekce Co citační styl neumí a je tedy nutné upravovat ručně.

##### Články:

Používejte typ položky "článek v časopise". Dodržujte všechna pravidla viz sekce Co citační styl neumí a je tedy nutné upravovat ručně.

Pokud chybí URL v citacích, je nutné ho nastavit v desktop Zoteru v preferencích (zahrnout URL článků v preferencích) viz

![](C:\Users\Marta\AppData\Roaming\marktext\images\2022-04-10-14-38-08-image.png)

##### Kapitoly:

Používejte typ položky "kapitola knihy". Dodržujte všechna pravidla viz sekce Co citační styl neumí a je tedy nutné upravovat ručně.

Pokud chybí editor knihy, je třeba ho psát do Zotera do pole editor.
DOI kapitoly pište do pole EXTRA ve tvaru DOI: 10.19.12345667.
Ze Scopusu se kapitoly stahují jako články, je možné okopírovat DOI a pak přes kouzelnou hůlku znovu vložit pomocí DOI.

##### Kvalifikační práce:

Používejte typ položky "vysokoškolská kvalifikační práce". Dodržujte všechna pravidla viz sekce Co citační styl neumí a je tedy nutné upravovat ručně.

Stahování z katalogu Univerzitní knihovny TUL nefunguje. Funguje stahování z DSpace (https://dspace.tul.cz/), ale automatický druh je článek v časopise, je nutné ho měnit; je třeba doplňovat ručně fakultu, typ práce, někdy i místo.

##### Webové stránky: <mark>(dodělat):</mark>

**<mark>Pokračovat v doplňování odsud!!!</mark>**

##### Legislativa (vyhlášky, zákony, věstníky, legislativa Evropské unie):



Používejte typ položky "návrh zákona". Dodržujte všechna pravidla viz sekce Co citační styl neumí a je tedy nutné upravovat ručně.

Citace je třeba vytvářet ručně, stahování ze systémů Zákony pro lidi, aplikace MVČR a dalších nefunguje.

Autor se píše v metadatech do pole SPONZOR. Název sbírky se píše do pole ZÁKONÍK. Částka do pole ROČNÍK ZÁKONÍKU. Rok do pole DATUM. ISSN je třeba psát do pole EXTRA, a to ve tvaru ISSN: 1234-5678.

##### Normy:

 (typ položky "kniha"):

##### Patenty a užitné vzory:

 (typ položky "patent"):

##### Přednášky (ústní sdělení):

 (typ položky "prezentace"):

##### E-maily:

 (typ položky "e-mail"):

##### Obrázky: (<mark>dodělat</mark>):

##### PDF na webu (příspěvky na webové stránce ve formátu PDF): (<mark>dodělat</mark>):

##### Postery: (<mark>dodělat</mark>):

# Pro Adyho:

## Chyby k vyřešení:

U kapitoly, pokud má kniha autora a ne editora, tak za autorem chybí tečka. Viz například citace na pokusnou kapitolu.

#### JSON na takový případ:

[
    {
        "id": "http://zotero.org/users/628524/items/YWD5VMUU",
        "type": "chapter",
        "abstract": "Abstrakt",
        "archive": "Archiv",
        "archive_location": "Místo v archivu",
        "call-number": "Signatura",
        "collection-number": "Číslo série",
        "collection-title": "Série",
        "container-title": "Jméno knihy",
        "edition": "Vydání",
        "event-place": "Místo",
        "ISBN": "ISBN",
        "note": "Extra",
        "number-of-volumes": "Počet ročníků",
        "page": "Rozsah",
        "publisher": "Vydavatel",
        "publisher-place": "Místo",
        "source": "medvik.cz",
        "title": "ZZZ pokusná kapitola",
        "title-short": "Krátký název",
        "URL": "URL",
        "volume": "Ročník",
        "author": [
            {
                "family": "ZZZ",
                "given": "Jméno"
            }
        ],
        "container-author": [
            {
                "family": "Příjmení autora knihy",
                "given": "Jméno",
                "dropping-particle": "autora knihy"
            }
        ],
        "editor": [
            {
                "family": "Editor",
                "given": ""
            }
        ],
        "collection-editor": [
            {
                "family": "Editor série",
                "given": "Jméno"
            }
        ],
        "translator": [
            {
                "family": "Překladatel",
                "given": "Jméno"
            }
        ],
        "accessed": {
            "date-parts": [
                [
                    "2022",
                    3,
                    19
                ]
            ]
        },
        "issued": {
            "literal": "Datum"
        }
    }
]

### Je hotovo:

- články ("type": "article-journal")

- e-maily ("type": "personal_communication")

- kapitoly (type": "chapter")

- knihy ("type": "book")

- legislativa ("type": "bill")

- normy ("type": "book")

- patenty ("type": "patent")

- přednášky ("type": "speech")

- vškp ("type": "thesis")

### Zbývá dodělat:

- obrázky

- PDF na webu

- postery

- webovky

## Na čem teď pracujeme:

~postery

### Co je třeba změnit:

~doplnit za název posteru typ, tedy [poster], brát ho z pole EXTRA

### Výsledná citace má být takto:

HENDRYCH LORENZOVÁ, E., K. RATISLAVOVÁ a L. KAŠOVÁ. 2016. Specifické diagnostické nástroje vhodné pro porodní asistentky pečující o ženy
po porodu v komunitním prostředí [poster]. In: *Cesta poznávání a vzdělávání
v ošetřovatelství VII.: konference ošetřovatelství a porodní asistence v Plzni, 4. května 2016*. DOI 10.13140/RG.2.1.4995.0325. Dostupné také z: https://www.researchgate.net/
publication/304025033_Specificke_diagnosticke_nastroje_vhodne_pro_porodni_asisten
tky_pecujici_o_zeny_po_porodu_v_komunitnim_prostredi

### JSON na takový případ:

[
    {
        "id": "http://zotero.org/users/628524/items/M4CMMG9S",
        "type": "chapter",
        "container-title": "Cesta poznávání a vzdělávání v ošetřovatelství VII.: konference ošetřovatelství a porodní asistence v Plzni, 4. května 2016",
        "note": "DOI: 10.13140/RG.2.1.4995.0325\ntyp: poster",
        "title": "Specifické diagnostické nástroje vhodné pro porodní asistentky pečující o ženy po porodu v komunitním prostředí",
        "URL": "https://www.researchgate.net/ publication/304025033_Specificke_diagnosticke_nastroje_vhodne_pro_porodni_asisten tky_pecujici_o_zeny_po_porodu_v_komunitnim_prostredi",
        "author": [
            {
                "family": "Hendrych Lorenzová",
                "given": "E."
            },
            {
                "family": "Ratislavová",
                "given": "K."
            },
            {
                "family": "Kašová",
                "given": "L."
            }
        ],
        "issued": {
            "date-parts": [
                [
                    "2016"
                ]
            ]
        }
    }
]



## Vzorová metadata:

##### Kniha:

<img src="file:///C:/Users/Marta/AppData/Roaming/marktext/images/2022-04-13-17-25-00-image.png" title="" alt="" width="365">

##### Článek:

<img title="" src="file:///C:/Users/Marta/AppData/Roaming/marktext/images/2022-04-13-17-30-50-image.png" alt="" width="410">

##### Kapitola:

<img src="file:///C:/Users/Marta/AppData/Roaming/marktext/images/2022-04-13-17-38-28-image.png" title="" alt="" width="476">

##### Kvalifikační práce:

<img src="file:///C:/Users/Marta/AppData/Roaming/marktext/images/2022-04-13-17-40-46-image.png" title="" alt="" width="505">

##### Legislativa: