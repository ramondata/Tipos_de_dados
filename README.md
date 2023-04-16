![type_data]()
Data types in Python language 🐍
======================

In Python there is some types usually used for the community.

- int
- str
- float
- bool
- chr

When we use data, is necessary save this in some place. One way to save data is inside memory RAM.
For do it, we need build a way to access that data. In this case, we create a variable wich work like a reference.

Look this example:
>>> name = "Chico"

The word name is a reference to access data, it`s a variable.
The string "Chico" is a data. An information saved in memory.

Example above, the data type is string ou str. In Python we do not need pass the data type for variables, but we can do it if necessary.

Look this example:
>>> name: str = "Ramon"

It`s like reference, then a data type, then data.

Each data there`s a number of identification. For see this identification, we use the built-in function id().

Look this example:
>>> count_cars_in_garage: int = 3

>>> id(count_cars_in_garage)

>>> output -> 1230947755 -> sequence of 10 numbers

Let`s follow some examples of variables
>>> count_books_on_table = 45

>>> more_than_one_object = True

>>> full_name = "Ramon Barbosa"

>>> is_greater_than = 30 >= 20

>>> price = 444.89

We can just cast a variable with some data type to another data type. Follow the examples below:

>>> my_age = '30'

>>> my_age_cast = int(my_age)

>>> size = '1.745'

>>> size_cast = float(size)

An important point about create a variable is the format the name of it.
There`s some kind of cases to do it; 

- camel case
- snake case
- pascal case
- kebab case

[x] Camel Case:
The words stay together and the first character of each word is upper case, except the first word in variable.

Example:

>>> macBookIsVeryBeauty = 'some text'

>>> myWifeIsVeryHungry = False

[x] Snake case:
The words are separeted with underline, everything with upper case or everything with lower case

Example:

>>> some_words_here = 1

>>> SNAKE_CASE_I_USE_OFTEN = 2

[x] Pascal Case:
The words stay together and the first character of each word is upper case, included the first word.

Example:

>>> FirstWordUpperTo = 'sun is beautifull'

>>> TheHelloWorldHere = 'Hello World'

[x] Kebab Case
Worlds with delimiter dash and everything with upper case or everything with lower case.

>>> THE-WORLD = 10

>>>  kebab-is-nice = 'good'
