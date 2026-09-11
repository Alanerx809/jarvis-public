# PROJEKT JARVIS V0.1.0-alfa

Witaj w projekcie Jarvis

## Konfiguracja

Skonfiguruj swojego asystenta!
- Włacz asystenta Jarvis
- Kliknij Konfiguracja lub powiedz "config"
- Wpisz dane 

Muzyka
- Mozesz wzrucac swoje mp3 do folderu ``music`` z rozszerzeniem mp3. Wystarczy powiedziec odtwórz/puść <nazwa>
Przykład: Wrzucasz plik ``muzyka.mp3`` do  folderu ``music``. Mowisz jarvisowi ``puść muzyka`` i wlacza sie twoj plik

Szablony
- W folderze ``autostarts`` mozes tworzyc swoje szablony czyli pliki .txt. Pozwalaja one na wykonanie kilka insurkcji naraz 

Komendy jarvis:

``config`` - włącza konfiguracje
``włącz/odpal/run`` - wlaczaja dany program z pliku paths.json
``puść/odtwórz`` - wlaczaja muzyke z folderu music
``szablon/template`` - wlaczaja szbalony z autostarts

Odpalanie programow
- By odpalac programy mussicz rpzejsc do pliku ``src/paths.json`` tam dodajesz w tym formacie swoje programy:
``{
    "program": "TwojaSciezka"
}``

Pozniej po tej nazwie mozesz odpalac programy w tym przykladzie mowiac ``otwórz program``