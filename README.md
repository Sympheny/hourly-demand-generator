# Hourly Demand Generator
With this Excel tool you can quickly **create annual energy demand profiles** with hourly resolution. Demand profiles can be created for a single building up to several buildings from different categories.

![Overview of the Excel generator](/resources/overview_generator_Sympheny.jpg)


## How does it work?

1. Enter the total usable area (m2) and the specific energy requirement (kWh/m2) in each of the yellow worksheets (``1 MFH`` to ``13 Hotel``)
The specific energy requirement (kWh/m2) for space heating, warm water and electricity can also be obtained in the worksheet ``CREM Qh, ww, e`` for different building ages

1. The aggregated hourly demand profiles for each energy source are calculated automatically and displayed in the green worksheet ``Hub``

1. Click on ``Export energy demand for Sympheny`` button in the worksheet ``Hub``. XLSX files with the hourly energy demand profile (1 file per energy carrier) are generated automatically. You can read these files directly and obtain your optimal system with [Sympheny Web App](https://app.sympheny.com/login)
