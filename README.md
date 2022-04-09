# zoteroproFZS

citation style for FZS TUL for Zotero

## Co lze citovat:

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