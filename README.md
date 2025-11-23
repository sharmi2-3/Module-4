# 4A.Classes and Objects in Python: Calculate the Area of a Circle

##  Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

##  Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## Program
```
class cse:
    def mech(self, r):
        area = 3.14159 * r * r
        print("Area of circle:", round(area, 2))
obj = cse()
radius = float(input())
obj.mech(radius)
```

## Output
<img width="439" height="123" alt="image" src="https://github.com/user-attachments/assets/c719ff26-1dce-4127-8965-26996872c5d4" />


## Result
Thus the program executed successfully.

## 4B.Dictionary Operations in Python: Merging Two Dictionaries

##  Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

##  Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

##  Program
```
dict1 = eval(input())
dict2 = eval(input())
merged_dict = {}
for key in dict1:
    merged_dict[key] = dict1[key]
for key in dict2:
    merged_dict[key] = dict2[key]
print(merged_dict)
```
## Output
<img width="279" height="145" alt="image" src="https://github.com/user-attachments/assets/893aba0b-2d37-4e98-b1e1-a8c0b42294dd" />
<img width="352" height="142" alt="image" src="https://github.com/user-attachments/assets/adeb8068-c40a-4d69-80eb-3430a716ebc4" />
<img width="380" height="144" alt="image" src="https://github.com/user-attachments/assets/cefa8404-1715-485c-89f9-2b5245ac53c7" />



## Result
thus,the program has been executed successfully.

# 4C. Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

##  Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order


##  Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

## Program
```
my_dict = {3: 323, 2: 56, 1: 2, 4: 24, 5: 12, 6: 18}
sorted_dict = sorted(my_dict.items(), key=lambda item: item[1])
print("Keys and Values sorted in alphabetical order by the value")
print(sorted_dict)
```
## Sample Output
<img width="348" height="106" alt="image" src="https://github.com/user-attachments/assets/7fb91096-ce39-493e-9312-06ba5629a82f" />
<img width="349" height="106" alt="image" src="https://github.com/user-attachments/assets/87b2f708-491d-474a-808e-1223044b1cc9" />

## Result

Thus the program executed successfully.

# 4D.Exception Handling in Python: Avoiding Index Errors

##  Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

##  Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

##  Program
```
my_list = [10, 20, 30, 40, 50]
try:
    print(my_list[10])
except IndexError:
    print("You're out of list range")
```

## Output
<img width="449" height="95" alt="image" src="https://github.com/user-attachments/assets/b802e3cf-6fbe-4ba2-ab2b-bec2ab1358ea" />


## Result
Thus the program executed successfully.

# 4E.File Handling in Python: Count Lines Not Starting with 'T'

##  Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

##  Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

##  Program
```
def returnSum(myDict):
    final=0
    for i in myDict.values():
        final+=i
    return final


myDict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :",returnSum(myDict))
```

## Output
<img width="284" height="117" alt="image" src="https://github.com/user-attachments/assets/3a1328f2-c9d1-4937-a2cb-162903d30651" />

## Result
Thus,the program has been executed successfully.
