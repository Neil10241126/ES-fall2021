
# 嵌入式系統實作 - 實作1

##  1-1 在TinkerCAD開一個新的Circuit, 加上一個外部的LED, 並且ON (亮) 1秒, OFF(滅) 1秒

---

![image](https://user-images.githubusercontent.com/63353432/132113779-7f5ee648-9461-446a-8a81-9a51ebf94ad0.png)

---

## 程式碼

````C

void setup()
{
  pinMode(13, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(1000); 
  digitalWrite(13, LOW);
  delay(1000); 
}
````
