# python-notes
Notes from udemy course 
I like compressing data. 

- [Complete Python Bootcamp](https://www.udemy.com/complete-python-bootcamp/)

- [Instructor's notebooks](http://nbviewer.jupyter.org/github/jmportilla/Complete-Python-Bootcamp/tree/master/)

- [Instructor's github repos](https://github.com/jmportilla?tab=repositories) 

- Sec01 and Sec02  
  - JupyterIntro 
  - Python 2 and 3 difference
  - git Intro: [Learn git online](https://try.github.io/levels/1/challenges/1)

- Numbers 

- String 
  - Strings: indexing starts at [0]. 
  - Then [-1] is end. 
  - [:] is all. 
  - [:3] is first three. 
  - [3:] leaves first 3. 
  - [::1]  is increments of all. 
  - [::-1] is everything reversed. 
  - s[:3:-1] does something interesting. 
  - 'original string'.format('appended string')
  - python 3 print() function and not print statement
  - no item/char assignment in string. s[0] = 'x' will not work. 
  - '+' concatenates. '*' repeats. 
  - s.append(), s.split(','), ... 
  
- Print Formatting
  - `print 'bla bra %s %1.3f' %('Hi',3.1456)`
  - `print 'bra bra {x} here {x} there {y}'.format(x='inserted text', y = 3.14)`

- Lists
  - List can hold multiple datatypes. ['Hi', 1, 3.14]
  - List of lists is possible. 
  - l[0] is first element. 
  - l[:3] all unto 3rd. (first 3. i.e., 0,1,2)
  - l = [1,2,[1,3,4]] is valid. l[0][1] returns 3.
  - list comprehensions: [row[0] for row in matrix]. 

- Dictionary
  - dict = {'KeyN':'ValueN', ... }
  - dict['KeyN'] returns 'ValueN',  
  - dictionary supports flexible data types. Lists, etc.
  - nested dictionaries possible. dict['K1']['NestedKM'][2] works
  - dict.keys() returns list of keys, not in order.
  - dict.values() returns list of values.
  - dict.items() returns tuples of ('key', values)
  
- Tuples
  - Tuples are data-type flexible but immutable. 
  - t =(1,2,3), t[0] = 4 will throw an error! 
  - very few methods. t.count(), t.index() 
  
- Files
  - f = open(fileNameString) returns a file object
  - f.read() reads the file and changes reading cursor to eof 
  - f.seek(0) sends cursor back to zero
  - f.readlines() returns list of strings  
  - `%%writefile new.text` to write in file
  - ```for lines in open('new.text'):
      print lines```
  - will print lines
  - Alternatively, for words in open('new.text'): will also  print lines 
  - won't read entire file in memory 
  - f.readlines() will store entire file string in memory. avoid. 
  
- Sets and Booleans
  - Sets are like dictionaries with just keys. 
  - x = set() creates a set
  - x.add(2) adds 2 to set
  - set doesn't allow repetitions. 
  - `set(xlist)` will return non repeating elements of the list 
  - a = True creates a boolean
  - 1 > 2 is a boolean
  - b = None is a placeholder
  
- Practice resourses
  - [Basic practice](http://codingbat.com/python)
  - [Math and harder](https://projecteuler.net/archives)
  - [List of problems](http://www.codeabbey.com/index/task_list)
  - [Sureddit daily practice](https://www.reddit.com/r/dailyprogrammer)
  - [Tough problems](http://www.pythonchallenge.com/)
    
- Objects and Data Structures

- Comparison Operators
  - == equal to
  - != not equal
  - <> not equal
  - < left lesser than right
  - > left greater than right
  - <= lesser than of equal to
  - >= greater than or equal to 
  
- Chained comparison operator
  - `1 < 2 < 3` is same as `1 < 2 and 2 < 3` 
  - `1 < 3 > 2` is same as `1 < 3 and 3 > 2`
  - and
  - or 
  
- Statements
  - python gets rid of () and {} using : and indentation. more readable. 
  - no semi colons like in C++ 
  
- if,elif,else statements
  - if case 1:
    - perform action 1
  - elif case 2:
    - perform action 1
  - else: 
    - perform action 3 
    
- for loops
  - `for element in list_l:` 
    - `print element` 
  - prints elements in the list
  - `for element in string_l:` `print element` prints letters in the string 
  - tuples unpacking
  - l = [(2,4),(6,8),(10,12)] 
  - `for tup in l:` `print tup` prints the tuples
  - `for (t1,t2) in l:` `print t1` prints first element in the tuple 
- `for item in dictionary_d:` `print item` prints keys in the dictionary
- in python 2, `for k,v in d.iteritems():` 
- iteritems() creates a *generator* (comes later)
- in python 3, `for k,v in d.items():`  
    
- while loops
  - while test:
    - code statement 
  - else: 
    - final code statement
  - `break`, breaks out of closest enclosing loop
  - `continue`, continues to the top of closest enclosing loop 
  - `pass`, does nothing at all 
  
- `range()`, `xrange()`
  - `range(stop)` gives list of integers
  - `range(start, stop[, step])`
  - *generator* does not store every instance in memory
  - in python 2, range() returns a list. list saved in memory.  
  - in python 2, xrange() returns a generator. not saved in memory. 
  - in python 3, range() returns a generator. not saves in memory. 
 
- list comprehension
  - creates list. flatten outs a for loop within a list
  - `[ element_function_of_item for item in list_l ]`
  - `lst = [x for x in 'word']` creates ['w', 'o', 'r', 'd']
  - `lst = [x**2 for x in range(0,11)]`
  - conditions work 
  - `[ element_function_of_item for item in list_l if condition_on_item]`
  - nested lists work
  - `[ x**2 for x in [x**2 for x in xrange(1,11) ]]`
  - generator comprehension and dictionary comprehension
  
- Methods
  - methods are functions built into objects
  - object.method(arg1,arg2,...) form
  - use tab to show available methods
  - use shift+tab to show details of a method 
  - help(l.count) to show details of a method 
  - methods as having an argument 'self' referring to the object itself.
  
- Functions
  - 'block of reusable statements'
  
- lambda expressions
  - `lambda num: num**2`returns a function
  - could be saved in a function variable name
  - `square = lambda num: num**2` and call `square(2)`
  - works with multiple arguments, `adder = lambda x,y : x+y`
  - `adder(2,3)`
  - [more notes](https://pythonconquerstheuniverse.wordpress.com/2011/08/29/lambda_tutorial/)
  - works well with map, reduce, and filter 
  - map(function, sequence_iterable) 
  - map(lambda_expression, sequence_iterable)

- Nestes statement and scope
  - **LEGB**
  - Local 
  - Enclosing function
  - Global 
  - Built-in 
  - `globals()` and `locals()` will return respective variables
  - functions are objects and hence could be assigned variable names 
  
- Milestone project 
