# house-prices

Start Jupyter notebook

    jupyter notebook house-prices.ipynb

And change URL to <http://127.0.0.1>

Data from <https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads>

> Contains HM Land Registry data © Crown copyright and database right 2021. This
> data is licensed under the Open Government Licence v3.0.

Download latest

```sh
curl -o pp-2023.csv http://prod1.publicdata.landregistry.gov.uk.s3-website-eu-west-1.amazonaws.com/pp-2023.csv
grep "\"RG30 " pp-2023.csv > ./RG30-2023.csv
grep "\"RG31 " pp-2023.csv > ./RG31-2023.csv
```
