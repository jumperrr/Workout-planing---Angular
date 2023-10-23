# Workout-planing---Angular

Celem tej pracy jest zaprojektowanie i realizacja aplikacji umożliwiającej planowanie treningów sportowych. 
Stworzenie takiej aplikacji ma na celu ułatwienie planowania treningów sportowych, poprzez przyjazny i możliwie prosty interfejs aplikacji internetowej. 
Zakres pracy obejmuje następujące zagadnienia:

- Projekt i implementacja bazy danych,
- Stworzenie serwera REST,
- Implementacja aplikacji klienckiej

Aplikacja umożliwia tworzenie planu treningowego, poprzez wprowadzenie przez użytkownika wybranych ćwiczeń i parametrów ćwiczenia do danego planu. 
Użytkownik może korzystać z aplikacji, używając przeglądarki internetowej.

Wymagania funkcjonalne:
- Rejestracja użytkownika,
- Logowanie użytkownika,
- Wyświetlanie dostępnych ćwiczeń,
- Grupowanie ćwiczeń w kategorie,
- Wyświetlanie planów treningowych użytkownika,
- Dodawanie nowego planu treningu,
- Dodawanie ćwiczenia do planu treningu,
- Wprowadzanie ilości powtórzeń i obciążenia dla danego ćwiczenia,
- Zatwierdzenie wykonania ćwiczenia,
- Edycja ilości powtórzeń i obciążenia,
- Przeglądanie statystyk danego ćwiczenia,
- Usuwanie ćwiczenia z planu treningu,
- Usuwanie planu treningu,
- Wylogowanie użytkownika.

Widoki:
- Oknko logowania
- Podgląd dostępnych ćwiczeń (dostępne dla wszystkich)
- Przegląd planów użytkownika (dostępne dla zalogowanego użyttkownika)
- Widok danego planu (dostępne dla zalogowanego użyttkownika)
- Przegląd statystyk danego ćwiczenia (dostępne dla zalogowanego użytkownika)
- Widok dodania/edycji ćwiczenia (dostępne dla zalogowanego użyttkownika)
 
Baza danych: MySQL XAMPP
Backend: Node.js
Frontend: Angular

Baza danych - Tabele:
- user
- workoutplan
- training
- category
- exercise
- unit
