# laboro-email-assets

Obrázky pro **e-mailový podpis** Laboro ateliér s.r.o. — hostované na veřejné URL,
aby je e-mailoví klienti (Gmail, Outlook, Apple Mail) spolehlivě zobrazili.

## ⚠️ NEMAZAT — soubory jsou ŽIVĚ používané

Na tyto soubory odkazují e-mailové podpisy **celého týmu Laboro**. Podpis si obrázek
stahuje z níže uvedených URL při každém zobrazení e-mailu. **Když se cokoliv z toho
změní, obrázky vypadnou VŠEM naráz:**

- ❌ **nemazat repo** ani jednotlivé soubory
- ❌ **nepřejmenovávat** soubory (URL se rozbije)
- ❌ **nepřepínat repo na soukromé** (klienti stahují bez přihlášení)
- ❌ **nerušit ani nepřejmenovávat GitHub účet** `kadrmas126-cpu`

Aktualizace obrázku (stejný vzhled, lepší kvalita): přepiš soubor pod **stejným názvem**.

## Soubory a `raw` URL

Raw base: `https://raw.githubusercontent.com/kadrmas126-cpu/laboro-email-assets/main/`

| Soubor | Použití |
|---|---|
| `logo-laboroatelier-email.png` | logo (na světlé pozadí) |
| `logo-laboroatelier-email-white.png` | logo (na tmavé pozadí) |
| `ikona-adresa.png` | ikonka adresy |
| `ikona-telefon.png` | ikonka telefonu |
| `ikona-email.png` | ikonka e-mailu |
| `ikona-web.png` | ikonka webu |
| `pruh-doprava-v3.png` | spodní dopravní pás (průhledné pozadí) |

## Plán do budoucna — přesun na firemní web

Cílově se obrázky přesunou na **firemní doménu laboroatelier.cz** (nezávislost na
osobním GitHub účtu, firemní zdroj přežije personální změny). Postup migrace:
1. Nahrát těchto 7 souborů na web (např. `laboroatelier.cz/podpis/`).
2. V generátoru `email-podpis\_generator\gen_team.py` změnit konstantu `RAW` na novou base URL.
3. Přegenerovat podpisy a rozeslat kolegům aktualizované soubory.

Generátor je stavěný tak, že hosting je **jediná proměnná** — migrace = změna jednoho řádku.
