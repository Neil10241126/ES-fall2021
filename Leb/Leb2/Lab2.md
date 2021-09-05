
#   嵌入式系統 - 實作2: 會呼吸的RGB LED,  按鍵控制, 狀態輸出 

##  B1 實作2-1, analogWrite(): 並且觀查LED亮度變化是否有像"呼吸的效果"和示波器的波形有什麼關連性? (互動1), (2021-09-05)

---

![image](https://user-images.githubusercontent.com/63353432/132114413-da8b4faa-4c8b-4762-94ba-7233975b25e6.png)

---

##  程式碼
````C
// C++ code
//
void setup()
{
  pinMode(9, OUTPUT);
}

void loop()
{
  digitalWrite(9, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(9, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}

````