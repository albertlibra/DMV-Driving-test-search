# DMV-Driving-test-search

Made for fun.Automatically search for the earliest date available on 4 DMV mega centers in Houston.

## Prerequisite

- **Selenium** package: conda install Selenium or pip install Selenium
***
Add webdriver exe into your PATH

- If you use Firefox,include [geckodriver](https://github.com/mozilla/geckodriver/releases) in your PATH 
- If you use chrome,include [this driver](https://sites.google.com/a/chromium.org/chromedriver/downloads) in your PATH
- webdrivers for [other browers](http://seleniumhq.github.io/selenium/docs/api/py/#drivers)
***
### step one:
- This will open a blank window in your web browser.Keep this window **open** until you finish.(If you failed open a new window then make sure the webdriver is in your PATH)
- User need to edit the command *below* to provide correct path of your webdriver:
```python
driver= webdriver.Chrome('/usr/bin/chromedriver_liunx64/chromedriver')
```
