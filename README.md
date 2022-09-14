# Form validation task

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/vue-9yhbdv)
**ZADANIE REKRUTACYJNE JUNIOR FRONT-END DEVELOPER**
**Wymagania techniczne:**

- Vue 2 +
- komponenty Option API lub Composition API (preferowany script setup)
- aplikacji SPA z wykorzystaniem Vue Cli lub Vite (preferowany)
- użycie TypeScript’u mile widziane i dodatkowo punktowane
- forma dostarczenia zadania dowolna (może być paczka zip lub repozytorium)
  Zadanie polega na stworzeniu formularza zawierającego reużywalne komponenty:
  a) input z walidacją (walidacja wykonywana podczas zejścia z pola – pole traci focus)

b) select

**Wytyczne dotyczące komponentów:**

- komponenty powinny być reużywalne
- komponenty powinny być reużywalne
- komponent powinien być napisany jako SFC
- powyższe grafiki są jedynie pomocnicze, nie wymagamy odzwierciedlenia wymiarów
  oraz kolorów
- komponenty wizualnie powinny być przygotowane z dbałością o estetykę
- wymagane stany komponentów:
  a) input: blur, focus, disabled, error (jedynie pierwszy wiersz – bez ikon)

**Formularz:**

- powinien składać się z dwóch pól:
  a) imię: komponent input
  b) marka pojazdu: komponent select (z 10 wybranymi markami pojazdów)
- formularz zawiera przycisk do walidacji formularza (może być to zwykły,
  nie ostylowany tag <button>)

**Walidacja formularza:**

- button walidacji formularza jest aktywny jeżeli input z imieniem oraz sele
  ct z marką pojazdu został wypełniony, w przeciwnym razie powinien mieć stan
  disabled a próba walidacji powinna zostać odrzucona
- poprawna walidacja formularza oznacza wpisanie imienia (input)
  (długośc znaków 3-16) oraz wybranie marki pojazdu (select)
- poprawna walidacja formularza wyświetli alert dowolnej treści
- niepoprawna walidacja formularza podświetli błędnie wpisany input z imieniem

Przykładowe pomocnicze stany formularza:
Stan formularza: inicjalny

Stan formularza: wypełniony select

Stan formularza: wypełniony select oraz błędnie wypełniony input

Stan formularza: wypełniony select oraz
