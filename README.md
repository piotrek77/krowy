# 🐄 KROWA.EXE (Web Edition)

> Współczesna, webowa rekonstrukcja kultowego polskiego programu-żartu z lat 90. (Windows 95/98).

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Platform: Web](https://img.shields.io/badge/Platform-HTML5%20%2F%20JS-brightgreen.svg)](#)
[![Privacy: GoatCounter](https://img.shields.io/badge/Analytics-GoatCounter%20(No%20Cookies)-purple.svg)](https://www.goatcounter.com)

---

### 🌐 Wypróbuj na żywo!
👉 **[https://krowy.cytr.us/](https://krowy.cytr.us/)** 👈

*Projekt jest dumnie hostowany na serwerach **[Mikr.us](https://mikr.us/?r=2fc012ae)** – gorąco polecam te ultra-tanie, polskie serwery VPS, idealne do małych projektów!*

---

## 📌 O projekcie

W drugiej połowie lat 90. ubiegłego wieku, w epoce dyskietek 3,5 cala i pracowni komputerowych z Windowsem 95/98, wielką popularnością cieszyły się mini-programy żartobliwe (tzw. *joke-programs*). Jednym z takich klasyków polskiego wczesnego internetu był anonimowy programik **`KROWA.EXE`**, stworzony na fali głośnego wówczas tematu choroby szalonych krów (BSE).

Całość składała się z małego, szarego okienka i prostego dylematu:
* **Krowa zdrowa** — odtwarzała klasyczne, spokojne *„Muuuu...”*.
* **Krowa szalona** — zaczynała się zwyczajnym rykiem, który płynnie przechodził w histeryczny, ludzki chichot.

Ten projekt to wierny, nostalgiczny port tamtej aplikacji uruchamiany bezpośrednio w przeglądarce internetowej.

---

## ✨ Cechy projektu

- **Oryginalne zasoby:** Autentyczne pliki dźwiękowe (`.mp3`) oraz zrzut okna programu (`apka.png`).
- **Styl retro 1:1:** Interfejs strony wykorzystuje oryginalną grafikę programu "Krasula Mleczna 2.0" w całości, na którą nałożone są precyzyjnie przeliczane, responsywne obszary klikalne (hotspoty).
- **Zero zależności (Vanilla Web):** Cały kod (HTML, CSS, JavaScript) zamknięty jest w jednym, błyskawicznie ładującym się pliku `index.html`.
- **Prywatność (Privacy-first):** Zintegrowany lekki licznik odwiedzin i kliknięć [GoatCounter](https://www.goatcounter.com) — brak ciasteczek, brak profilowania, zgodność z RODO.

---

## 📂 Struktura katalogów

```text
krowy/
├── index.html        # Kod całej aplikacji: interfejs, style, obsługa audio i śledzenie
├── apka.png          # Oryginalna grafika "Krasula Mleczna 2.0" służąca jako wygląd całej strony
├── plik1.mp3         # Oryginalny dźwięk lewego przycisku ("Krowa Zdrowa")
├── plik2.mp3         # Oryginalny dźwięk prawego przycisku ("Krowa Zwariowana")
├── KROWY.EXE         # Pierwotny plik wykonywalny z lat 90. (archiwalny)
├── LICENSE           # Licencja MIT z klauzulą dla historycznych zasobów
├── .gitignore        # Ignorowane pliki środowiskowe (np. .agy/)
└── README.md         # Niniejsza dokumentacja
```

---

## 🚀 Uruchomienie

### 1. Lokalnie
Wystarczy pobrać repozytorium i otworzyć plik `index.html` w dowolnej współczesnej przeglądarce:
```bash
git clone https://github.com/[twoj-login]/krowa-exe.git
cd krowa-exe
# Możesz otworzyć plik bezpośrednio lub odpalić prosty serwer:
python3 -m http.server 8080
```

### 2. GitHub Pages
Repozytorium jest gotowe do natychmiastowego hostowania przez **GitHub Pages**:
1. Wejdź w ustawienia repozytorium (**Settings** -> **Pages**).
2. Wybierz gałąź `main` (lub `master`) i folder `/ (root)`.
3. Kliknij **Save** — strona będzie dostępna pod adresem `https://[twoj-login].github.io/[repozytorium]/`.

---

## 📊 Analityka (GoatCounter)

W projekcie wykorzystano licznik **GoatCounter**:
- Nie używa cookies ani pamięci lokalnej (Local Storage / Session Storage).
- Zlicza wyłącznie unikalne wizyty bez gromadzenia danych identyfikujących użytkownika.
- W pliku `index.html` możesz zmienić atrybut `data-goatcounter` na własny adres subdomeny w GoatCounter lub usunąć skrypt, jeśli nie potrzebujesz statystyk.

---

## 📜 Licencja i prawa autorskie (Licensing & Disclaimer)

* **Kod źródłowy:** Całość napisanego kodu (HTML, CSS, JavaScript) udostępniona jest na licencji **[MIT](LICENSE)**.
* **Materiały archiwalne (Audio i Grafika):** Wszystkie pliki dźwiękowe oraz graficzne zostały wyekstrahowane z historycznego, anonimowego programu typu freeware `KROWY.EXE` (lata 90. XX wieku). Zostały one dołączone wyłącznie w celach archiwalnych, edukacyjnych i ochrony cyfrowego folkloru tamtej epoki (*digital preservation / abandonware*).