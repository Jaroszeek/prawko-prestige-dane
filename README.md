# Dane do aplikacji Prawko Prestige

Pytania i media do aplikacji Prawko Prestige (Android), trening do teoretycznego egzaminu na prawo jazdy.

| Plik | Opis |
|---|---|
| `manifest.json` (gałąź `main`) | wersja danych, adresy, suma SHA256 pytań, zasady egzaminu |
| `questions.json` (tagi `v1`, `v2`, ...) | pytania w formacie aplikacji |
| wydania `media-v1-1`, `media-v1-2`, ... | filmy MP4 i zdjęcia WebP (GitHub pozwala na 1000 plików w jednym wydaniu) |

## Źródło

Pytania, zdjęcia i filmy pochodzą z oficjalnej bazy pytań egzaminacyjnych na prawo jazdy
udostępnianej przez Ministerstwo Infrastruktury: https://www.gov.pl/web/infrastruktura/prawo-jazdy
(katalog z lipca 2026 i multimedia z października 2026).

Zmiany względem oryginału: filmy WMV przekodowane do MP4 (H.264, maks. 720p), zdjęcia JPG do WebP
(maks. 1280 px), nazwy plików bez spacji, arkusz XLSX zamieniony na JSON. Treść pytań bez zmian.

Ten projekt nie jest powiązany z Ministerstwem Infrastruktury, WORD ani żadnym innym urzędem.

Polityka prywatności aplikacji: [privacy.md](privacy.md)
