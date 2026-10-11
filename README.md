# Błyskawiczna instalacja C++ (g++) na Windowsie

Ten skrypt automatycznie pobiera i konfiguruje kompilator C++ (MinGW/g++). 

## Instrukcja

1. Otwórz menu Start, wpisz **PowerShell** i uruchom go.
2. Skopiuj poniższy kod w całości, wklej do okna terminala i wciśnij **Enter**:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser -Force; Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression; scoop install gcc
```

3. Poczekaj, aż na ekranie przestaną pojawiać się nowe napisy (może to zająć chwilę).

> [!WARNING]
Uruchom ponownie Visual Studio Code (a dla pewności zrestartuj cały komputer).

Gotowe! Możesz teraz normalnie używać komendy g++ w terminalu.
