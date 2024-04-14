## 01: DataScienceEcosystem.ipynb

## 02 : Data Science Tools and Ecosystem

## 03: Introduction

#### In this notebook, Data Science Tools and Ecosystem are summarized.

## 04: List Data Science Languages

#### Some of the popular languages that Data Scientists use are:

#### Ordered List

##### 01: Python
##### 02: R
##### 03: SQL (Structured Query Language)

## 05: List Data Science Libraries

#### Some of the commonly used libraries used by Data Scientists include:

#### Ordered List

01: Pandas

02: NumPy

03: Matplotlib

## 06: Tableof Data Science Tools

#### Data Science Tools


```python
!pip install tabulate
```

    Requirement already satisfied: tabulate in c:\users\shuja\anaconda3\lib\site-packages (0.8.10)
    


```python
from tabulate import tabulate

# Define the data
data = [["Data Science Tools"],
        ["Jupyter Notebook"],
8        ["RStudio"],
        ["Spyder"]]

# Draw the table
print(tabulate(data, headers="firstrow", tablefmt="pipe"))
```

    | Data Science Tools   |
    |:---------------------|
    | Jupyter Notebook     |
    | RStudio              |
    | Spyder               |
    

## 07: Introducing Arithmetic Expression 

### Below are a few examples of evaluating arithmetic expressions in Python:


```python
result =1+2
print(result)
```

    3
    


```python
a=2*3
print(a)
```

    6
    


```python
b=10
c=2
print(b/c)
```

    5.0
    

## 08: Multiply and Add Numbers

### This a simple arithmetic expression to mutiply then add integers.


```python
(5*4)+4
```




    24




```python
(10*6)+10
```




    70



## 09: Convert minutes to hours

### This will convert 200 minutes to hours by diving by 60.


```python
minutes = 200
hours = minutes / 60
print(hours)  
```

    3.3333333333333335
    

## 10: List Objectives

### List popular languages for Data Science

#### Five popular languages for data science are:

1. Python
2. R
3. SQL (Structured Query Language)
4. Java
5. MATLAB

## 11 : Author 

Name: Shuja Ur Rahman

## Objectives

### Unordered list

#### List  of popular languages for Data Science

Here are five popular languages for data science:

1. Python
2. R
3. SQL (Structured Query Language)
4. Julia
5. Scala
