# basic data types

![types.jpg](basic%20data%20types%2068cb9de477084da6b6134ff617b99515/types.jpg)

## 1.integer/float:前者是整數，後者是有小數點的數字。

### 數字除了四則運算之外，還有mod也就是餘數 符號是% e.g. 10%3=1

### 兩個 * 就是平方 2**3=8

![num1.jpg](basic%20data%20types%2068cb9de477084da6b6134ff617b99515/num1.jpg)

### 1. abs=absolute value =絕對值

### 2. pow=power=平方 e.g. print(pow(2,10))=1024

### 3.max,min 在一串數字裡面找最大或最小的數字

### 4.round=四捨五入 但規則較特殊，在.5的情況下 偶數會捨 奇數會入 e.g. 2.5變2 ,3.5變4

### 5.string/float/int 改變datatypes

# Strings

## 1.string is ordered , it can use indexing and slicing Indexing就是五個數字，第一個數字從0開始算

```python
print("hello"[1]) # it will return e
mySTring="hello"
print(mySTring[-1]) # it will return o
```

## 2.slicing = 以index為基礎

```python
x="abcdefg"
print(x[2:6]) # it will return cdef
print(x[:4]) # 從0數到4 但不包含4
```

## 3.single quote and double quote

## 一串字不可以同時出現兩組雙引號。但可以單雙交叉使用。

## 4.\n 在string裡面加上\n 就會自動斷行

```python
print("I said\n'Good morning'") 
# it will return I said
# good morning
```

## 5.concatenation

## 可以把兩個string加起來，不能將number將string串起來(in python)，但在JavaScript可以。不然就是將Number改成string。

## 6.String is immutable，無法改變的。

```python
myString="hello"
myString[0]="H"
print(myString)  # it will return type error
```

# Python Built-in String method

## 1.len⇒ length

## 2. int不可以用英文表示x(two hundred)x

## 3.upper()/lower() ，就是改變大小寫

## 4.replace()

```python
name="Josh Jordan"
print(name.replace("Josh","kyle")) # it will return kyle Jordan
```

## 5.spilt()/list()

```python
sentence = "Today is a good day"
print(sentence.spilt(" ")) #it will return 1.today2.good3.day...
print(list(sentence)) #每一個字都會被切開。
```

## 6.format()

```python
print("{},{},{}".format(20,"here is another string",3.14))
#it will return 20,here is another string ,3.14
print("{0},{0},{0}").format(20,"here is another string",3.14))
# it will return 20,20,20。because 20 is 0 in index number。
```

## 7.fstring

```python
name=hertz
print(f"hello,my name is{name}")
```

## 8.count() /find()

```python
string="Good day is a good day"
print(string.count(good)) # it will return 1 這是數量
print(string.find(day)) #it will return 5 ，return index number。 
```

## 9.startswith/endswith

## 確認string的開頭跟結尾,而結果會產生TRUE and False

## 10.Other

## string可以跟number相乘，但number僅限interger，不能用float
