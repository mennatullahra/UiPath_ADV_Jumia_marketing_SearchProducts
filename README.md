## Search Products - Robot Process Automation using UiPath Platform

## Project Overview

The **Search Products** project is a Robot Process Automation (RPA) solution developed using UiPath Platform. It involves automating the process of searching for products from an input Excel file, filtering emails in Outlook, and scraping data from an e-commerce website (Jumia) based on the search query.

## Project Features

- **Send Email with Products:**
  The robot sends an email to your specified account with the Excel file attached, containing the products to search for. The subject of the email will be "Searching Products."

- **Filtering Emails:**
  The robot filters your Outlook emails with the subject "Searching Products." If there are multiple emails with the same subject or no attachment in the email, the robot throws a Business Exception (BE).

- **Jumia Product Search:**
  The robot opens the Jumia website and performs a product search using the subject of the email as the search query. It filters the search results based on the "high to low" price option.

- **Data Scraping and Highlighting:**
  The robot uses data scraping to extract product information, including prices, from the search results on Jumia. It calculates the average price and highlights cells with prices higher than the average price in yellow.


## Supervision
This project has been done under the supervision of **ADVANSYS-ESC**, providing guidance and support throughout the development process.
