# OMXS30 Projekt
# OMXS30 – Förutsägelse av dagliga rörelser med AI

##Steg 1: Dataförberedelse och analys
- Hämtade historisk data (2015–2024) från Yahoo Finance (^OMX)
- Skapade Return och Target (1 = uppgång, 0 = nedgång)
- Rensade data och visualiserade stängningskurser
- Lagt till indikatorer: MA5, MA20, RSI14, Volatility10, Weekday
- Utforskat fördelning mellan upp- och nedgångsdagar

---

#Steg 2: Modellbygge och utvärdering
- Byggt feature-matris (X, y) och one-hot-kodat Weekday
- Delat data i tränings- och testperiod (80/20 kronologiskt)
- Standardiserat numeriska features
- Tränat Logistic Regression (baseline)
- Utvärderat med accuracy, ROC och AUC
- Testat Random Forest som icke-linjär modell
- Nästa steg: feature importance, korsvalidering och förbättrad prediktiv precision

---

📅 **Senaste version:** 2025-10-21  
✏️ **Utvecklat i Google Colab → synkat till GitHub**
