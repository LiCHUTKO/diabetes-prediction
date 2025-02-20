# 📊 Projekt Predykcji Cukrzycy

## 📋 Przegląd

Celem tego projektu jest przewidywanie cukrzycy za pomocą modelu regresji logistycznej. Wykorzystano zbiór danych Pima Indians Diabetes Database. Projekt obejmuje ładowanie danych, wizualizację, przetwarzanie wstępne, trenowanie modelu oraz jego ewaluację.

## 📚 Spis Treści

- [Przegląd](#-przegląd)
- [Instalacja](#-instalacja)
- [Użycie](#-użycie)
- [Struktura Projektu](#-struktura-projektu)
- [Opis Danych](#-opis-danych)
- [Trenowanie Modelu](#-trenowanie-modelu)
- [Ewaluacja](#-ewaluacja)
- [Autor](#-autor)

## 🛠️ Instalacja

Aby uruchomić ten projekt, musisz mieć zainstalowanego Pythona oraz następujące biblioteki:

```bash
pip install -r requirements.txt
```

## 🚀 Użycie

1. Sklonuj repozytorium:
    ```bash
    git clone https://github.com/LiCHUTKO/diabetes-prediction.git
    cd diabetes-prediction
    ```

2. Otwórz Jupyter Notebook:
    ```bash
    jupyter notebook notebook.ipynb
    ```

3. Uruchom komórki w notebooku, aby wykonać projekt krok po kroku.

## 🗂️ Struktura Projektu

```
Diabets/
├── notebook.ipynb
└── README.md
```

## 📊 Opis Danych

Wykorzystano zbiór danych Pima Indians Diabetes Database, który zawiera następujące kolumny:

- **Pregnancies**: Liczba ciąż
- **Glucose**: Stężenie glukozy w osoczu
- **BloodPressure**: Rozkurczowe ciśnienie krwi (mm Hg)
- **SkinThickness**: Grubość fałdu skórnego tricepsa (mm)
- **Insulin**: 2-godzinne stężenie insuliny w surowicy (mu U/ml)
- **BMI**: Wskaźnik masy ciała (waga w kg/(wzrost w m)^2)
- **DiabetesPedigreeFunction**: Funkcja rodowodu cukrzycy
- **Age**: Wiek (lata)
- **Outcome**: Zmienna klasy (0 lub 1)

## 🧠 Trenowanie Modelu

Trenowanie modelu obejmuje następujące kroki:

1. **Ładowanie Danych**: Załaduj zbiór danych z pliku CSV.
2. **Wizualizacja Danych**: Zwizualizuj dane za pomocą histogramów i map cieplnych.
3. **Przetwarzanie Wstępne**: Normalizuj i skaluj cechy.
4. **Podział na Zbiory Treningowy i Testowy**: Podziel dane na zbiory treningowy i testowy.
5. **Trenowanie Modelu**: Trenuj model regresji logistycznej na danych treningowych.

## 📈 Ewaluacja

Model jest oceniany za pomocą następujących metryk:

- **Accuracy**: Proporcja poprawnie przewidzianych przypadków.
- **Precision**: Proporcja pozytywnych identyfikacji, które były faktycznie poprawne.
- **Recall**: Proporcja rzeczywistych pozytywów, które zostały poprawnie zidentyfikowane.
- **F1-Score**: Średnia harmoniczna precyzji i czułości.

Również jest tworzona macierz konfuzji, aby zwizualizować wydajność modelu.

## 👨‍💻 Autor

**LiCHUTKO**