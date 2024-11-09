# mpt
Modern Portfolio Theory
Az anyagot a Kürt Akadémia (Start) Data Science képzésre készítettem. Ez volt a vizsgamunkám.
A téma: Modern portfolio elmélet vizsgalata élő részvényadatokkal (Yahoo finance letöltésekkel).

1) blind_monkey_simulated portfolio optimization.ipynp - ez a munkafüzet tartalmazza a részvények mutatóinak alapszámítasait, valamint egy pseudo (eloszlás mentes) portfolio generálast. A kapott legjobb mutatoval rendelkezo portfolio eredményeit az elemzes végen visszamerjuk, kiszámoljuk a belöle képezhető bétákat, majd az eredményt regresszi analízissel ellenörizzuk.
2) genetic_algo_simulated portfolio_optimization.ipynb - ez a munkafüzet egy saját építésu genetikus algoritmust használ az optimális portfolio meghatározására. Miutan megvan a ortfolio eredményeit az elemzes végen visszamerjuk, kiszámoljuk a belöle képezhető bétákat, majd az eredményt regresszi analízissel ellenörizzuk.
3) SLSQP_efficient_frontier_calculation.ipynb - ez a munkafüzet egy SLSQP eljárást használja a lehetseges portfoliok legjobbjának megkeresésére. A Sharpe Ratio mutatobol képzett fúggvény maximumát keressük. Az elérhető maximum hozam és a legalacsonyabb volatilitással rendelkezö portfolio kozott hozamokra visszaszámolja a program a portfolio összetételt és annak volatilitását. A legjobb ortfolio eredményeit az elemzes végen visszamerjuk, kiszámoljuk a belöle képezhető bétákat, majd az eredményt regresszi analízissel ellenörizzuk.
4) Markowitz_efficient frontier_Benninga_FINAL.ipynb - ez a munkafüzet a lineáris algebra számitásokat tartalmaz amelyek segítségével meghatározzuk az efficient frontier gorbéjét. Az eredményt visszamérjük, ellenörizzuk a kapott béta mutatókat regresszio analizissel. A training idöszakra végezzuk el a tesztet. Ezt követöen az eredményt visszamérjuk a training idöszakra, majd a teszt időszakra. klustering eljárással megkeressük, hogy milyen cégcsoportok (szektorok) miatt történtek a változások.



-------------------------
#mpt
### Modern Portfolio Theory

This material was prepared for the **Kürt Academy (Start)** Data Science course. It served as my exam project.  
**Topic:** Examination of Modern Portfolio Theory using live stock data (downloaded from Yahoo Finance).

---

1. **`blind_monkey_simulated_portfolio_optimization.ipynb`**  
   This notebook contains the basic calculations of stock metrics and a pseudo (distribution-free) portfolio generation. At the end of the analysis, the results of the best-performing portfolio are backtested, its beta values are calculated, and the results are validated using regression analysis.

2. **`genetic_algo_simulated_portfolio_optimization.ipynb`**  
   This notebook uses a custom-built genetic algorithm to determine the optimal portfolio. After obtaining the portfolio, its results are backtested, beta values are calculated, and the results are validated using regression analysis.

3. **`SLSQP_efficient_frontier_calculation.ipynb`**  
   This notebook applies an SLSQP procedure to identify the best portfolio among possible options. It seeks the maximum value of a function derived from the Sharpe Ratio. The program calculates the portfolio composition and volatility for returns between the achievable maximum return and the lowest-volatility portfolio. At the end of the analysis, the best-performing portfolio's results are backtested, beta values are calculated, and the results are validated using regression analysis.

4. **`Markowitz_efficient_frontier_Benninga_FINAL.ipynb`**  
   This notebook contains linear algebra calculations used to determine the efficient frontier curve. The results are backtested, and the beta values obtained are validated using regression analysis. The test is performed on the training period. Subsequently, the results are backtested for both the training and testing periods. A clustering method is used to identify which company groups (sectors) contributed to the changes. 
