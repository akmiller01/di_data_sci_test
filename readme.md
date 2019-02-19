# DI Data Science Tests

## Instructions

Please read these instructions carefully.

You may fork this repository, or download the data in `test_data` otherwise.
You may submit your answers in code in the form of a forked repository, or via a zipped folder of code, tables, etc.

## `test_data/scrambled_dhs.csv`

1. Using the column `wealth`, what is the mean wealth index score? What is the median? Please show your work.
2. Using the columns `wealth` and `weights` what is the weighted mean of the wealth index score?
3. Using the columns `wealth` `weights` and `region` what is the weighted mean of the wealth index score by region?
4. Using your results from the previous question, assuming that `region` in `scrambled_dhs.csv` maps to `REGCODE` in `shps/sdr_subnational_boundaries`, present your results with human-readable region names.
5. Using your results from the previous question and/or `shps/sdr_subnational_boundaries`, please make a visualisation of your results.

## `test_data/CRS 2010.zip`

1. If you extract this zip file, you will find a text file which represents the raw Creditor Reporting System data for 2010. How many rows have either a `LongDescription` or a `ShortDescription` that contains the word `"vaccine"`?
2. What is the total US Dollar Deflated (`usd_disbursement_defl`) for flows from (`DonorName`) the US to (`RecipientName`) Uganda?

