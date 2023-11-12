### Assignment-03 (Strings)
- Change the notebook name with your name and Roll Number.
- Try this as your own, no chatgpt (it's for your learning)
- after completing the assignment, submit this book on google class room.

Create a string variable with your name and print it.



```python
my_name = "SANIA RASHEED"
print(my_name)
```

    SANIA RASHEED
    

Define a multiline string that includes line breaks and print it.



```python
string = """I am Student of M.Phil. 
I am completing my assignment which is assigned by our professor.
It is easy to understand and execute"""
print(string)
```

    I am Student of M.Phil. 
    I am completing my assignment which is assigned by our professor.
    It is easy to understand and execute
    

Access the first character of a string.



```python
first_character = string[0]
print(first_character)
```

    I
    

Access the last character of a string.



```python
len(string)
last_character = string[123]
print(last_character)
```

    c
    

Access the second to the fifth character of a string.


```python
multi_characters = string[1:4]
print(multi_characters)
```

     am
    

Attempt to change a character within an existing string and explain the result.



```python
new_string = string[:9] + 'd' + string[17:]

print(new_string)
```

    I am Studd.Phil. 
    I am completing my assignment which is assigned by our professor.
    It is easy to understand and execute
    


Slice a string to obtain the first 3 characters.



```python
three_characters = string[:3]
print(three_characters)
```

    I a
    

Slice a string to obtain the last 4 characters.



```python
four_characters = string[120:124]
print(four_characters)
```

    exec
    

Slice a string to get every second character.



```python
every_second = string[::2]
print(every_second)
```

    Ia tdn fMPi.
     mcmltn yasgmn hc sasge yorpoesr
    ti ayt nesadadeeue
    

Reverse a string using slicing.


```python
reverse = string[::-1]
print(reverse)
```

    etucexe dna dnatsrednu ot ysae si tI
    .rosseforp ruo yb dengissa si hcihw tnemngissa ym gnitelpmoc ma I
     .lihP.M fo tnedutS ma I
    

Create two string variables and concatenate them.




```python
a = "Sania"
b = "Rasheed"
concatenate = a + b
print(concatenate)
```

    SaniaRasheed
    

Concatenate a string with a number (convert the number to a string first).


```python
message = "my birthday is"
print(message)

num = 12
print(num)

type(num)

string = str(num)
print(string)
type(string)

concatenate = message + string
print(concatenate)
```

    my birthday is
    

Generate a string that repeats "abc" 10 times.




```python
string = "abc" * 10
print(string)
```

    abcabcabcabcabcabcabcabcabcabc
    

Create a string containing a repeating pattern of your choice.


```python
repeat = "12" * 15
print(repeat)
```

    121212121212121212121212121212
    

Convert a string to lowercase using the lower() method.



```python
string = "KINZA"
print(string)
```

    SANIA
    


```python
lower_name = str.lower(string)
print(lower_name)
```

    sania
    


Convert a string to uppercase using the upper() method.



```python
string = "sania"
print(string)
```

    sania
    


```python
upper_name = str.upper(string)

print(upper_name)
```

    SANIA
    

Remove leading and trailing whitespace from a string using the strip() method.



```python
text_message = "   i am a girl and i am a student of M.PHILL   "
print(text_message)
```

       i am a girl and i am a student of M.PHILL   
    


```python
stripped_string = text_message.strip()
print(stripped_string)
```

    i am a girl and i am a student of M.PHILL
    

Check if a string starts with a specific prefix using the startswith() method.


## CONDITION 1:-


```python
message = "SANIA RASHEED"
prefix = "SANIA"
start = message.startswith(prefix)
print(start)
```

    True
    

## CONDITION 2:-


```python
message = "SANIA RASHEED"
prefix = "SANIA"
start = message.startswith(prefix)
print(start)
```

    True
    

Split a string into a list of words using the split() method.



```python
string = "NN & AI CLASS ASSIGNMENT"
splitted = string.split()
print(splitted)
```

    ['NN', '&', 'AI', 'CLASS', 'ASSIGNMENT']
    

Join a list of words into a single string using the join() method.


```python
words = ["Sania" , "Rasheed" , "m.phil" , "student"]
joined = " ".join(words)
print(joined)
```

    Sania Rasheed m.phil student
    


```python

```
