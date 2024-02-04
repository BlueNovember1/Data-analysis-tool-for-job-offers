# Data-analysis-tool-for-job-offers
Narzędzie pozwalające na wyszukanie ofert pracy ze strony No Fluff Jobs. Po wybraniu nazwy stanowiska lub umiejętności program pobiera dane ze strony (webscraping) i wyodrębnia z nich intersujące nas dane takie jak nazwa oferty, widełki, lokalizacje itd. Dane z obecną datą zostają zapisne do pliku csv i następinie są poprawiane autoamtycznie przez program. Ostatecznie otrzymujemy posrotowany i czytelny plik csv któy ułatwi analizę ofert. W przysłosci planuje dodać wyszukanie ofert z innych stron.

# Program pobiera następujące dane:
- Nazwa wyszukania
- Nazwa oferty
- Firma
- Informacje o ofercie (umiejętności)
- Widełki płacowe
- Rodzaj stanowiksa (senior, lead, mid, junior)

## Ostateczna anliza znajduję sie w project\data\processed_manual !

Przykładowy wynik dla haseł "Programista Python", "React Native" i "Data Enginire"  z dnia 4.02.24 został zapisany następująco:
- project\data\interim -> nie przefitrowane przez program dane
- project\data\processed -> posortowane autoamtycznie przez porgram dane
- project\data\processed_manual -> posortowane automatycznie i manulanie dane. W tym pliku zostały usunięty puste wiersze i duplikaty. Dodatwoko dodałem nowy arkuz w któym znajdują się tabele przestawne i wykresy.

## Stack technologiczny:
- python
- selenium & chromedrive
- html
- csv & excel


