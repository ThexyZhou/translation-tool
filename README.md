# translation-rool
当初只是为了偷懒..仅供娱乐
## 使用方法
将鼠标放至待翻译的单词/语句的左上方，显示坐标后再放至右下方
## 原理
* 寻找两次鼠标放置的坐标
* 截取两次坐标构成的矩形
* 提取图片中的文字
* 送至有道翻译
* 爬取翻译结果(source.txt)
## 需要安装
* tesseract-ocr-3.05.2
* Google Chrome(版本尽量新一)
* MongoDB(非必须，仅用于存储每次查询的单词)
## 所需库
* selenium
* pyquery
* pyautogui
* tesserocr
* pymongo
* pillow
