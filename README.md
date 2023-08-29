# Swiggy-webscrapping
This repository showcases a web scraping project involving Swiggy's Bangalore website. The project's objective was to extract data, convert it into CSV format, clean the dataset, and address a specific problem: determining an optimal location for opening a remote kitchen restaurant, along with menu selection.
Project Highlights
Web Scraping: Code and resources in the repository detail the process of scraping data from Swiggy's Bangalore website.
Data Conversion: The scraped data was transformed into CSV format for further analysis and processing.
Data Cleaning: Scripts and notebooks illustrate the steps taken to clean and preprocess the dataset.
Problem Solving: The repository includes methodologies and results for selecting an ideal restaurant location and designing an appropriate menu.
requirements :
import requests
import html_to_json
from selenium import webdriver
from selenium.webdriver.common.by import By
from selenium.webdriver.common.keys import Keys
from pyshadow.main import Shadow
from bs4 import BeautifulSoup
import time
