import selenium
from selenium import webdriver
from selenium.webdriver.chrome.options import Options
from selenium.webdriver.chrome.service import Service
service = Service("chromedriver.exe")
options = webdriver.ChromeOptions()
driver = webdriver.Chrome(service=service, options=options)
driver.get("https://www.youtube.com/")
driver.get("https://www.youtube.com/watch?v=Jn09UdSb3aA")
time.sleep(30)
driver.quit()
