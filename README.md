# TicTacToeApp_Android
Making the first app with multiplayer features for android!

Check out our specification:

Kółko i Krzyżyk (Multiplayer)
Opis ogólny
Gra Kółko i Krzyżyk rozgrywana jest na planszy składającej się z komórek ułożonych 3x3. Dwóch graczy: gracz_X, gracz_O. Wszystkie komórki na początku gry są puste. Gracze naprzemiennie umieszczają „X” lub „O” w pustej komórce. Celem jest posiadanie trzech „X” lub trzech „O” w rzędzie, w kolumnie lub po przekątnej. Pierwszy gracz, któremu się to uda, wygrywa. Gra kończy się remisem, jeśli wszystkie 9 komórek zostanie wypełnionych bez wygranej żadnego gracza.

Wymagania funkcjonalne:

- uruchomienie gry
- wpisanie nazwy użytkownika/email/hasla założenie konta użytkownika/logowanie

REGISTER:
{
email,
password
}

- interfejs wyszukiwania graczy online, zaproszenie do gry, alert (accept/refuse)
- pole gry (siatka 3x3)
- koniec rozgrywki (podsumowanie)
- statystyki gracza
- ranking graczy

Wymagania niefunkcjonalne:

- interfejs nawiązywania połączenia pomiędzy wybranymi graczami
- polaczenie z bazą danych przechowującą wyniki/statystyki zarejestrowanych użytkowników/loginy/hasla
- mechanizm wykrywania istniejacego konta w bazie danych
- mechanizm rejestracji w bazie
- mechanizm walidacji logowania i bledow
- walidacja błędnych ruchów użytkowników
- mechanizm wykrywania końca gry

DATABASE:

TABLES: 

User {
id PK,
username,
password (secret),
countWins,
countLoses,
ip
}

//App logic - photo:

https://ibb.co/b8kzMx

