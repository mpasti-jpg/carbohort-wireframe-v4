# Carbohort — prototyp serwisu (wireframe, V4)

Klikalny prototyp (makieta lo-fi) nowego serwisu **Carbohort** w jednym, spójnym
**systemie wireframe** — skala szarości, bez koloru i brandingu, struktura + treść + flow.
To etap makiety, nie projekt graficzny: warstwa wizualna (zdjęcia/wykresy) to placeholdery,
a dane merytoryczne (dawki, ceny, liczby) są do potwierdzenia z zespołem Carbohort.

## Podgląd na żywo
**Strona główna:** [home.html](home.html) — start prototypu (otwiera się też przez `index.html`).

## Co jest w środku (31 stron)
- **Produkty:** filar `produkty.html` + rodziny `carbomat` / `carbohumic` / `carbomat-humic`
- **Rodzaje upraw:** `sadownicze`, `jagodowe`, `warzywnicze`, `zboza`, `zielen`, `szkolki`
  (profesjonalne) oraz `trawnik`, `ogrod`, `krzewy` (ogród i działka) + hub `uprawy.html`
- **Sprzedaż:** `sklep`, `pdp`, `koszyk`, `checkout`, `potwierdzenie`, `konfigurator`
- **B2B:** `rejestracja`, `platforma-b2b`, `admin`, `potwierdzenie-b2b`
- **Treść/firma:** `centrum-wiedzy`, `o-firmie`, `kontakt`, `zalecenia`, `partner`, `prochnica-plus`

## System
Zbudowane na uniwersalnym kicie **Wireframe Design System** (tokeny `--w-*`, klasy `wf-*`,
ikony Tabler) + cienka warstwa projektu `cw-*` (`cw.css` / `cw.js`: mega-menu, dok „dr Jurek",
koszyk, konfigurator, panel B2B). Strony są statyczne (HTML/CSS/JS) — bez backendu.

## Lokalnie
```bash
python3 -m http.server 8080
# otwórz http://localhost:8080/
```
