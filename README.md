# Environmentally-friendly food recommendation app

A working prototype of an app to calculate the CO2 emissions of products from popular supermarkets, and hence recommend a user alternatives to their food which are better for the environment.
The project uses data taken from scientific studies, and calculates emissions based on the average emissions to produce each of the ingredients, and the emissions produced by transporting the item from where it was produced.

## Technologies
- Python with BeautifulSoup for scraping the supermarket websites
- Python with Pandas, Heroku Postgres and SQL for database management
- Tkinter for user interface

## The project in motion

https://www.loom.com/share/9eb27d82e6be4c389ba2c03faecc066e

## What the files do

'tkinterGUI.py' runs the main interface

'Heroku_functions.py' contains necessary functions to interact with Heroku

'get_sainsburys_sectors.py' updates the 'sainsburys_sectors' database

'get_sainsburys_products.py' updates the 'sainsburys_products' database

'upload_emissions_stats.py' was used to upload the database 'SuEatableLife_Food_Fooprint_database.csv'

'add_emissions.py' calculates the emissions of products and adds this information to the 'sainsburys_products' database

'A level coursework 13.docx' is the full write-up which was submitted for my A-level coursework


Limitation - usage blocked by some firewalls including 'Smoothwall', ensure firewalls are disabled before running
