# ssb-api-python-examples
## Examples on how to use Python to access Statstics Norways APIs

Statistics Norway has got three external APIs. The most important one is the [API:Create your own dataset](https://www.ssb.no/en/omssb/tjenester-og-verktoy/api/px-api) or PxWebApi. The plan is to post examples on how to use the APIs from Python.

The doi_csv examples in this repository are a very basic towards the [API: Readymade datasets](https://data.ssb.no/api/v0/dataset/?lang=en).

Laks-no is a basic example on using http POST to query API:Create your own datasets or [PxWebApi](https://www.ssb.no/en/omssb/tjenester-og-verktoy/api/px-api).

Klasskommune shows how to use Statistics Norways [Statistical Classifications and Codelists](https://www.ssb.no/en/klass/) API, to get municipality IDs.

Two-tables-in-one-chart combines datasets from two Statbank tables using Pandas pivot, and plot them using Matplotlib.

Konkurs-nor shows the use of a function for converting the time variable from category to date, and the difference of the two in two plots. The table used is on weekly bankruptcies.

BNP-dateconv shows posting the same query for GDP changes to tables with different frequency, and the use of the function dateconv.

The plan is to post all examples both in Norwegian and in English.
