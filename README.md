# UDP-Guess-Game
## Gra o architekturze Klient-Serwer polegająca na zgadywaniu liczb. Wykorzystuje własny protokół binarny do komunikacji. Napisana została w języku C++ z wykorzystaniem bibliotek SFML.

Gra pozwalająca dwóm użytkownikom przy pomocy dwóch aplikacji klienckich podłączyć się do aplikacji serwera w celu zagrania w grę. Celem gracza jest zgadnięcie liczby zanim zrobi to jego przeciwnik.

Gra wykorzystuje protokół UDP w warstwie transportowej. W warstwie aplikacji wykorzystywany jest własny protokół binarny służący do przekazywania komend, poleceń, statusów, zgadywanych liczb itp.

Szczegółową treść zadania oraz opis stworzonego protokołu i formatu jego komunikatów zawarto w pliku "opis_zadania_i_protokolu.pdf".

--------------------------------------------------------
## Client-Server architecture number guessing game that uses own binary communication protocol. Written in C++ using SFML libraries.

Game enables two users with two client applications to connect to server apllication in order to play a game. Player's objective is to guess the number before his opponent does.

Game uses UDP protocol in transport layer. Game uses it's own binary communication protocol in application layer to pass information about commands, game status, numbers etc.

Detailed task descritpion as well as description of created protocol and it's message format can be read in "opis_zadania_i_protokolu.pdf" file (file is written in Polish).
