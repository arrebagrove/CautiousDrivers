### Przygotowanie i normalizacja
- przycięcie do ramki kierownica - zagłówek
- zmniejszenie
- obrócenie do jednej linii np. okna
- wyszarzenie?
- skontrastowanie?
- uwydatnienie konturów?


### Sposoby: 
#### podział obrazka na obszary
badanie położenia różnych części ciała w obszarach i odchyleń

#### analiza sylwetki

- rozpoznanie szkieletu + przedmiotów, 
- wykrywanie ramion przez sprogowanie i wykrycie linii ramion
- progowanie: 
 - rozpoznanie postury przy analizę naświetlenia (światło pada zawsze od przodu)
- wykrywanie krawędzi (transformata hough'a (?))
- funkcje ciała (funkcje opisujące konkretne części ciała)

#### analiza całościowa:

- różnicowanie obrazków [przykład z twarzami: wektor zwektoryzowanych obrazków * ]
- one against all
- safe driver i % porównania odchyłów od pozostałych klas

#### inne
- wykrywanie pasu (np jako punkt orientacyjny)
- liczba rąk na kierownicy
- testy binarne
- rozpoznawanie telefonu jako dwie nienaturalnie równoległe linie przy głowie
- sprawdzanie linii brwi i oczu - im dłuższa tym bardziej postać zwrócona w prawo
- sprawdzanie zwrócenia twarzy po ocenie jej naświetlenia
- maska na kolor skóry
