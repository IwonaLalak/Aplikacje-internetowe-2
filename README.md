# Aplikacje-internetowe-2

## verbing
- OK  got: 'hailing' expected: 'hailing'
- OK  got: 'swimingly' expected: 'swimingly'
- OK  got: 'do' expected: 'do'

## not_bad
- OK  got: 'This movie is good' expected: 'This movie is good'
- OK  got: 'This dinner is good!' expected: 'This dinner is good!'
- OK  got: 'This tea is not hot' expected: 'This tea is not hot'
- OK  got: "It's bad yet not" expected: "It's bad yet not"

## front_back
- OK  got: 'abxcdy' expected: 'abxcdy'
- OK  got: 'abcxydez' expected: 'abcxydez'
- OK  got: 'KitDontenut' expected: 'KitDontenut'

## donuts
- OK  got: 'Number of donuts: 4' expected: 'Number of donuts: 4'
- OK  got: 'Number of donuts: 9' expected: 'Number of donuts: 9'
- OK  got: 'Number of donuts: many' expected: 'Number of donuts: many'
- OK  got: 'Number of donuts: many' expected: 'Number of donuts: many'

## both_ends
- OK  got: 'spng' expected: 'spng'
- OK  got: 'Helo' expected: 'Helo'
- OK  got: '' expected: ''
- OK  got: 'xyyz' expected: 'xyyz'

## fix_start
- OK  got: 'ba**le' expected: 'ba**le'
- OK  got: 'a*rdv*rk' expected: 'a*rdv*rk'
- OK  got: 'goo*le' expected: 'goo*le'
- OK  got: 'donut' expected: 'donut'

## mix_up
- OK  got: 'pox mid' expected: 'pox mid'
- OK  got: 'dig donner' expected: 'dig donner'
- OK  got: 'spash gnort' expected: 'spash gnort'
- OK  got: 'fizzy perm' expected: 'fizzy perm'


## match_ends
- OK  got: 3 expected: 3
- OK  got: 2 expected: 2
- OK  got: 1 expected: 1

## front_x
- OK  got: ['xaa', 'xzz', 'axx', 'bbb', 'ccc'] expected: ['xaa', 'xzz', 'axx', 'bbb', 'ccc']
- OK  got: ['xaa', 'xcc', 'aaa', 'bbb', 'ccc'] expected: ['xaa', 'xcc', 'aaa', 'bbb', 'ccc']
- OK  got: ['xanadu', 'xyz', 'aardvark', 'apple', 'mix'] expected: ['xanadu', 'xyz', 'aardvark', 'apple', 'mix']

## sort_last
- OK  got: [(2, 1), (3, 2), (1, 3)] expected: [(2, 1), (3, 2), (1, 3)]
- OK  got: [(3, 1), (1, 2), (2, 3)] expected: [(3, 1), (1, 2), (2, 3)]
- OK  got: [(2, 2), (1, 3), (3, 4, 5), (1, 7)] expected: [(2, 2), (1, 3), (3, 4, 5), (1, 7)]

## remove_adjacent
- OK  got: [1, 2, 3] expected: [1, 2, 3]
- OK  got: [2, 3] expected: [2, 3]
- OK  got: [] expected: []
## linear_merge
-  OK  got: ['aa', 'bb', 'cc', 'xx', 'zz'] expected: ['aa', 'bb', 'cc', 'xx', 'zz']
-  OK  got: ['aa', 'bb', 'cc', 'xx', 'zz'] expected: ['aa', 'bb', 'cc', 'xx', 'zz']
-  OK  got: ['aa', 'aa', 'aa', 'bb', 'bb'] expected: ['aa', 'aa', 'aa', 'bb', 'bb']

## lab

```
if __name__ == "__main__":
    print("Hello World")
    
    print("=========== zad1 =========== \n")

    for i in range (1,6):
            if i%2==0:
                    print("-------------")
            else:
                    print("  |	 |	")


    print("\n")
    print("=========== zad2 =========== \n")

    for i in range(0,5):
            if i%2==0:
                    for j in range(0,5):
                            if j%2==0:
                                    print("  |  |  H  |  |  H  |  |  ")
                            else:
                                    print("--+--+--H--+--+--H--+--+--")
            else:
                    print("========+========+========")			


    print("\n")
    print("=========== zad3 =========== \n")			

    sum = 0;
    for i in range(3,1001):
            if i%3==0 or i%5==0:
                    #print(i)
                    sum = sum+i
    print (sum)


>>> fizz()
234168

>>> collatz(13)
10

>>> converter()
Temperatura F? 212
100.0 st C

>>> lists()
[1, 0, 0]
['a', '', '']
[[1], [1], [1]]

>>> lists2()
[1, 0, 0]
['a', '', '']
[[1], [], []]

>>> gcd(8,32)
8

>>> flip_dict({"CA": "US", "NY": "US", "ON": "CA"})
{'CA': ['ON'], 'US': ['CA', 'NY']}

>>> comprehensions_read()
[None, None, None]
[[3, 2, 1, 12], ['a', 'b', 'c', 'aaaa'], [('do',), ['re'], 'mi', ('do', 'do', 'do', 'do')]]
['Y', 'O', 'N']
{8, 2, 3, 5}

>>> comprehensions_write()
2*x +1
[0, 1, 2, 3]
[1, 3, 5, 7]



##Podzielniki 3
[3, 5, 9, 8]
[True, False, True, False]

##Zaczyna się na TA
['TA_sam', 'TA_guido', 'student_poohbear', 'student_htiek']
['sam', 'guido']

##Duże pierwsze litery
['apple', 'orange', 'pear']
['A', 'O', 'P']

##Jeżeli jest litera 'p'
['apple', 'orange', 'pear']
['apple', 'pear']

##Owoc z jego długością krotka
['apple', 'orange', 'pear']
[('apple', 5), ('orange', 6), ('pear', 4)]

##Owoc z jego długością (słownik)
['apple', 'orange', 'pear']
{'apple': 5, 'pear': 4, 'orange': 6}
>>> 

##Lab3.py

>>> print_two(1,2)
Arguments: 1 and 2

>>> print_two_test()
Arguments: 4 and 1
Arguments: 4 and 1
Arguments: 4 and 1

>>> keyword_args(a=4)
a: 4
b: 1
c: X
d: None

>>> print_keyword_args()
a: 5
b: 1
c: X
d: None
a: 5
b: 1
c: X
d: None
a: 5
b: 8
c: X
d: None
a: 5
b: 2
c: 4
d: None
a: 5
b: 0
c: 1
d: None
a: 5
b: 2
c: 4
d: 8
a: 1
b: 1
c: 7
d: None
a: 5
b: 2
c: []
d: 5
a: 1
b: 1
c: 7
d: None

>>> variadic()
Positional: ()
Keyword: {}

>>> print_variadic()
Positional: (2, 3, 5, 7)
Keyword: {}
Positional: (1, 1)
Keyword: {'n': 1}
Positional: ()
Keyword: {}
Positional: ()
Keyword: {'cs': 'Computer Science', 'pd': 'Product Design'}
Positional: (5, 8)
Keyword: {'k': 1, 'swap': 2}
Positional: (8, 3, 4, 5)
Keyword: {'k': 1, 'a': 5, 'b': 'x'}
Positional: (8, 3, 4, 5)
Keyword: {'k': 1, 'a': 5, 'b': 'x'}
Positional: (3, 4, 5, 8, 4, 1)
Keyword: {'k': 1, 'a': 5, 'b': 'x'}
Positional: ({'a': 5, 'b': 'x'}, 'a', 'b')
Keyword: {'a': 5, 'b': 'x'}

>>> all_together(x=1,y=2)
x: 1
y: 2
z: 1
nums: ()
indent: True
spaces: 4
options: {}

>>> print_all_together()
x: 2
y: 5
z: 7
nums: (8,)
indent: False
spaces: 4
options: {}
x: 2
y: 5
z: 7
nums: (6,)
indent: None
spaces: 4
options: {}
x: {'x': 0, 'y': 1}
y: 0
z: 1
nums: (2, 3, 4, 5, 6, 7, 8, 9)
indent: True
spaces: 4
options: {}
x: [1, 2]
y: {3: 4}
z: 1
nums: ()
indent: True
spaces: 4
options: {}
x: 8
y: 9
z: 10
nums: (2, 4, 6)
indent: True
spaces: 0
options: {'a': [4, 5], 'b': 'x'}
x: 8
y: 9
z: 2
nums: (4, 6, 'z')
indent: True
spaces: 0
options: {'a': [4, 5], 'b': 'x'}

>>> speak_excitedly("Przykładowy tekst")
'Przykładowy tekst!'

>>> average(1,2,3,4,5)
3.0

>>> test_make_table()
=========================
| first_name  |     Sam |
| last_name   | Redmond |
| shirt_color |    pink |
=========================
==================================
|            song |    Style     |
| artist_fullname | Taylor $wift |
|           album |     1989     |
==================================

##LAB4.py

>>> test_lambda()
25
24
py

>>> test_map()
[22, 51966, 42]
[12, -2, 0]
[5, 5]
['olleh', 'dlrow']
[(2, 4, 8), (3, 9, 27), (4, 16, 64), (5, 25, 125)]
[6, 15, 28]

>>> test_filter()
['12', '0']
['world']
['Stanford']
[0, 3, 5, 6, 9, 10, 12, 15, 18]

>>> gcd(84,16)
4

>>> lcm(4,7,3)
84.0

>>> fact(5)
120

>>> test_operator()
3
30
8
2

>>> test_ord()
apple
['cabbage', 'apple', 'pear', 'bananas']
cabbage
bananas

>>> alpha_score("ABC")
6

>>> two_best(["slowo","wyraz","wyrazenie"])
['slowo', 'wyraz']

>>> test_two_best()
['PyThOn', 'wOrLD']

>>> float_Control(1)
'Winner'
>>> float_Control(-1)
'Loser'
>>> float_Control(5)
'Tied'

>>> iterator_Consumption()
True
68
Traceback (most recent call last):
  File "<pyshell#15>", line 1, in <module>
    iterator_Consumption()
  File "C:/Python zadania/lab4.py", line 88, in iterator_Consumption
    (next(it))  # => StopIteration
StopIteration

>>> test_itertools()
('X', 'K'), ('X', 'C'), ('X', 'D'), ('K', 'X'), ('K', 'C'), ('K', 'D'), ('C', 'X'), ('C', 'K'), ('C', 'D'), ('D', 'X'), ('D', 'K'), ('D', 'C'), LOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLOLTraceback (most recent call last):
  File "<pyshell#8>", line 1, in <module>
    test_itertools()
  File "C:/Python zadania/lab4.py", line 96, in test_itertools
    print(el, end='')  # Don't run this one. Why not?
KeyboardInterrupt

>>> dot_product([1, 3, 5], [2, 4, 6])
44

>>> test_transpose()
((1, 5, 9), (2, 6, 10), (3, 7, 11), (4, 8, 12))

>>> generate_triangles()
<generator object generate_triangles at 0x0000000003153308>

>>> primes_under(1000)
<generator object primes_under at 0x00000000030D3308>

<function outer.<locals>.inner at 0x00000000032C52F0>
<function outer.<locals>.inner at 0x00000000032C5378>
>>> outer()>>> generate_triangles()
<generator object generate_triangles at 0x0000000003153308>
>>>
===================== RESTART: C:/Python zadania/lab4.py =====================
>>> primes_under(1000)
<generator object primes_under at 0x00000000030D3308>

>>> test_make_adder()
<function make_adder.<locals>.add_n at 0x0000000003144378>
<function make_adder.<locals>.add_n at 0x0000000003144400>

>>> foo()>>> test_make_adder()
<function make_adder.<locals>.add_n at 0x0000000003144378>
<function make_adder.<locals>.add_n at 0x0000000003144400>

>>> test_outer()
[1, 2, 3, 1, 2, 3, 1, 2, 3]
[1, 2, 3, 4, 1, 2, 3, 4, 1, 2, 3, 4]

>>> print_args(outer(1))
<function print_args.<locals>.wrapper at 0x00000000030D99D8>

##LAB5.py

>>> from lab5 import Course
>>> stanford_python = Course("CS","41","hap.py code: The python programming language")

>>> stanford_python.title
'hap.py coder: the python programming language'
>>> stanford_python.number
41
>>>
>>> from lab5 import Course, CSCourse
>>> a = Course("CS", "106A", "Programming Methodology")
>>> b = CSCourse("CS", "106B", "Programming Abstractions")
>>> type(a)
<class 'lab5.Course'>
>>> isinstance(a,Course)
True
>>> isinstance(b,Course)
True
>>> type(a) == type(b)
False
>>> a ==b
False

>>> cs106a = Course("CS", "106A", "Programming Methodology")
>>> cs106b = CSCourse("CS", "106B", "Programming Abstractions")
>>> cs107 = CSCourse("CS", "107", "Computer Organzation and Systems")
>>> cs110 = CSCourse("CS", "110", "Principles of Computer Systems")
>>> cs110 > cs106b
True
>>> cs107 > cs110
False
