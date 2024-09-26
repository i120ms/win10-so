# użytkownicy i grupy

## użytkownicy - komendy

- Lista kont użytkowników w systemie: ```net user```
- Lista grup użytkowników w systemie: ```net localgroup```
- Tworzenie konta użytkownika: ```net user nazwa_użytkownika /add```
- Ustawienie hasła użytkownika: ```net user nazwa_użytkownika hasło_użytkownika```
- Wymuszenie zmiany hasła użytkownika po zalogowaniu: ```net user nazwa_użytkownika /logonpasswordchg:yes```
- Zablokowanie możliwości zmiany hasła użytkownika: ```net user nazwa_użytkownika /passwordchg:no```
- Ograniczenie czasu pracy użytkownika: ```net user nazwa_użytkownika /times:{czas}```
- Wyświetlenie ustawień konta użytkownika: ```net user nazwa_użytkownika```
- Ustawienie daty wygaśnięcia konta użytkownika: ```net user nazwa_użytkownika /expires:{data}```
- Ustawienie komentarza dla konta użytkownika: ```net user nazwa_użytkownika /comment:”treść_komentarza”```
- Dodatnie pełnej nazwy konta użytkownika: ```net user nazwa_użytkownika /fullname:”Pełna nazwa”```
- Dezaktywacja konta użytkownika: ```net user nazwa_konta /active:no```
- Dodanie konta użytkownika do grupy lokalnej: ```net localgroup nazwa_grupy nazwa_konta /add```
- Usunięcie konta użytkownika: ```net user nazwa_konta /del```

## grupy - komendy

- Wyświetla listę grup lokalnych 
.
```net localgroup```

- Wyświetla listę użytkowników należących do danej grupy 
.
```net localgroup grupa```
```net localgroup klasa_2```

- Tworzy nową grupę
.
```net localgroup nowa_grupa /add```
```net localgroup klasa_2 /add```

- Usuwa daną grupę
.
```net localgroup grupa /delete``` 
```net localgroup klasa_2 /delete```

- Dodaje użytkownika do danej grupy 
.
```net localgroup grupa użytkownik /add```
```net localgroup klasa_2  uczen /add```

- Usuwa użytkownika z danej grupy
.
```net localgroup grupa użytkownik /delete```
```net localgroup klasa_2  uczen /add```
