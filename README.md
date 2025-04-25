# Zalando Scraper

Scrape Zalando utilising Decodo's Web Scraping API

<p align="center">
<a href="https://dashboard.decodo.com/?page=residential-proxies&utm_source=socialorganic&utm_medium=social&utm_campaign=resi_trial_GITHUB"><img src="https://github.com/user-attachments/assets/60bb48bd-8dcc-48b2-82c9-a218e1e4449c"></a>
</p>


[![](https://dcbadge.vercel.app/api/server/Ja8dqKgvbZ)](https://discord.gg/Ja8dqKgvbZ)

## Dependencies

```
BeautifulSoup
```

## Authentication

Once you have an active Web Scraping API subscription, you can try sending a request right from the dashboard Web Scraping API > API playground method tab simply by clicking on Send Request. You will also see an example of a curl request generated on the right. 

### This Pyhton code example uses Base64 encoded ```user:pass``` authentication.

| Parser type | Example location         | Download |
| -------------------- | ------------------------ | -------- |
| HTML to JSON        | [zalando_html_parser.py](https://github.com/Decodo/zalando_python_scaper/blob/main/zalando_html_parser.py) |``` curl https://raw.githubusercontent.com/Decodo/zalando_python_scaper/blob/main/zalando_html_parser.py > zalando_html_parser.py ``` |

## HTML to JSON

This Python script extracts Brand Name, Model, Price, discount, Category, Product, and image URL data directly from the HTML of the Zalando website and saves it to a JSON file.
