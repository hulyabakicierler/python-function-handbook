# String Methods
## upper()
text = "hello"
text.upper()
# 'HELLO'

## lower()
text = "MERHABA"
text.upper()
# 'merhaba'

## strip()
text = "  hi  "
text.strip()
# 'hi'

## split()
text = "a,b,c"
text.split(",")
# ['a', 'b', 'c']

## replace()
text = "I like PowerBI"
text.replace("PowerBI", "Dataverse")
# 'I like Dataverse'

## Exercise (Step-by-step) (Sentence source: ChatGPT)
# 1) Convert the text to uppercase
text = “This is a simple, friendly collection of Python functions and methods, written as a personal reference with small examples.”
text = text.upper()
print(text)
# THIS IS A SIMPLE, FRIENDLY COLLECTION OF PYTHON FUNCTIONS AND METHODS, WRITTEN AS A PERSONAL REFERENCE WITH SMALL EXAMPLES.
# 2)Replace punctuation with spaces (, and .)
text = text.replace(","," ").replace(".", " ")
print(text)
# THIS IS A SIMPLE  FRIENDLY COLLECTION OF PYTHON FUNCTIONS AND METHODS  WRITTEN AS A PERSONAL REFERENCE WITH SMALL EXAMPLES
# 3) Split the string into a list of words
text = text.split()
print(text)
# ['THIS', 'IS', 'A', 'SIMPLE', 'FRIENDLY', 'COLLECTION', 'OF', 'PYTHON', 'FUNCTIONS', 'AND', 'METHODS', 'WRITTEN', 'AS', 'A', 'PERSONAL', 'REFERENCE', 'WITH', 'SMALL', 'EXAMPLES']

## len()
lst = ["P", "Y", "T", "H", "O", "N"]
len(lst)
print(len (lst))
# ...6
##
lst[5]
print(lst[5]) 
# ...N
##
data_list = lst[0:4]
print(data_list)
# ["P", "Y", "T", "H"]
## pop()
lst.pop(2)
print(lst)
## ['P', 'Y', 'H', 'O', 'N']
## insert()
lst.insert(2, "ROSE")
print(lst)
# ['P', 'Y', 'ROSE', 'T', 'H', 'O', 'N']


## Dictionary Practice (Step-by-step)
# 0) Create the dictionary

people = {
    "Mia": ["USA", 18],
    "Efe": ["Turkey", 12],
    "Sofia": ["Spain", 22],
    "Luca": ["Italy", 25]
}

print(people)
# {'Mia': ['USA', 18], 'Efe': ['Turkey', 12], 'Sofia': ['Spain', 22], 'Luca': ['Italy', 25]}

# 1) Get all keys
people_keys = list(people.keys())
print(people_keys)
# ['Mia', 'Efe', 'Sofia', 'Luca']

# 2) Get all values
people_values = list(people.values())
print(people_values)
# [['USA', 18], ['Turkey', 12], ['Spain', 22], ['Italy', 25]]

# 3) Update Efe’s age from 12 to 13
people["Efe"][1] = 13
print(people["Efe"])
# ['Turkey', 13]

# 4) Add a new person (Zeynep: ["Germany", 24])
people["Zeynep"] = ["Germany", 24]
print(people["Zeynep"])
# ['Germany', 24]

# 5) Delete Sofia
people.pop("Sofia")
print(people)








