# python_interview_preparation
One great thing about interviews is that you get to know what you don't know, luckily I had a lot of interviews (and I know how it feel when you want a job but they ask you a question, you don't know the answer, and I you end up feeling like that is something you should of know)


## Theorical Questions Section

### Theorical Question 1

Do you understand why we put this line at the beggining of python files ?

#!/usr/local/bin/python

<details><summary><b>Answer</b></summary>

![Image](img/shebang.png "shebang")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 59
</details>

### Theorical Question 2

Do you understand what the dir() function is for ?

<details><summary><b>Answer</b></summary>

![Image](img/dirFunction.png "dirFunction")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 104
</details>

### Theorical Question 3

Do you know what the pdb library is for ?

<details><summary><b>Answer</b></summary>

debugging

</details>

<details><summary><b>Source</b></summary>

here is the [link](https://docs.python.org/3/library/pdb.html).

</details>

### Theorical Question 4

Do you know what is ASCII text, how unicode help us represent it correctly and how to use unicode in python ?

<details><summary><b>Answer</b></summary>

![Image](img/unicodeSupport.png "unicodeSupport")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 106
</details>

### Theorical Question 5

Do you know how to use regular expressions in python ?

<details><summary><b>Answer</b></summary>

![Image](img/regex.png "regex")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 106
</details>

### Theorical Question 6

Do you know what tuples are and when do we use them ?

<details><summary><b>Answer</b></summary>

![Image](img/tuples_1.png "tuples 1")

![Image](img/tuples_2.png "tuples 2")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 106
</details>

### Theorical Question 7

Do you understand why we add the parameted "encoding utd_8" when we open a file ?

<details><summary><b>Answer</b></summary>

![Image](img/openEncodedFile.png "openEncodedFile")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 106
</details>


### Theorical Question 8

Do you understand what __init__ and self mean ?

<details><summary><b>Answer</b></summary>

![Image](img/initSelf.png "init self")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 106
</details>

### Theorical Question 9

Do you understand the difference between "==" and "is" ?

<details><summary><b>Answer</b></summary>

![Image](img/identityEquality.png "identity Equality")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 186
</details>

### Theorical Question 10

Do you know what would happen if you don't close a python file?

![Image](img/notClosingFile.png "notClosingFile")

<details><summary><b>Answer</b></summary>

Calling the file close method terminates your connection to the external file, re-
leases its system resources, and flushes its buffered output to disk if any is still in
memory. As discussed in Chapter 6, in Python an object’s memory space is auto-
matically reclaimed as soon as the object is no longer referenced anywhere in the
program.

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 290
</details>

### Theorical Question 11

Do you know what we use pickle for?

<details><summary><b>Answer</b></summary>

![Image](img/picleForSerialization.png "picleForSerialization")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 290
</details>

### Theorical Question 12

Do you understand the difference between generators and functions?

<details><summary><b>Answer</b></summary>

return sends a result object back to the caller. When a function is called, the
caller stops until the function finishes its work and returns control to the caller.
Functions that compute a value send it back to the caller with a return statement;
the returned value becomes the result of the function call. A return without a value
simply returns to the caller (and sends back None , the default result).

yield sends a result object back to the caller, but remembers where it left
off. Special word "yield" create a generator. Functions known as generators may also use the yield statement to send back

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 475
</details>

### Theorical Question 13

Do you know the argument matching syntax?

<details><summary><b>Answer</b></summary>

![Image](img/argumentMatchingSyntax.png "argument Matching Syntax")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 530
</details>

### Theorical Question 14

When you are importing a module in python do you know where does it look for it ?

<details><summary><b>Answer</b></summary>

![Image](img/importingModules.png "importin gModules")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 638
</details>

### Theorical Question 15

Do you understand what these lines are for in a python program ?

![Image](img/name_main.png "name_main")

<details><summary><b>Answer</b></summary>

![Image](img/name_main_answer.png "name main answer")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 638
</details>

### Theorical Question 16

I imagine you know how to sum two numbers in python or how to organiza number or words in a python list, but do you know how to change the behaviour when you sum two objects in python or how to change the way how objects are sorted in a python list ?

<details><summary><b>Answer</b></summary>

you would need to change special method __add__ to change the way how two objects are added up, and to change the way how objects are sorted we need to change the special methods __lt__ and __gt__ 

![Image](img/interceptingOperators.png "intercepting Operators")

![Image](img/interceptingOperatorsPart2.png "intercepting Operators Part 2")

![Image](img/interceptingOperatorsPart3.png "intercepting Operators Part 3")

![Image](img/specialMethodSorting.png "special Method Sorting")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 805

https://stackoverflow.com/questions/48313301/python-sort-has-higher-priority-for-lt-than-gt
</details>

### Theorical Question 17

Do you know what specal methods could you use to change objects behaviours ?

<details><summary><b>Answer</b></summary>

![Image](img/overloadingMethods.png "overloading Methods")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 805

https://stackoverflow.com/questions/48313301/python-sort-has-higher-priority-for-lt-than-gt
</details>


### Theorical Question 18

Do you understand what abstractMethod are for in python  ?

<details><summary><b>Answer</b></summary>

![Image](img/abstractMethods.png "abstract Methods")

![Image](img/abstractMethodsPart2.png "abstract Methods Part 2")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 870
</details>

### Theorical Question 19

Do you know what the special methods __iter__ and __next__ are for ?

<details><summary><b>Answer</b></summary>

![Image](img/iterNext.png "iter and next")

![Image](img/iterNextPart2.png "iter and next par2")

![Image](img/iterNextPart3.png "iter and next par3")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 895
</details>

### Theorical Question 20

Do you know what the special method __call__ ?

<details><summary><b>Answer</b></summary>

![Image](img/callMethod.png "call method")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 922
</details>

### Theorical Question 21

How do you create a private variable in python ?

<details><summary><b>Answer</b></summary>

![Image](img/pythonPrivateVar.png "python Private Var")

![Image](img/pythonPrivateVarPart2.png "python Private Var Part2")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 945
</details>

### Theorical Question 22

Do you understand what static and class methods are ?

<details><summary><b>Answer</b></summary>

![Image](img/staticClassMethods.png "static Class Methods")

![Image](img/staticClassMethodsPart2.png "static Class Methods Part2")

![Image](img/staticClassMethodsPart3.png "static Class Methods Part3")

![Image](img/staticClassMethodsPart4.png "static Class Methods Part4")

![Image](img/staticClassMethodsPart5.png "static Class Methods Part5")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 945
</details>

### Theorical Question 23

Do you understand what decorators are ?

<details><summary><b>Answer</b></summary>

![Image](img/decorators.png "decorators")

![Image](img/decoratorsP2.png "decorators")

![Image](img/decoratorsP3.png "decorators")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 1035
</details>

### Theorical Question 24

Do you understand what exceptions are ?

<details><summary><b>Answer</b></summary>

![Image](img/exceptions.png "exceptions")

![Image](img/exceptionsP2.png "exceptions Part2")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 1081
</details>

### Theorical Question 25

Do you understand what managed attributes and properties are ?

<details><summary><b>Answer</b></summary>

![Image](img/managedAttibues.png "managed Attibues")

![Image](img/managedAttibuesP2.png "managed Attibues Part2")

![Image](img/properties.png "properties")

![Image](img/propertiesP2.png "properties")

![Image](img/propertiesP3.png "properties")

</details>

<details><summary><b>Source</b></summary>
learning python 5th edition - pag 1081
</details>

### Theorical Question 26

Do you know what corutines are ?

<details><summary><b>Answer</b></summary>

![Image](img/corutines.png "corutines")

![Image](img/corutinesPart2.png "corutines part 2")

![Image](img/corutinesPart3.png "corutines part 3")

![Image](img/corutinesPart4.png "corutines part 4")

![Image](img/corutinesPart5.png "corutines part 5")

![Image](img/corutinesPart6.png "corutines part 6")

![Image](img/corutinesPart7.png "corutines part 7")

![Image](img/corutinesPart8.png "corutines part 8")

![Image](img/corutinesPart9.png "corutines part 9")

![Image](img/corutinesPart10.png "corutines part 10")

![Image](img/corutinesPart11.png "corutines part 11")

![Image](img/corutinesPart12.png "corutines part 12")

![Image](img/corutinesPart13.png "corutines part 13")

![Image](img/corutinesPart14.png "corutines part 14")
</details>

<details><summary><b>Source</b></summary>
fluent python - pag 468
</details>

### Theorical Question 27

Do you know what futures are and what concurrency is ?

<details><summary><b>Answer</b></summary>

![Image](img/futures.png "futures")

![Image](img/futuresPart2.png "futures part 2")

![Image](img/futuresPart3.png "futures part 3")

![Image](img/futuresPart4.png "futures part 4")

![Image](img/futuresPart5.png "futures part 5")

![Image](img/futuresPart6.png "futures part 6")

![Image](img/futuresPart7.png "futures part 7")

![Image](img/futuresPart8.png "futures part 8")

![Image](img/futuresPart9.png "futures part 9")

![Image](img/futuresPart10.png "futures part 10")

![Image](img/futuresPart11.png "futures part 11")

![Image](img/futuresPart12.png "futures part 12")

![Image](img/futuresPart13.png "futures part 13")
</details>

<details><summary><b>Source</b></summary>
fluent python - pag 505
</details>


### Theorical Question 28

Do you know what the GIL is ?

<details><summary><b>Answer</b></summary>

![Image](img/GIL.png "GIL")

![Image](img/GIL_part2.png "GIL part 2")

![Image](img/GIL_part3.png "GIL part 3")

![Image](img/GIL_part4.png "GIL part 4")

![Image](img/GIL_part5.png "GIL part 5")

![Image](img/GIL_part6.png "GIL part 6")

![Image](img/GIL_part7.png "GIL part 7")

![Image](img/GIL_part8.png "GIL part 8")

![Image](img/GIL_part9.png "GIL part 9")

![Image](img/GIL_part10.png "GIL part 10")

![Image](img/GIL_part11.png "GIL part 11")

![Image](img/GIL_part12.png "GIL part 12")

![Image](img/GIL_part13.png "GIL part 13")

![Image](img/GIL_part14.png "GIL part 14")

![Image](img/GIL_part15.png "GIL part 15")

![Image](img/GIL_part16.png "GIL part 16")

![Image](img/GIL_part17.png "GIL part 17")

![Image](img/GIL_part18.png "GIL part 18")
</details>

<details><summary><b>Source</b></summary>
fluent python - pag 505
</details>

### Theorical Question 29

Do you know what the asyncio python library is ?

<details><summary><b>Answer</b></summary>

![Image](img/asyncio.png "asyncio")

![Image](img/asyncioPart2.png "asyncio part 2")

![Image](img/asyncioPart3.png "asyncio part 3")

![Image](img/asyncioPart4.png "asyncio part 4")

![Image](img/asyncioPart5.png "asyncio part 5")

![Image](img/asyncioPart6.png "asyncio part 6")

![Image](img/asyncioPart7.png "asyncio part 7")

![Image](img/asyncioPart8.png "asyncio part 8")

![Image](img/asyncioPart9.png "asyncio part 9")

![Image](img/asyncioPart10.png "asyncio part 10")

![Image](img/asyncioPart11.png "asyncio part 11")

![Image](img/asyncioPart12.png "asyncio part 12")

![Image](img/asyncioPart13.png "asyncio part 13")

![Image](img/asyncioPart14.png "asyncio part 14")

![Image](img/asyncioPart15.png "asyncio part 15")

![Image](img/asyncioPart16.png "asyncio part 16")

![Image](img/asyncioPart17.png "asyncio part 17")

![Image](img/asyncioPart18.png "asyncio part 18")

![Image](img/asyncioPart19.png "asyncio part 19")

![Image](img/asyncioPart20.png "asyncio part 20")

![Image](img/asyncioPart21.png "asyncio part 21")

![Image](img/asyncioPart22.png "asyncio part 22")

![Image](img/asyncioPart23.png "asyncio part 23")

![Image](img/asyncioPart24.png "asyncio part 24")

![Image](img/asyncioPart25.png "asyncio part 25")

![Image](img/asyncioPart26.png "asyncio part 26")

![Image](img/asyncioPart27.png "asyncio part 27")

![Image](img/asyncioPart28.png "asyncio part 28")

![Image](img/asyncioPart29.png "asyncio part 29")

![Image](img/asyncioPart30.png "asyncio part 30")

![Image](img/asyncioPart31.png "asyncio part 31")

![Image](img/asyncioPart32.png "asyncio part 32")

![Image](img/asyncioPart33.png "asyncio part 33")

![Image](img/asyncioPart34.png "asyncio part 34")

![Image](img/asyncioPart35.png "asyncio part 35")

![Image](img/asyncioPart36.png "asyncio part 36")

![Image](img/asyncioPart37.png "asyncio part 37")

![Image](img/asyncioPart38.png "asyncio part 38")

![Image](img/asyncioPart39.png "asyncio part 39")

![Image](img/asyncioPart40.png "asyncio part 40")

![Image](img/asyncioPart41.png "asyncio part 41")

![Image](img/asyncioPart42.png "asyncio part 42")

![Image](img/asyncioPart43.png "asyncio part 43")

![Image](img/asyncioPart44.png "asyncio part 44")

![Image](img/asyncioPart45.png "asyncio part 45")

![Image](img/asyncioPart46.png "asyncio part 46")

![Image](img/asyncioPart47.png "asyncio part 47")

![Image](img/asyncioPart48.png "asyncio part 48")

![Image](img/asyncioPart49.png "asyncio part 49")

![Image](img/asyncioPart50.png "asyncio part 50")

![Image](img/asyncioPart51.png "asyncio part 51")

![Image](img/asyncioPart52.png "asyncio part 52")
</details>

<details><summary><b>Source</b></summary>
fluent python - pag 538
</details>

### Theorical Question 30

Do you know the difference between \__new__ and \__init__  ?

<details><summary><b>Answer</b></summary>

![Image](img/difference_init_new.png "difference init new")

</details>

<details><summary><b>Source</b></summary>

https://santoshk.dev/posts/2022/__init__-vs-__new__-and-when-to-use-them/#:~:text=__new__%20returns%20a,returned%20by%20__new__%20.

</details>