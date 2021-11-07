#   嵌入式系統 - 實作7: AI-based ES? AI? ML? DL? 要如何入門 (How To Learn)? (W12)

##  Lab 7-1 在你的Google Drive, 建立你的第一個Colab Notebook 

---

實作成果
![image](https://user-images.githubusercontent.com/63353432/140632053-57fa5c7d-8893-4d05-aa7f-c353831f90b6.png)

---

##  Lab 7-2 暖身: 一起來十分鐘學會Python

---

````Python
# task 1: string variable
name = "TA Grace"
print(name)

# task 2: number variable
number = 26
print(number)
print(number*3)
print(number/2)
print(number + number)
print(number - number)

# task 3: function

def printName(firstName, lastName):
  print(lastName + ' ' + firstName)

printName('Grace', 'TA')

# task 4: if else

def printName(firstName, lastName, isCool):
  if isCool:
    print(lastName + ' ' + firstName + ' very cool!')
  else:
    print(lastName + ' ' + firstName + ' not cool!')

# Start
printName('Grace', 'TA', True)
printName('Grace', 'TA', False)

# task 5: for loop

def printName(firstName, lastName, isCool, num):
  for i in range(1, num):
    if isCool:
      print(i, lastName + ' ' + firstName + ' very cool!')
    else:
      print(i, lastName + ' ' + firstName + ' not cool!')

# Start
printName('Grace', 'TA', True, 10)
````


##  Task 5的結果
![image](https://user-images.githubusercontent.com/63353432/140632086-a5ac5d23-e98f-4d71-83d1-020a27a7635a.png)

---

##  Lab 7-3 確認Lab7完成的兩個Notebook都成功的存在你的雲端硬碟/ES2021目錄下

![image](https://user-images.githubusercontent.com/63353432/140632115-7bae02e3-416a-4bae-93a8-6a23b84ea908.png)

