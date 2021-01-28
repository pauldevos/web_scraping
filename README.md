# web_scraping with Python


- BeautifulSoup (bs4)
- Requests
- lxml
- Selenium


Yeah cookies are key to Selenium. That's how I auto post polls to Twitter for example, otherwise you get "login from new device" warnings each time the script runs. Some other useful stuff: add a helper function or decorator to add random delay.  Check the display state of elements before you click. If you need to input text, looping charwise with minor delay is less suspicious than sending larger strings at once. Aria labels for accessibility can be helpful to target elements with obfuscated classes / ids
