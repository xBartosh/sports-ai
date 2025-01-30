# 📌 Projekt Klasyfikacji Sportów za pomocą CNN

## 📂 [Zbiór danych](https://www.kaggle.com/datasets/gpiosenka/sports-classification?resource=download)
Model bazuje na zestawie danych zawierającym obrazy sześciu różnych sportów. Aby poprawnie przygotować zbiór danych do treningu, należy wykonać następujące kroki:

1. **Zostawić tylko foldery dla sześciu sportów**, które będą używane w klasyfikacji.
2. **Przenieść zawartość folderów ‘valid’ oraz ‘test’ do ‘train’**, ponieważ model automatycznie dzieli dane na zbiór treningowy i walidacyjny.
3. Struktura folderów powinna wyglądać następująco:
   ```
   data/
   ├── train/
       ├── baseball/
       ├── cricket/
       ├── mushing/
       ├── nascar racing/
       ├── rock climbing/
       ├── swimming/
   ```
   Folder `data/train` powinien znajdować się w **roocie projektu**, a wewnątrz niego powinny być foldery odpowiadające poszczególnym kategoriom sportów.

---

## 🚀 Uruchomienie Modelu
Wybór architektury sieci neuronowej:
- **CNN** → Uruchomienie kodu w pliku `cnn.ipynb`.
- **VGG** → Uruchomienie kodu w pliku `vgg.ipynb`.

Aby uruchomić notebook:
1. Otwórz terminal i przejdź do katalogu projektu.
2. Uruchom środowisko Jupyter:
   ```sh
   jupyter notebook
   ```
3. Wybierz `cnn.ipynb` lub `vgg.ipynb` i wykonaj wszystkie komórki kodu.

---

## ⚠️ Ważne Uwagi
- Program **nie korzysta z oddzielnego zbioru testowego** – podział na dane treningowe i walidacyjne następuje automatycznie.
- Upewnij się, że masz zainstalowane wymagane biblioteki, np.:
  ```sh
  pip install tensorflow keras numpy matplotlib scipy scikit-learn
  ```

---

## 🏁 Podsumowanie
1️⃣ Przygotuj zbiór danych zgodnie z instrukcją.  
2️⃣ Wybierz architekturę sieci (CNN lub VGG).  
3️⃣ Uruchom odpowiedni notebook (`cnn.ipynb` lub `vgg.ipynb`).  
4️⃣ Rozpocznij trening modelu.

