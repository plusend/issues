# Selenium

## Selenium 安装

Selenium 可以模拟用户对浏览器的操作。

### Selenium IDE

https://www.seleniumhq.org/selenium-ide/ 单独使用，可以记录对浏览器的操作。

### Selenium 库

1. `pip install selenium` 安装

2. https://chromedriver.storage.googleapis.com/index.html 下载 driver，并配置到环境变量里，注意需要和你使用的 Chrome 版本相匹配。

## Selenium 使用

1. 使用 Selenium IDE 记录用户的操作过程，然后可以导出为 Python 文件
2. 结合Selenium 提供的接口，编写上一步导出的 Python 文件，添加更丰富的功能