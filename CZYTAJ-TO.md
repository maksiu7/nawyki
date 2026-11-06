# Nawyki na GitHub Pages

Wgraj wszystkie pliki z tego folderu do repozytorium (w głównym katalogu albo w folderze, z którego działa Twoja strona):
`index.html`, `manifest.webmanifest`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png`.

## Jak zaktualizować aplikację na telefonie
1. Podmień pliki w repozytorium (commit) i poczekaj ok. minuty, aż GitHub Pages opublikuje zmianę.
2. Na telefonie otwórz aplikację przy włączonym internecie. Aplikacja sama sprawdza wersję przy starcie i po powrocie do niej
   i pokazuje u góry przycisk „Odśwież”. Możesz też wejść w Ustawienia → Aplikacja → „Sprawdź aktualizację”.
3. Aby każda kolejna aktualizacja była wykrywana, zmieniaj liczbę w tagu `<meta name="app-version" content="...">`
   w `index.html` (np. na `2026-11-10.1`).

## Kopia zapasowa (zrób ją PRZED większymi zmianami)
Ustawienia → Kopia zapasowa:
- „Zapisz do pliku” otwiera arkusz udostępniania. Zapisz plik w Plikach (iCloud Drive) albo wyślij go do siebie.
- „Kopiuj jako tekst” kopiuje całą kopię jako tekst, np. do Notatek.
- „Importuj z pliku” / „Wklej tekst kopii” przywraca dane (przed zamianą zobaczysz podsumowanie).

Ważne: dane są zapisane w pamięci tej konkretnej aplikacji na tym telefonie, osobno dla każdego adresu strony.
Aplikacja z ekranu początkowego i ta sama strona w Safari mają osobne dane. Zmiana adresu (np. nazwy repozytorium)
oznacza puste dane, więc najpierw zrób kopię i wczytaj ją pod nowym adresem.
