# MicroPython
use ESP8266 training MicroPython

LED 模組

#匯入 machine 裡的所有類別

>from machine import Pin


#匯入程式庫裡的time

>import time


#自訂變數名稱：p2, 接腳編號2, Pin.OUT代表輸出

>p2 = Pin(2, Pin.OUT)


#執行迴圈, LED會每個1秒亮、滅

>for i in range(3):

  >p2.value(0)
  
  >time.sleep(1)
  
  >p2.value(1)
  
  >time.sleep(1)
