# nfl-pbp

## Goal:

To use play-by-play data of NFL games in the recent seasons to track success rate of various plays based on location on the field.

## Current status:

Scraping play by play data for 2018*, 2017*, 2016-, 2015, 2014, 2013. Will see if 2019 is available.

* \* = finished
* \- = currently scraping

## Scraping data:

Utilizes nflscrapR (https://github.com/maksimhorowitz/nflscrapR). R package that has various functions to scrape data, including play by play. Then dumping each year's data into a .csv. Will import the .csv into python for analysis.
