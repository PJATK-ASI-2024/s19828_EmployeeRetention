# Prognozowanie retencji pracowników w firmie

## 1. Opis projektu

Projekt polega na stworzeniu modelu do prognozowania retencji pracowników w firmie na podstawie historycznych danych o pracownikach.

## 2. Problem biznesowy

Projekt adresuje problem rotacji pracowników, który stanowi poważne wyzwanie dla wielu firm. Generuje ona koszty związane z rekrutacją i szkoleniem nowych osób, a także prowadzi do spadku produktywności. Opracowanie modelu predykcyjnego pozwoli na wczesne identyfikowanie pracowników zagrożonych odejściem i wdrażanie działań mających na celu poprawę ich satysfakcji i zaangażowania.

## 3. Źródło danych

W projekcie wykorzystano zbiór danych z platformy [Kaggle](https://www.kaggle.com/datasets/tawfikelmetwally/employee-dataset/data) dotyczący retencji pracowników. Zbiór ten zawiera kluczowe informacje o pracownikach, takie jak:
- **Education**: poziom wykształcenia
- **Joining Year**: rok, w którym pracownik rozpoczął pracę
- **City**: miasto, w którym osoba pracuje
- **Payment Tier**: kategoria pensji
- **Age**: wiek
- **Gender**: płeć
- **Ever Benched**: czy pracownik był kiedykolwiek tymczasowo bez poleconego zadania
- **Experience in Current Domain**: doświadczenie pracownika w obecnej branży w latach
- **Leave or Not**: czy pracownik odszedł

Zbiór danych z Kaggle został wybrany, ponieważ zawiera istotne zmienne potrzebne do analizy problemu.

## 4. Cele projektu

- Zbadanie wpływu różnych cech pracowników na ich decyzję o odejściu z firmy
- Stworzenie modelu predykcyjnego
- Ocena dokładności modelu i wynikających z niego wniosków

## 5. Struktura projektu

1. Analiza i czyszczenie danych
2. Wybór modelu i trenowanie
3. Ocena wyników
4. Dokształcanie modelu
5. Wdrożenie modelu
6. Prezentacja wyników

## 6. Użyte narzędzia i technologie
- **Język programowania**: Python
- **Biblioteki**:
