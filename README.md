# GISAID EpiCov Sequence Downloader

## Overview
This Python script automates the download of the latest EpiCov sequences from the GISAID platform. It uses **Selenium** for web automation and **BeautifulSoup** for scraping location data from the GISAID Forum. The tool simplifies downloading sequences for all countries in an organized manner.


## Features
- Automates login and navigation on the GISAID website using **Selenium**.
- Scrapes continent and country information from the GISAID Forum with **BeautifulSoup**.
- Automatically downloads and saves sequences in the default `Downloads` folder.
