Library tests and tutorials.
These are codes mostly from documentation and tutorials.
Let me know if you find a missing source. 

# PEP 8 
- [PEP 8 stlye guide](https://www.python.org/dev/peps/pep-0008/)

# Selected Python Books
- [Hitchhiker's guide](http://python-guide-pt-br.readthedocs.io/en/latest/)
- [Interactive Python Algorithms and Data Structures](http://interactivepython.org/runestone/static/pythonds/index.html)
- [Python Tips](http://book.pythontips.com/en/latest/index.html) Intermediate python
- [Ipython cookbook](https://github.com/ipython-books/cookbook-code)

# O'Reilly Archive 
- [Free O'Reilly Books](http://www.oreilly.com/data/free/archive.html)

# Algorithms and Data Structures
### Big O
- [Big O Cheat Sheet](http://bigocheatsheet.com/)
- [Big O in Plain English](https://stackoverflow.com/questions/487258/what-is-a-plain-english-explanation-of-big-o-notation/487278#487278)
- [O(log n) described](https://stackoverflow.com/questions/2307283/what-does-olog-n-mean-exactly) 

### Array Sequences
- Listm Tuples, and String 

### Stacks Queues and Deques

### Linked List 

### Recursion 

### Trees

### Searching and Sorting 

### Graph Algorithms 

- [Portilla's Notebooks](http://nbviewer.jupyter.org/github/jmportilla/Python-for-Algorithms--Data-Structures--and-Interviews/tree/master/) 
- [Portilla's GH](https://github.com/jmportilla/Python-for-Algorithms--Data-Structures--and-Interviews/tree/master/)

# Jupyter
- [Jupyter Notebook Manual](https://athena.brynmawr.edu/jupyter/hub/dblank/public/Jupyter%20Notebook%20Users%20Manual.ipynb)

# Pandas
- [Pandas Documentation](http://pandas.pydata.org/pandas-docs/stable/index.html)
- [Pandas Cookbook](http://nbviewer.jupyter.org/github/jvns/pandas-cookbook/tree/v0.1/)
- [Pandas Udemy Portilla Notes](https://github.com/jmportilla/Udemy-notes)
- [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
  - Array, Series, DataFrames
  - Index, Reindex, Drop, Select/slice, Alignment
  - Rank, Sort, Summary, Missing Data
  - Index Hierarchy
  - Input and output
  - Merge, Merge on index, Concatenate, Combine 
  - Reshape, Pivot, Duplicates
  - Mapping, Replace, Rename index
  - [Categorical Data](http://pandas.pydata.org/pandas-docs/stable/categorical.html)
  - Binning, Outliers
  - Permutation 
  - groupby on DataFrames
  - groupby on Dict and Series
  - Aggregate
  - Splitting, Applying, Combining
  - Cross-Tabulation 
 - [Pandas exercises](https://github.com/guipsamora/pandas_exercises)
 - `pandas.Series.apply(lambda x : func of x )`
 - pandas.cut() returns indices of half open bins 
 - pandas.MultiIndex
 - pandas.reindex 
 - [Split Apply Combine in R](https://www.jstatsoft.org/article/view/v040i01)

# SQL
- [SQL practise](https://lagunita.stanford.edu/courses/DB/SQL/SelfPaced/courseware/ch-sql/seq-exercise-sql_movie_query_core/)
- [sqlzoo](https://sqlzoo.net/) 
- [w3schools](https://www.w3schools.com/sql/)
- Basics: [w3schools](https://www.w3schools.com/sql/default.asp)
- Basics: [MODE Basics](https://community.modeanalytics.com/sql/tutorial/sql-in-mode/), MODE Inter
1. SELECT
2. FROM
3. WHERE
    * IN, BETWEEN
    * wildcards `%`, `_` 
    * `CONCAT`,`REPLACE`, `AS` 
    * `ROUND`, `LENGTH`
    * =, !=, AND, OR, XOR 
4. GROUP BY
5. HAVING
6. ORDER BY
- Aggregate: COUNT, SUM, MIN/MAX, AVG
- DISTINCT 
- CASE
- JOIN: Outer, INNER, Left, Right, FULL
- JOIN: UNION, Self
- [MODE Advanced](https://community.modeanalytics.com/sql/tutorial/sql-data-types/)
- [Relational algebra](https://en.wikipedia.org/wiki/Relational_algebra), [Relational Databse](https://en.wikipedia.org/wiki/Relational_database)

# Sklearn
- [Sklearn examples](http://scikit-learn.org/stable/auto_examples/index.html) 

# NetworkX

# Snap.py

# Numpy

# Scipy

# Matlpotlib
- [Pyplot](http://matplotlib.org/api/pyplot_api.html)

# Seaborn
- [Seaborn Documentation](https://seaborn.pydata.org/tutorial.html)

# Unix
- [awk and sed](http://www.theunixschool.com/p/awk-sed.html)

# Scraping
1. Check terms, legatily 

### Date and Time 
- `dt = datetime.datetime.strptime(string_date, fmt)`
- [datetime docs](https://docs.python.org/2/library/datetime.html#datetime.datetime.strptime) 
- [converting string to date time SO](https://stackoverflow.com/questions/466345/converting-string-into-datetime)

### Beautiful Soup
- [Docs](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

### HTML
- [w3schools](https://www.w3schools.com/html/)
- Also, Check codeacademy 

### CSS
- [w3schools](https://www.w3schools.com/css/default.asp)

### XML
- [w3schools](https://www.w3schools.com/xml/default.asp)
- [xml.sax blog post](http://www.knowthytools.com/2010/03/sax-parsing-with-python.html)

# RegEx
- [RE guide](http://www.zytrax.com/tech/web/regex.htm), RE guide [examples](http://www.zytrax.com/tech/web/regex.htm#experiment)
- [RE Python docs], RE Python [HOWTO](https://docs.python.org/2/howto/regex.html#regex-howto)
- Portialla's [notes](http://nbviewer.jupyter.org/github/jmportilla/Complete-Python-Bootcamp/blob/master/Regular%20Expressions.ipynb)
- Book: Regular expression: Pocket Reference 

### `re.search()`
- `re.search(pattern, text)` returns a *match* object 
- `match.start()`, `match.end()`

### `re.split()`, `re.findall()`
- `re.split(split_term,phrase)`
- `re.findall(term, phrase)`

### Metacharacters . ^ $ * + ? { } [ ] \ | ( )
- `*` is repeated 0 or more times 
- `+` is repeated 1 or more times 
- `?` is 0 or 1 
- `{m}` for *m* number of occurances
- `{m,n}` minimum *m* and maximum *n* repetitions 
```
 'sd*'           # s followed by zero or more d's
 'sd+'           # s followed by one or more d's
 'sd?'           # s followed by zero or one d's
 'sd{3}'         # s followed by three d's
 'sd{2,3}'       # s followed by two to three d's
```
### Charcater sets [ ]
- [ab] searches for occurrences of either a or b.
```
  '[sd]'     # either s or d
  's[sd]+'   # s followed by one or more s or d
```
- `^` excludes terms
- `[^xy...z]` will match any single character not in the brackets 

### Character Ranges 
- `[start-end]`
```
  '[a-z]+'        # sequences of lower case letters
  '[A-Z]+'        # sequences of upper case letters
  '[a-zA-Z]+'     # sequences of lower or upper case letters
  '[A-Z][a-z]+']  # one upper case letter followed by lower case letters
```

### Escape Codes 
- `\d`: a digit
- `\D`: a non-digit
- `\s`: a whitespace 
- `\S`: a non-whitespace
- `\w`: alphanumeric
- `\W`: non-alphanumeric
```
  r'\d+'   # sequence of digits
  r'\D+'   # sequence of non-digits
  r'\s+'   # sequence of whitespace
  r'\S+'   # sequence of non-whitespace
  r'\w+'   # alphanumeric characters
  r'\W+'   # non-alphanumeric
```
- use of *r* to escape backslash 

### GIFs
- [sort file names numerically SO](https://stackoverflow.com/questions/4623446/how-do-you-sort-files-numerically)
- [creating GIFs](https://stackoverflow.com/questions/753190/programmatically-generate-video-or-animated-gif-in-python)

# Git Tutorials
1. There are repos 
2. There is a master branch
3. To make changes, you create another branch (_working version_)
4. Change and make a commit (_saved changes_)
5. Open pull request (_propose changes_ from a branch)
6. Merge pull request (_add changes_ in master branch)
7. Delete version branch 

- [Git tutorial](https://try.github.io/levels/1/challenges/1) 
- [Github guides](https://guides.github.com/)
- [How to use git](http://lifehacker.com/5983680/how-the-heck-do-i-use-github)
- [Pro Git Book](https://git-scm.com/book/en/v2)  

# Aside 
## Udacity 
- [A/B testing](https://www.udacity.com/course/ab-testing--ud257) 
- [Techinical interview](https://www.udacity.com/course/technical-interview--ud513) 
 
## Coding links
- [LeetCode](https://leetcode.com/)
- [Topcoder](https://www.topcoder.com/)
 
## Blogs
- [Analytics Vidya](https://www.analyticsvidhya.com/)
