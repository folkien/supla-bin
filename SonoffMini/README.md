# Instrukcja wgrywania

UWAGA na zasilanie 230V

1. zainstalować na telefonie eWeLink i założyć tam konto oraz pobrać na komputer Sonoff_Devices_DIY_Tools-master ze strony producenta. https://github.com/itead/Sonoff_Devices_DIY_Tools
2. stworzyć na telefonie punkt dostępowy WiFI z danymi SSID sonoffDiy i hasło 20170618sn
3. przygotować zasilanie 230V dla modułu (ja to zrobiłem ze starego kabelka od lampki oczywiście zaznaczyłem na wtyczce gdzie jest faza - L oraz sprawdziłem w listwie gdzie jest faza tak aby podłączyć moduł zgodnie z opisem)
4. połączyć się telefonem do rutera, w którym jest internet.
5. uruchomić na telefonie eWeLink i kliknąć dodawanie modułu plusik na dole ekranu potem Quick Paring podać dane do rutera z pkt. 4 i kliknąć dalej. Zacznie się wyszukiwanie modułu i wtedy podaję zasilanie na moduł SonoffMini moduł zostanie wykryty nadaję mu nową nazwę np SonoffMini.
6. po dodaniu na liście urządzeń mam już SonoffMini trzeba kliknąć w dodane urządzenie i w górnym prawym rogu będzie kółko z trzema kropkami klikamy na ustawienia dokonujemy aktualizacji moja wersja była 3.0.0 i zaktualizowałem do 3.3.0
7. Odłączam moduł od zasilania zakładam zworkę uruchamiam w telefonie punkt dostępowy z danymi jak w pkt. 2 podłączam ponownie moduł do zasilania łączy się on z WiFi w telefonie teraz łączę się komputerem z WiFi telefonu dane jak w pkt. 2.
8 Uruchamiam na komputerze tool_01DIY85(3.3.0).exe znajdujący się w Sonoff_Devices_DIY_Tools-master\tool
9. w uruchomionym oknie powinien pojawić się moduł klikamy po prawej stronie na Firmware flash podajemy ścieżkę do pliku bin (Import firmware) potem klikamy na Flash device list powinien tam znajdować się nasz moduł potem klikamy na OK i następuje wgrywanie pliku po dojściu do 100% wyskoczy okienko i klikamy OK w celu zrestartowania modułu.
10. zamykamy okno DIY Flash Firmware Tool i kolejno DIY mode tool.
11. w tym momencie moduł rozgłasza już sieć MODUL SUPLA klikamy aby się połączyć z modułem. Po połączeniu w przeglądarce wpisujemy adres 192.168.4.1 i dokonujemy ustawień Ustawienia WIFI, Ustawienia administratora, Ustawienia SUPLA i Ustawienia modułu zapisujemy wszystko i restartujemy odłączamy zasilanie wyciągamy zworkę i ponownie podłączamy zasilanie.
12. Logujemy się do Cloud i dodajemy nasz moduł.

UWAGA na zasilanie 230V


W spakowanym folderze znajduje się plik bin jak i pliki do Arduino IDE.

Primary_GUI_Sonoff_Mini.rar
    (267.09 KiB) Downloaded 63 times

(https://forum.supla.org/viewtopic.php?f=8&t=5165&start=90)
