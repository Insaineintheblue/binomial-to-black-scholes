# From the Discrete Model to the Black-Scholes Formula

Python implementation and bilingual dissertation written for the 1st year of the Magistère de Mathématiques (AI specialization) at the Université de Bourgogne, under the supervision of Mr. Samuel Herrmann.

## Project Content

This repository contains the mathematical framework and the numerical applications developed to analyze option pricing, moving from discrete-time models to continuous-time limits.

### 1. Theory (Dissertation)
Along the way, the dissertation covers:
 
- Arbitrage, hedging portfolios, and the risk-neutral probability measure (one-period model)
- The general (d+1)-asset, k-state model, and the first fundamental theorem of asset pricing
- Dynamic discrete-time models: filtrations, self-financing strategies, martingale measures
- The CRR binomial model: European and American option pricing, the Snell envelope, optimal exercise boundaries
- Convergence to continuous time and the Black-Scholes formula

Files available:
* `Dissertation_Magistère_1st_year.pdf` (English version)
* `Mémoire_Magistère_1ère_année.pdf` (French version)

### 2. Numerical Implementation (`.ipynb`)
The Jupyter Notebook contains the Python source code for:
* Pricing European and American options using binomial trees.
* Computing the optimal exercise boundary for American options.
* Simulating the convergence of the CRR model toward the Black-Scholes price.
* Testing the model against real market data using a Crédit Agricole warrant (historical data included in `Actions_Crédit_agricole_18.01-17.04.csv`).

## Running the code
 
```bash
pip install numpy scipy matplotlib pandas
jupyter notebook "Python Magistère 1st year.ipynb"
```
 
## Reference
 
Rose-Anne Dana and Monique Jeanblanc, *Financial Markets in Continuous Time*, Springer Finance, 2007.
 
## License
 
MIT — see [`LICENSE`](LICENSE).
