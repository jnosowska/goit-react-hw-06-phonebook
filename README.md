Kryteria zaliczenia
Użyj tego szablonu projektu React jako punktu wyjścia dla swojej aplikacji.

Stworzone repozytorium goit-react-hw-06-phonebook
Przy oddawaniu zadania domowego znajdują się w nim odnośniki do: oryginalnych plików i roboczej strony projektu na GitHub Pages.
W stanie Redux przechowywany jest minimalny wymagany zestaw danych.
Po włączeniu kodu zadania, na konsoli nie ma błędów i ostrzeżeń.
Dla każdego komponentu stworzony został folder z plikiem komponentu React i plikiem stylów.
Dla komponentu opisane są propTypes.
Wykorzystywana jest biblioteka Redux Toolkit.
Książka telefoniczna
Przeprowadź refaktor kodu aplikacji "Książka telefoniczna", dodając zarządzanie stanem przy pomocy biblioteki Redux Toolkit.

Niech stan Redux wygląda następująco.

{
  contacts: [],
  filter: ""
}

Stwórz magazyn z configureStore().
Stwórz działanie zapisywania i usuwania kontaktu oraz odświeżania filtru. Wykorzystaj funkcję createAction().
Stwórz reduktory kontaktów i filtru. Wykorzystaj funkcję createReducer() lub createSlice().
Powiąż komponent React i logikę Redux przy pomocy hooków biblioteki react-redux.
