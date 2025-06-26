# Big_Data_Quiz

## Group Members
```
-Irabaruta Willy Norbert(27463)
-Uwimbabazi Sandrine(27399)
-Nshuti Tricia(27253)
-Kwizera Sandrine(26104)
-Rugandura Maurice(27718)
-Murihira Muhire Arsene(27656)

```

### 1.📊 `calculate_age function`
```sql
def calculate_age():
    name = input('Enter your name:')
    year_birth = int(input('Enter your date of birth:'))
    age = 2025 - year_birth
    print(f'{name}, your age is : {age}')
    print('Thank you')
calculate_age()
```
![Conceptual Diagram](https://github.com/Nshutitricia/Big_Data_Quiz/blob/92332e28b3e5111b4912f5e68c0f3f040148df6f/git1.PNG)
### 2.📊 `ispalindrome function`
```sql
def isPalindrome():
    text = input('Enter a text')
    return "Yes, it is palindrome" if text.lower() == text.lower()[::-1] else "No, it is not palindrome"
isPalindrome()
```
![Conceptual Diagram](https://github.com/Nshutitricia/Big_Data_Quiz/blob/92332e28b3e5111b4912f5e68c0f3f040148df6f/git2.PNG)
### 3.📊 `iteratetexts function`
```sql
def iterateTexts():
    text1 = input('Enter first text')
    text2 = input('Enter second text')
    combined = text1 + text2
    char = [n for n in combined]
    print(char)
    print('Thank you for using my application')
iterateTexts()
```
![Conceptual Diagram](https://github.com/Nshutitricia/Big_Data_Quiz/blob/92332e28b3e5111b4912f5e68c0f3f040148df6f/git3.PNG)
