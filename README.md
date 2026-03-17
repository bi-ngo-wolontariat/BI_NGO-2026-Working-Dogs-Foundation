# BI_NGO 2026 – Working Dogs Foundation

Repozytorium zawiera dane udostępnione w ramach projektu wolontariatu analitycznego **BI_NGO 2026**, realizowanego we współpracy z [**Working Dogs Foundation**](https://workingdogs.pl/).

Dane mogą zostać wykorzystane do analiz i wizualizacji wspierających działania edukacyjne, informacyjne i promocyjne fundacji.

## O projekcie BI_NGO

Więcej informacji o projekcie oraz zasadach udziału w wolontariacie znajdziesz na [stronie](https://bingo.jezykdanych.pl/).

## Dane do analizy

### 1. Sytuacja psów w Polsce

Dane w tym folderze przedstawiają kontekst problemu bezdomności psów i kotów w Polsce oraz funkcjonowania schronisk dla zwierząt. Dataset obejmuje lata **2005–2024** i zawiera informacje o liczbie zwierząt przyjmowanych do schronisk, liczbie adopcji oraz liczbie schronisk w Polsce. Dane pochodzą z raportów [**Głównego Inspektoratu Weterynarii (GIW)**](https://www.wetgiw.gov.pl/nadzor-weterynaryjny/schroniska-dla-bezdomnych-zwierzat) dotyczących schronisk dla bezdomnych zwierząt.

📂 Lokalizacja:  
[`dane/sytuacja_psow_w_polsce`](dane/sytuacja_psow_w_polsce)

📄 Pliki:

- `schroniska_zwierzeta_polska.csv`
- `schroniska_zwierzeta_polska.xlsx`

---

#### Ważne informacje metodologiczne

- Liczba zwierząt przyjętych do schroniska oznacza **liczbę przyjęć**, a nie liczbę unikalnych zwierząt.  
  Jedno zwierzę mogło zostać przyjęte do schroniska więcej niż jeden raz.

- W kategorii **adopcji** uwzględniane są również **zwroty zwierząt właścicielom**. GIW w oficjalnych raportach nie podaje, jaki odsetek adopcji stanowią zwroty właścicielom.

- Całkowita liczba schronisk obejmuje również schroniska dla koni oraz placówki, w których w danym roku nie przebywały zwierzęta.

---

#### Uwagi dotyczące danych

W raportach źródłowych GIW występowały rozbieżności między zestawieniami dla liczby psów w schroniskach (2008, 2019) oraz liczby kotów w schroniskach (2018, 2019); w datasecie przyjęto wartości najczęściej występujące w raportach.

---

#### Populacja psów w Polsce

W Polsce nie funkcjonuje powszechny obowiązek znakowania i rejestrowania psów i kotów.  
Z tego powodu nie istnieją oficjalne dane dotyczące liczby zwierząt domowych.

Szacunkowe dane o populacji psów pochodzą z badań i raportów organizacji zajmujących się rynkiem zwierząt domowych oraz problemem bezdomności zwierząt. Na tego typu estymacje powołuje się również [**Najwyższa Izba Kontroli (NIK)** w swoich analizach dotyczących bezdomności zwierząt w Polsce](https://www.nik.gov.pl/plik/id,30164,vp,33186.pdf).

| Źródło | Szacowana liczba psów | Szacowana liczba kotów |
|------|------|------|
| [The Voice of the European Pet Food Industry (2023)](https://europeanpetfood.org/wp-content/uploads/2025/06/FEDIAF-Facts-Figures-2025.pdf) | 8 440 000 (strona 5) | 7 546 000 |
| [State of Pet Homelessness (2022/2023)](https://cms.stateofpethomelessness.com/s3media/2024-01/SoPH-Poland.pdf?VersionId=cG.R9DSm1uogH_YA2ke8frLtJdyKhDh1) | 7 090 000 (strona 3) | 5 250 000 |

---

#### Psy w gospodarstwach domowych

Według [raportu **The Voice of the European Pet Food Industry (2023)**](https://europeanpetfood.org/wp-content/uploads/2025/06/FEDIAF-Facts-Figures-2025.pdf):

- w **49% gospodarstw domowych w Polsce jest co najmniej jeden pies**
- w **41% gospodarstw domowych jest co najmniej jeden kot**

---

#### Adopcje ze schronisk

Badania pokazują, że tylko część opiekunów psów w Polsce przygarnia zwierzę ze schroniska.

| Źródło | Odsetek opiekunów, którzy adoptowali psa ze schroniska |
|------|------|
| [Badanie Karmimy Psiaki / Minds & Roses](https://karmimypsiaki.com.pl/blog/polacy-wobec-bezdomnych-zwierzat-badanie-karmimy-psiaki-i-agencji-minds-roses/) | 17% |
| [State of Pet Homelessness](https://cms.stateofpethomelessness.com/s3media/2024-01/SoPH-Poland.pdf?VersionId=cG.R9DSm1uogH_YA2ke8frLtJdyKhDh1) | 11% |

Dodatkowo w badaniu Karmimy Psiaki **9% respondentów wskazało, że zwierzę zostało znalezione**.

### 2. Dane Working Dogs Foundation

Dane dotyczą działań prowadzonych przez **Working Dogs Foundation** od 2023 roku.

📂 Lokalizacja </br>
[`dane/dzialalnosc_fundacji`](dane/dzialalnosc_fundacji)

📄 Pliki:

- `working_dogs_foundation-dane_2023-2025.csv`
- `working_dogs_foundation-dane_2023-2025.xlsx`
- `working_dogs_foundation-dane_finansowe.csv`
- `working_dogs_foundation-dane_finansowe.xlsx`
- `working_dogs_foundation-wypowiedzi_beneficjentow.csv`
- `working_dogs_foundation-wypowiedzi_beneficjentow.xlsx`
- 

## Materiały pomocnicze

W repozytorium dostępne są również materiały, które mogą zostać wykorzystane przy tworzeniu wizualizacji.

- [zdjęcia psów](https://drive.google.com/drive/folders/1f9ZN0ieHXyxIKA575r3rAfF6hgouSO41?usp=drive_link)
- [logotypy i identyfikacja wizualna fundacji](https://drive.google.com/drive/folders/1FZVMY9e8IerHz-PP2CZyjZQ9nQjZ9M8o?usp=drive_link)

Zachęcamy do przygotowywania wizualizacji zgodnie z identyfikacją wizualną **Working Dogs Foundation**.  
W folderze z materiałami znajdziesz logotypy, kolory oraz inne elementy, które mogą pomóc zachować spójność wizualną przygotowanych materiałów.

## Jak korzystać z danych

Rekomendujemy pobranie danych lokalnie przed rozpoczęciem pracy nad wizualizacją.

Nie zalecamy budowania dashboardów bezpośrednio na plikach w repozytorium.

Dane mogą być w przyszłości aktualizowane o kolejne lata.


## Ograniczenia danych

Dane mogą zawierać uproszczenia wynikające ze źródeł lub sposobu agregacji.

Przy interpretacji wyników warto uwzględnić kontekst działalności fundacji oraz dostępność danych w poszczególnych latach.

## Dodatkowe źródła

Dla osób zainteresowanych szerszym kontekstem problemu bezdomności zwierząt w Polsce polecamy również poniższe materiały:

- **[Raport: Sprawa Bezdomnych Zwierząt](https://sprawabezdomnychzwierzat.pl/raport/)** – opracowanie na podstawie danych pozyskanych od gmin w Polsce.

- **Statystyki dot. schronisk od [Biura Ochrony Zwierząt](https://www.boz.org.pl/stats/index.htm)**  

- **[W 2024 r. w Polsce psy pogryzły ludzi niemal 35 tysięcy razy](https://prawo.gazetaprawna.pl/artykuly/9898018,pogryzienia-przez-psy-100-dziennie-350-tys-rocznie-prawo-wymaga-zmian.html)**  

- **[Raport Najwyższej Izby Kontroli](https://www.nik.gov.pl/aktualnosci/bezdomnosc-zwierzat.html) – Bezdomność zwierząt: wydatki rosną, a problem wciąż nierozwiązany**

-----

## **Powodzenia!**

Czekamy na Twoje wizualizacje 💛

Klaudia & Ela
