# Zadanie
Bufor 9 elementowy FIFO. Dwóch konsumentów i dwóch producentów. Producent A produkuję literę A. Producent B produkuje
literę B. Element A odczytuje (usuwa) konsument A. Elementy B odczytuje (usuwa) konsument B. Odczyt (usunięcie) jest
dozwolone, gdy liczba elementów w buforze jest większa niż 3.

# Kompilacja `g++`
```sh
g++ Buffer.cpp main.cpp Buffer.h -std=gnu++11 -pthread -o monitory.o
```


