# Predykcja średniej oceny IMDb filmu za pomocą regresji LASSO

**Opis:**  
Model LASSO na danych TMDB 5000 pozwala prognozować średnią ocenę użytkowników IMDb (vote_average) na podstawie cech filmu (gatunki, czas trwania, rok premiery, popularność, liczba głosów).

**Kroki:**
1. EDA
2. Preprocessing (one-hot genres, standardization)
3. LassoCV + Lasso
4. Ewaluacja (MSE, R²)
5. Interpretacja (top 10 cech)

**Uruchomienie:**  
```bash
python -m venv env
source env/bin/activate      # na macOS/Linux
.\env\Scripts\Activate.ps1   # na Windows PowerShell
pip install -r requirements.txt
jupyter notebook
