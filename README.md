# SPECIALTY

Digitální prototyp deskové hry o pražírně výběrové kávy. Hraje se v prohlížeči u jednoho počítače: hráči se střídají v tazích (hot seat), 2–5 hráčů, zhruba 30–40 minut.

**Hrát:** https://jonas-lukyn.github.io/specialty/ – zadej jména hráčů, nic se neinstaluje. Rozehraná hra se ukládá v prohlížeči, po zavření okna jde pokračovat.

## Pravidla v kostce

- Všichni hrají na **společné chuťové mapě 7×7**: vodorovně Ovocnost, svisle Tělo. Každý na ní má dvě šarže kávy (žetony ve své barvě s čísly 1 a 2).
- **Pražírny (volitelné):** na začátku si každý hráč postupně lízne 2 pražírny, jednu si nechá a druhou vrátí do balíčku. Každá pražírna mění jedno pravidlo – viz tabulka níže.
- Tah = **2 akce**. Každá akce znamená poslat baristu na jedno ze tří míst:
  - **Farma** – na stole leží vždy 4 karty. Vezmi jednu, lízni naslepo, nebo za 1 akci spláchni celou řadu. Zpracování hned posune neupraženou šarži. Recept pražení si necháš, nebo ho dáš na Pražírnu (max. 2 veřejné) – když ho použije soupeř, dostaneš 1 bod. Vybavení (max. 1 od každého druhu) dává +1 bod při prodeji.
  - **Pražírna** – každý má jedno vlastní místo, praží tedy jednou za kolo. Základní pražení šarži nehýbe, recept ji posune. Upražená káva musí do dalšího tahu odpočinout.
  - **Kavárna** – 4 body přesně na zákazníka, 2 body o pole vedle, 1 bod prodej mimo zákazníky (zákazník zůstává). +1 bod za vybavení, které sedí s přípravou zákazníka. **VIP zákazník** dává 7 bodů, bere jen přesnou trefu a jen s jeho vybavením. Na stole je vždy jeden.
- Kdo první dosáhne cílového počtu bodů (**2 hráči 16, 3 hráči 20, 4 hráči 16, 5 hráčů 14**), spustí konec: kolo se dohraje a vyhrává nejvíc bodů, při shodě remíza. Ve dvou hráčích začíná pořád stejný hráč, ve 3–5 se začínající hráč každé kolo posouvá.

## Pražírny

| Pražírna | Schopnost |
|---|---|
| Řemeslná pražírna | Základní pražení smí posunout Tělo o 1 nahoru, nebo dolů. Veřejné recepty ostatních nepoužívá. |
| Fermentační laboratoř | Kartu zpracování smí použít obráceně. Smí ji použít i na obě své neupražené šarže najednou, obě stejným směrem – to ale stojí 2 akce (celý tah). |
| Přímý obchod | Po prodeji si lízne 3 původy a 1 si nechá jako novou šarži. |
| Velkopražírna | Jednou akcí upraží obě šarže, obě stejným způsobem. |
| Pop-up stánek | Kávu smí prodat hned po upražení, takový prodej ale dá o 1 bod méně. |
| Cupping laboratoř | Přesná trefa u běžného zákazníka 5 bodů, těsně vedle jen 1 bod. |
| Soutěžní barista | VIP obslouží i bez vybavení za 5 bodů, s vybavením dostane 8. |
| Konkurenční řetězec | Má 5 žetonů. Jednou za kolo smí ve svém tahu bez akce posunout neupraženou šarži soupeře o 1 pole. |

Pražírny jsou vyladěné botem (tisíce simulovaných her): ve 3 a 4 hráčích má každá pražírna výherní šanci do ±3 procentních bodů od férového podílu, ve 2 hráčích do ±6.

Kompletní pravidla a vysvětlení kávových pojmů jsou ve hře pod tlačítkem **Pravidla**.

## Technicky

Ovládá se přímo v polích Farma, Pražírna a Kavárna. Celá hra je jeden soubor `index.html` (HTML, CSS, JavaScript a písmo Archivo pod SIL Open Font License), bez instalace a bez závislostí. Stačí ho otevřít v prohlížeči.
