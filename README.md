# ssb-api-python-examples

## Jupyter notebooks on how to use Python to access Statstics Norways APIs

Statistics Norway has got three external APIs. The most important one is the [API:Create your own dataset](https://www.ssb.no/en/omssb/tjenester-og-verktoy/api/px-api) or PxWebApi. Here are examples on how to use the APIs from Python. 

The plan is to give all examples both in Norwegian and in English.
- The [doi_csv](eks1_doi_csv_nor.ipynb) examples in this repository are a very basic towards the [API: Readymade datasets](https://data.ssb.no/api/v0/dataset/?lang=en).

Examples, for det time beeing, in Norwegian only
- [kt-csv-nor](kt-csv-nor.ipynb) import a readymade dataset as CSV to Pandas, and shows basic plots using Pandas plot and Plotly Express.
- [Laks-no](laks-no.ipynb) is a basic example on using http POST to query API:Create your own datasets or [PxWebApi](https://www.ssb.no/en/omssb/tjenester-og-verktoy/api/px-api).
- [Two-tables-in-one-chart](two-tables-one-chart_nor.ipynb) combines datasets from two Statbank tables using Pandas pivot, and plot them using Matplotlib.
- [Konkurs-datokonv-nor](konkurs-datokonv.ipynb) shows the use of a general function for converting the time variable from category to date, and the difference of the two in two plots. The table used is on weekly bankruptcies.
- [nr-dateconv-nor](nr-datokonv.ipynb) shows posting the same query for GDP changes to tables with different frequency, and the use of the function dateconv which converts fra Categories to dateformat and set a Pandas PeriodIndex.

- [Klasskommune](klass_kommune2020.ipynb) shows how to use Statistics Norways [Statistical Classifications and Codelists](https://www.ssb.no/en/klass/) API, to get municipality IDs.

