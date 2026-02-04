```mermaid
graph TD
    A[Start aplikacji] --> B{Zalogowany?}
    B -- Nie --> C[Ekran logowania]
    B -- Tak --> D[Panel główny]
    D --> E[Dodaj zadanie]
    D --> F[Sprawdź kalendarz]
    E --> G[Zadanie zapisane!]
    F --> G