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
