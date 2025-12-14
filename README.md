# Siamese Audio Classifier

Projekt modelu Siamese Network do klasyfikacji i porównywania par nagrań audio z wykorzystaniem OpenL3 do ekstrakcji cech i PyTorch Lightning do trenowania.

## Instalacja środowiska

### Wymagania
- Python 3.7 lub wyżej
- pip

### Kroki instalacji

#### 1. Tworzenie wirtualnego środowiska (venv)

```bash
python3 -m venv .venv
```

#### 2. Aktywacja wirtualnego środowiska

**Na Linux:**
```bash
source .venv/bin/activate
```

**Na Windows:**
```bash
.venv\Scripts\activate
```

#### 3. Instalacja wymaganych pakietów

```bash
pip install -r requirements.txt
```

## Struktura projektu

```
siamese-audio-classifier/
├── dataset/                 # Zbiór danych
│   └── MAD_dataset/        # Dataset MAD
│       ├── training/       # Dane treningowe
│       ├── test/           # Dane testowe
│       ├── training.csv    # Plik CSV ze wskaźnikami treningowymi
│       └── test.csv        # Plik CSV ze wskaźnikami testowymi
├── lightning_logs/         # Logi z TensorBoard/PyTorch Lightning
├── dataloader.ipynb        # Jupyter Notebook dla ładowania danych
├── requirements.txt        # Plik z wymaganiami projektowymi
└── README.md              # Ten plik
```
