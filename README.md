# TridentTD_ESP_TrueRandom
ESP8266/ESP32 True Random Library  
----  

ไลบรารี่ True Random เป็นการ random ตัวเลขที่ไม่ซ้ำเลยจริงๆ แต่ต้น   
สำหรับ ESP8266/ESP32  

วิธีใช้  
```
esp.random();         // random เลขขนาด 32bit  
esp.random(1000);     // random เลขตั้งแต่ 0-999  
esp.random(20,100);   // random ตั้งแต่ 20-99
esp.genUUID();        // สร้าง UUID 
esp.genMacAddress();  // สร้าง Mac Address
```
  
TridentTD  
16 August 2018  

