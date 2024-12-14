# AoC day1, 2023


<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

``` python
samp='1abc2
pqr3stu8vwx
a1b2c3d4e5f
treb7uchet
'
```

      Cell In[1], line 1
        samp='1abc2
             ^
    SyntaxError: unterminated string literal (detected at line 1)

**AI Prompt**

how do I fix this

**AI Response**

The error is occurring because Python is having trouble with the
multi-line string. There are two ways to fix this:

1.  Use triple quotes (““” or ’’’) for multi-line strings, or
2.  Use the `\n` character for line breaks in a regular string

Here’s option 1 with triple quotes:

``` python
samp = '''1abc2
pqr3stu8vwx
a1b2c3d4e5f
treb7uchet
'''
```

Would you like to try one of these approaches? Let me know if you need
any clarification!

``` python
samp = '''1abc2
pqr3stu8vwx
a1b2c3d4e5f
treb7uchet
'''
```

``` python
lines = samp.splitlines() # .splitlines() can convert the \n to list
lines
```

    ['1abc2', 'pqr3stu8vwx', 'a1b2c3d4e5f', 'treb7uchet']

``` python
x=lines[1]
```

**AI Prompt**

how do I tell if a character is a digit

**AI Response**

In Python, you can use the `isdigit()` method to check if a character is
a digit. For example:

``` python
'5'.isdigit()  # Returns True
'a'.isdigit()  # Returns False
```

Would you like to try using this to check some characters in your
strings? I can help you test it out!

``` python
from aocd import get_data
inp = get_data(day=1,year=2023)
```

``` python
xs = inp.splitlines()
```

``` python
x = xs[0]
```

``` python
[o for o in x]
```

    ['f', 'i', 'v', 'e', '8', 'b']

``` python
[o for o in x if o.isdigit()]
```

    ['8']

``` python
digits = [o for o in x if o.isdigit()]
```

``` python
digits[0],digits[-1]
```

    ('8', '8')

``` python
int(digits[0]+digits[-1])
```

    88

``` python
digits[0]+digits[-1]
```

    '88'

``` python
def get_degits(x):
    digits = [o for o in x if o.isdigit()]
    return sum(digits[0]+digits[-1])

get_degits('abc8')
```

    ---------------------------------------------------------------------------
    TypeError                                 Traceback (most recent call last)
    Cell In[1], line 5
          2     digits = [o for o in x if o.isdigit()]
          3     return sum(digits[0]+digits[-1])
    ----> 5 get_degits('abc8')

    Cell In[1], line 3, in get_degits(x)
          1 def get_degits(x):
          2     digits = [o for o in x if o.isdigit()]
    ----> 3     return sum(digits[0]+digits[-1])

    TypeError: unsupported operand type(s) for +: 'int' and 'str'

    TypeError: unsupported operand type(s) for +: 'int' and 'str'
    Traceback (most recent call last):

      File "/usr/local/lib/python3.11/site-packages/IPython/core/interactiveshell.py", line 3577, in run_code
        exec(code_obj, self.user_global_ns, self.user_ns)

      File "<ipython-input-1-6d4b20b01d58>", line 5, in <module>
        get_degits('abc8')

      File "<ipython-input-1-6d4b20b01d58>", line 3, in get_degits
        return sum(digits[0]+digits[-1])
               ^^^^^^^^^^^^^^^^^^^^^^^^^

    TypeError: unsupported operand type(s) for +: 'int' and 'str'

``` python
def get_degits(x):
    digits = [o for o in x if o.isdigit()]
    return int(digits[0]+digits[-1])

get_degits('abc8')
```

    88

``` python
get_degits('abc89asdb1')
```

    81

``` python
sum([get_degits(x) for x in xs])
```

    55029

**AI Prompt**

make a dictionary that have ‘zero’:0, from 0 - 9

**AI Response**

Here’s how you can create a dictionary mapping number words to digits:

``` python
nums = {
    'zero': '0',
    'one': '1',
    'two': '2',
    'three': '3',
    'four': '4',
    'five': '5',
    'six': '6',
    'seven': '7',
    'eight': '8',
    'nine': '9'
}
```

Would you like to test it out? Let me know what you’d like to do with
it!

``` python
nums = {
    'zero': '0',
    'one': '1',
    'two': '2',
    'three': '3',
    'four': '4',
    'five': '5',
    'six': '6',
    'seven': '7',
    'eight': '8',
    'nine': '9'
}
```

make a function have convert strings to number if they have those in
nums

**AI Prompt**

make a function have convert strings to number if they have those in
nums

**AI Response**

Let’s break this down. Do you want to find and convert number words
(like ‘one’, ‘two’) within a string into their digit equivalents?

Before I suggest an approach, could you give me an example of what you
want the function to do? For instance, what should happen with a string
like “onetwothree” or “hello2one”?

This will help me guide you toward the most appropriate solution.

``` python
hello2one would be hello21
```

      Cell In[1], line 1
        hello2one would be hello21
                  ^
    SyntaxError: invalid syntax

**AI Prompt**

hello2one would be hello21

**AI Response**

Ah, I understand now - you want to keep the digits and replace any
number words with their corresponding digits.

Let’s think about how to solve this step by step: 1. First, we’ll need
to find any number words in the string 2. Then replace them with their
corresponding digits 3. Keep any existing digits unchanged

Would you like to try writing this function, or would you like me to
suggest some code to get started?

**AI Prompt**

yes, suggest some code

**AI Response**

Here’s a starting point using string replacement:

``` python
def convert_numbers(s):
    result = s
    for word, digit in nums.items():
        result = result.replace(word, digit)
    return result
```

Try this out and let me know if it works for your needs! We can test it
with some examples like: - “hello2one” - “twothree”

Would you like to try it?

``` python
def convert_numbers(strings):
    for world, digit in nums.items():
        strings = strings.replace(word,digit)
    return strings

convert_numbers('hello1two')
```

    ---------------------------------------------------------------------------
    NameError                                 Traceback (most recent call last)
    Cell In[1], line 6
          3         strings = strings.replace(word,digit)
          4     return strings
    ----> 6 convert_numbers('hello1two')

    Cell In[1], line 3, in convert_numbers(strings)
          1 def convert_numbers(strings):
          2     for world, digit in nums.items():
    ----> 3         strings = strings.replace(word,digit)
          4     return strings

    NameError: name 'word' is not defined

    NameError: name 'word' is not defined
    Traceback (most recent call last):

      File "/usr/local/lib/python3.11/site-packages/IPython/core/interactiveshell.py", line 3577, in run_code
        exec(code_obj, self.user_global_ns, self.user_ns)

      File "<ipython-input-1-e8ad9b5fe513>", line 6, in <module>
        convert_numbers('hello1two')

      File "<ipython-input-1-e8ad9b5fe513>", line 3, in convert_numbers
        strings = strings.replace(word,digit)
                                  ^^^^

    NameError: name 'word' is not defined

``` python
def convert_numbers(strings):
    for word, digit in nums.items():
        strings = strings.replace(word,digit)
    return strings

convert_numbers('hello1two')
```

    'hello12'

``` python
xs_converted = [convert_numbers(o) for o in xs]
```

``` python
xs_converted[0]
```

    '58b'

``` python
xs[0]
```

    'five8b'

``` python
def get_degits(x):
    digits = [o for o in x if o.isdigit()]
    return int(digits[0]+digits[-1])

get_degits('abc8')
```

    88

``` python
def get_digits(x):
    digits = [o for o in x if o.isdigit()]
    return int(digits[0]+digits[-1])

get_digits('abc8')
```

    88

``` python
xs_digits = [get_digits(o) for o in xs_converted]
```

``` python
xs_digits[0]
```

    58

``` python
sum(xs_digits)
```

    55194

**AI Prompt**

for nums dictionary, could you also covers something like sixteen,
basically all of the digits

**AI Response**

The `nums` dictionary currently only covers zero through nine, since
those are the basic digit words. Numbers like “sixteen” are compound
numbers (made up of “six” and “teen”) and aren’t typically converted to
single digits.

If you want to handle numbers like “sixteen”, we should first
clarify: 1. What range of numbers do you want to cover? 2. What digit
should “sixteen” convert to - should it be ‘1’ and ‘6’, or something
else?

Let me know what you’re trying to achieve and I can help you expand the
dictionary appropriately!

**AI Prompt**

sixteen would be like 16, yes I’d like to have a dictionary of compound
numbers

**AI Response**

I can help you create an expanded dictionary that includes compound
numbers. Here’s a suggestion - should we add:

1.  Numbers 11-19 (eleven through nineteen)
2.  Multiples of 10 up to 90 (twenty, thirty, etc.)
3.  Or would you like to go up to a specific number?

Let me know which range you’d like to cover and I can help you create
the appropriate dictionary!

**AI Prompt**

yes, 1-2

**AI Response**

I’ll help you create an expanded dictionary that includes numbers 11-19
and the multiples of 10 up to 90. Here’s the addition to your existing
dictionary:

``` python
nums.update({
    'eleven': '11',
    'twelve': '12',
    'thirteen': '13',
    'fourteen': '14',
    'fifteen': '15',
    'sixteen': '16',
    'seventeen': '17',
    'eighteen': '18',
    'nineteen': '19',
    'twenty': '20',
    'thirty': '30',
    'forty': '40',
    'fifty': '50',
    'sixty': '60',
    'seventy': '70',
    'eighty': '80',
    'ninety': '90'
})
```

Would you like to try this out and see if it works with your existing
code?

``` python
nums.update({
    'eleven': '11',
    'twelve': '12',
    'thirteen': '13',
    'fourteen': '14',
    'fifteen': '15',
    'sixteen': '16',
    'seventeen': '17',
    'eighteen': '18',
    'nineteen': '19',
    'twenty': '20',
    'thirty': '30',
    'forty': '40',
    'fifty': '50',
    'sixty': '60',
    'seventy': '70',
    'eighty': '80',
    'ninety': '90'
})
```

``` python
nums
```

    {'zero': '0',
     'one': '1',
     'two': '2',
     'three': '3',
     'four': '4',
     'five': '5',
     'six': '6',
     'seven': '7',
     'eight': '8',
     'nine': '9',
     'eleven': '11',
     'twelve': '12',
     'thirteen': '13',
     'fourteen': '14',
     'fifteen': '15',
     'sixteen': '16',
     'seventeen': '17',
     'eighteen': '18',
     'nineteen': '19',
     'twenty': '20',
     'thirty': '30',
     'forty': '40',
     'fifty': '50',
     'sixty': '60',
     'seventy': '70',
     'eighty': '80',
     'ninety': '90'}

``` python
sum([get_digits(convert_numbers(o)) for o in xs])
```

    55194

``` python
'5'.isdigit()
```

    True

``` python
'5sdf'.isdigit()
```

    False

``` python
's'.isdigit()
```

    False

``` python
's'.isalpha??
```

    Object `isalpha` not found.

``` python
's'.isalpha()
```

    True

``` python
's'.isalnum()
```

    True

``` python
's'.istitle()
```

    False

``` python
'Ssss'.istitle()
```

    True