# Kolokwium WdPBSP 8.01.2025

### Zadanie 1:
Napisz program, który przyjmuje na wejściu listę zawierającą elementy różnych typów: `str`, `float`. Dla każdego typu wykonaj określoną operację:  

1. **Dla łańcuchów znaków (`str`)**:
   - Zamień wszystkie litery `l`, `s`, `r` na wielkie litery (`A`, `B`, `R`).
   - Usuń wszystkie wystąpienia litery `q` (niezależnie od wielkości liter).  

2. **Dla liczb zmiennoprzecinkowych (`float`)**:
   - Zaokrąglij liczbę do dwóch miejsc po przecinku.
   - Dodaj do listy jeśli całkowita częśc tej livzby jest pierwsza  

Program powinien zwrócić dwie listy:
- Listę zmodyfikowanych łańcuchów znaków.  
- Listę zaokrąglonych liczb zmiennoprzecinkowych.

---

### Przykład wejścia:  
```python
["lser", 3.14159, 4.56789, "Quick", 27.1234]
```

### Przykład wyjścia:  
```python
(["LSeR", "uick"], [3.14, 27.12])
```

**Zadanie 2:**  
Napisz program realizujący **szyfr Cezara**. Program powinien:  
1. Przyjąć od użytkownika:  
   - ciąg znaków (*string*), który ma zostać zaszyfrowany,  
   - liczbę całkowitą (*int*) określającą, o ile miejsc ma być przesunięta każda litera w ciągu.  
2. Wykorzystać przesunięcie znaków w alfabecie:  
   - Przyjmujemy, że alfabet to litery od `a` do `z` oraz `A` do `Z`.  
   - Jeśli przesunięcie wykracza poza zakres alfabetu, należy je kontynuować od początku alfabetu.  
3. Program powinien zwrócić zaszyfrowany ciąg znaków.  

Przykład:  
Dla wejścia:  
```
Podaj tekst: abc  
Podaj przesunięcie: 2  
```  
Program powinien zwrócić:  
```
Zaszyfrowany tekst: cde  
```  

---

**Zadanie 3:**  
Napisz program realizujący **sortowanie przez wstawianie**. Program powinien:  
1. Przyjąć od użytkownika listę liczb całkowitych jako wejście.  
2. Wykorzystać algorytm sortowania przez wstawianie do uporządkowania listy w porządku rosnącym.  

Przykład działania:  
Dla wejścia:  
```
[2, 45, 2, 9]  
```  
Program powinien zwrócić:  
```
Posortowana lista: [2, 2, 9, 45]  
```  

**Zadanie wysłać na**
```
grzegorz.czechmanowski@put.poznan.pl
```