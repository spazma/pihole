# Spaz-Block – Custom Pi-hole Adlist

Niestandardowa lista domen do Pi-hole, przygotowana pod moje urządzenia:

- TCL Smart TV (Android TV / Google TV)
- Samsung S20 (Android)
- Steam Deck (SteamOS)
- Raspberry Pi 5 (Linux)
- Ogólne blokowanie reklam i trackerów

Lista działa jako **Adlist**, czyli subskrybowana lista domen pobierana automatycznie przez Pi-hole.

## Jak dodać listę do Pi-hole

1. Skopiuj link RAW do pliku:
   https://raw.githubusercontent.com/spazma/pihole/refs/heads/main/spaz-block.txt

2. W Pi-hole przejdź do:
   **Group Management → Adlists**

3. Kliknij **Add**, wklej link RAW i zapisz.

4. Następnie wykonaj:
   **Tools → Update Gravity**

Pi-hole pobierze listę i zacznie blokować domeny automatycznie.

## Informacje

- Lista jest w wersji stabilnej (safe).
- Nie blokuje domen potrzebnych do aktualizacji systemów.
- Można ją rozszerzać o kolejne urządzenia i usługi.
- Repozytorium może zawierać wiele plików .txt, każdy z własnym RAW linkiem.

## Licencja

jaka licencja? na zabijanie reklam? tak
