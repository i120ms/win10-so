<h1 align="center" style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">
Skrypty // Pliki wsadowe - Windows 10
</h1>

### Tworzenie plików wsadowych - part I
.
- tryb tekstowy (CMD) - ```copy con <lokalizacja>```
- tryb graficzny - ```opcja <nazwa pliku> <1.bat>```

### Odpalenie pliku
.
- tryb tekstowy - ```<lokalizacja> <nazwa pliku> lub start <nazwa pliku>```
- tryb graficzny: 
1. ```@echo off``` - wyłączamy wyświetlanie komend. używamy na początku skryptu
1. ```@echo on``` - włączamy wyświetlanie komend. używamy na końcu skryptu
3. ```pause``` - zatrzymuje działanie programu

### Tworzenie plików wsadowych - part II
.
- ```C:\> a.bat New 1``` - stworzenie pliku a.bat z parametrami New i 1
- ```%1 / %liczba%``` - odwołanie do zmiennej
- ```goto``` - przejście do etykiety - ```goto <etykieta>```
- ```if / if NOT```- jeśli warunek zostaje spełniony lub nie to stanie się coś - ```if <warunek> <np: mkdir C:\test>```
- ```if errorlevel2``` - jeśli poziom błędu poprzedniej komendy = 2 to robi coś - ```if errorlevel2 <np: mkdir C:\test>```
- ```if exist / not exist```
- ```if %liczba%==5```
- ```if %1=="New" pol```