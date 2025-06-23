# 🏘️ Projekt: Odhad ceny - Lineární regrese 

## 📄 Popis projektu
Tento projekt je zaměřen na využití lineární regrese k odhadu cen bytů na základě jejich velikosti. Jako datový analytik ve startupu zaměřeném na nemovitosti máš za úkol odhadnout ceny bytů na základě historických dat o velikostech bytů a jejich cenách.

## 🎯 Cíl projektu
Cílem tohoto projektu je vytvořit model, který na základě velikosti bytu odhaduje jeho cenu. Tento model bude využíván k predikci cen pro nové nemovitosti, které firma zvažuje v nabídce.

## 🛠️ Použité nástroje a technologie
- Pandas, Numpy, Matplotlib, Scikit-learn

## 📊 Data
- 545 záznamů


## 📌 Závěr

- **Koeficient (sklon):** `5039,77`  
  → Každé 1 m² navíc zvyšuje cenu o cca 5000 $

- **MAE (průměrná chyba):** `1 041 410 $`  
  → Model se v průměru mýlí o více než 1 milion $

- **R²:** `0,39`  
  → Model vysvětluje jen 39 % variability cen

####  Hodnocení:
Model je nepřesný – **jen velikost nestačí** k odhadu ceny. Výsledky jsou slabé.

####  Doporučení:

- Přidat další faktory *(lokalita, počet pokojů, vybavení…)*
- Použít pokročilejší modely *(např. Random Forest, XGBoost)*

Model ukázal, že velikost bytu má nějaký vliv na cenu, ale ne dostatečný pro přesné predikce.  
Doporučuji přidat další faktory (např. lokalita, počet pokojů, vybavení) a vyzkoušet pokročilejší metody strojového učení pro lepší výsledky.
