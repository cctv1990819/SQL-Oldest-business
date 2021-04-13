# SQL-Oldest-business
This is a SQL project using Postgresql.
BusinessFinancing.co.uk researched the oldest company that is still in business in (almost) every country and compiled the results into a dataset. 
In this project, you'll explore that dataset to see what they found.

Tables may use:
categories:
  category_code: (varchar) Code for the category of the business.
  category: (varchar) Description of the business category.
countries:
  country_code: ISO 3166-1 3-letter country code.
  country: (varchar) Name of the country.
  continent: (varchar) Name of the continent that the country exists in.
businesses:
  business: (varchar) Name of the business.
  year_founded:	(int)	Year the business was founded.
  category_code:	(varchar)	Code for the category of the business.
  country_code:	(char)	ISO 3166-1 3-letter country code.
