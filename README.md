# etf_analyzer

This Jupyter Notebook is an analyzer for a Fintech ETF consisting of PYPL, SQ, GS, and GDOT. 

---

## Technologies

Project uses:

[Pandas](https://pandas.pydata.org/)

[pathlib](https://docs.python.org/3/library/pathlib.html)

[hvplot](https://hvplot.holoviz.org/)

[SQLAlchemy](https://www.sqlalchemy.org/)

[Numpy](https://numpy.org/)



---

## Installation Guide

Run this program in Jupyter notebook and have hvplot, numpy and SQLAlchemy installed



---

## Usage

Utilize Jupyter Labs to interact with the software program

!["Jupyter Labs Example"](https://miro.medium.com/max/955/1*mXGu0MeYgnUkyR9ybVlQpg.png)

**Key example code for hvPlot graph**
```
# Using hvplot, create an interactive line plot that visualizes the ETF portfolios cumulative return values.
etf_cumulative_returns.hvplot(
    xlabel="Date",
    ylabel="Cumulative Return",
    title ="Cumulative Return for PYPL, GDOT, SQ and GS",
    rot=90, 
    height = 500,
    width = 1000
)
```

---

## Contributors

Hugo Kostelni

---

## License

Open Source