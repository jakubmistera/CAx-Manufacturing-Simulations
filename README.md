# ⚙️ Symulacje Procesów Wytwarzania i Analiza Numeryczna (CAE/CAx)

Repozytorium stanowi zbiór projektów inżynierskich z zakresu komputerowego wspomagania inżynierskiego (CAE/CAD). Projekty skupiają się na cyfrowej optymalizacji procesów technologicznych (odlewnictwo, obróbka plastyczna) oraz zaawansowanych symulacjach wytrzymałościowo-termicznych.

## 🛠 Wykorzystane technologie i oprogramowanie
* **Projektowanie CAD:** Dassault Systèmes SolidWorks
* **Analizy Numeryczne i Symulacje (CAE):** * **MES (Metoda Elementów Skończonych):** Analiza naprężeń, temperatur i odkształceń.
  * **MOS (Metoda Osobliwości):** Szybkie analizy analityczne obszarów z dużymi gradientami.
  * **Symulacje obróbki plastycznej:** Badanie rozkładu prędkości odkształceń w funkcji czasu i przemieszczenia.

---

## 📁 Struktura Repozytorium i Opis Projektów

### 1️⃣ Optymalizacja technologii odlewania (SolidWorks)
Projekt polegający na zaprojektowaniu układu wlewowego i nadlewów w celu eliminacji rzadzizn i porowatości skurczowych w gotowym detalu.
* **Zakres prac:** Modelowanie 3D detalu, ocena pierwotnej porowatości, zaprojektowanie dedykowanego kołnierza oraz układu zasilającego.
* **Wyniki:** Skuteczne wyeliminowanie porowatości wewnątrz odlewu. Zoptymalizowano proces tak, że stosunek masy zaprojektowanego nadlewu do odlewu wyniósł **29,8%** (spełniony rygor technologiczny <50%).

### 2️⃣ Zaawansowana analiza numeryczna: MES vs MOS
Projekt badawczy polegający na zestawieniu i krytycznej ocenie dwóch metod numerycznych (MES i MOS) na przykładzie obciążanego prostopadłościanu.
* **Analizowane parametry:**
  * **Equivalent Stress (Naprężenia):** Identyfikacja miejsc koncentracji naprężeń na krawędziach podstaw.
  * **Effective Plastic Strain (Odkształcenia plastyczne):** Analiza deformacji struktury, ze szczególnym uwzględnieniem zachowania wierzchołków.
  * **Rozkład Temperatury:** MES precyzyjnie wskazał rozkład od 760°C do 1080°C, podczas gdy MOS mocno uprościł model do jednolitych 1090°C.
  * **Material Flow & Contact Pressure:** Badanie gradientów przepływu materiału i rozkładu ciśnień kontaktowych.
* **Wnioski:** MES jest metodą pierwszego wyboru dla precyzyjnych analiz konstrukcyjnych, termicznych i dynamicznych. MOS świetnie sprawdza się do szybkich szacunków i wstępnej identyfikacji lokalnych ekstremów.

### 3️⃣ Symulacja procesu spęczania (Formowanie na zimno)
Analiza numeryczna procesu obróbki plastycznej (spęczania), badająca wpływ prędkości roboczej narzędzia (stempla) na zachowanie materiału i rozkład odkształceń.
* **Zakres prac:** Modelowanie układu stempel-materiał-kowadło. Przeprowadzenie symulacji dla trzech prędkości stempla: **1 mm/s, 10 mm/s oraz 100 mm/s**.
* **Wyniki i obserwacje:** * **Niskie prędkości (1 mm/s):** Zapewniają równomierny rozkład prędkości odkształceń i wysoką stabilność siły względem przemieszczenia, co jest kluczowe dla materiałów kruchych.
  * **Wysokie prędkości (100 mm/s):** Prowadzą do szybkiej deformacji, jednak generują silnie zróżnicowany rozkład odkształceń, co zwiększa ryzyko powstawania mikropęknięć i wad strukturalnych.

---

## 📷 Wizualizacje wyników symulacji

### Stworzony model  w SolidWorks
<img width="798" height="638" alt="image" src="https://github.com/user-attachments/assets/ba96ba7b-5a48-4925-8681-aa528d0cc0cf" />

### Porowatość bez nadlewu
<img width="738" height="534" alt="image" src="https://github.com/user-attachments/assets/54b231a1-cc8c-4d42-a67b-dca5b7a005cb" />

### Model wraz ze stworzonym nadlewem oraz kołnierzem
<img width="566" height="625" alt="image" src="https://github.com/user-attachments/assets/904cce31-e728-445b-bd49-9a80d2e5176c" />

### Porowatość z wykorzystaniem powyższego nadlewu z kołnierzem wygląda następująco i jest akceptowalna
<img width="558" height="585" alt="image" src="https://github.com/user-attachments/assets/bcfebd3e-2674-45c7-9811-54d45132586e" />

### Porównanie wyników – MOS vs MES
<img width="947" height="518" alt="image" src="https://github.com/user-attachments/assets/816521f2-223d-4dff-8c52-4b50e0fb1d71" />

### Porównanie Effective Plastic Strain Rate (1/s) dla prostopadłościanu - MES vs MOS
<img width="945" height="427" alt="image" src="https://github.com/user-attachments/assets/31ef8090-3a70-4d44-b155-0bec6f5e4618" />

### Próbka po spęczaniu z prędkością stempla 1 mm/s, z narzędziami
<img width="637" height="711" alt="image" src="https://github.com/user-attachments/assets/afc30c2a-2592-4929-89df-dfed5f4e7d13" />

### Wykres siły od przemieszczenia
<img width="947" height="559" alt="image" src="https://github.com/user-attachments/assets/f028730e-dd7e-4eb0-9155-5e9569126f22" />

---
*Projekty zrealizowane w ramach zajęć inżynierskich na Politechnice Warszawskiej (Kierunek: Automatyzacja i Robotyzacja Procesów Produkcyjnych).*
