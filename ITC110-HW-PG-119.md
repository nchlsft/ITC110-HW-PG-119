# ITC110-HW-PG-119
1. What does the code for an empty dictionary look like? 
emptyDictionary = {} , the two curly brackets with nothing in between them shows that it’s empty. 

2. What does a dictionary value with a key 'foo' and a value 42 look like?
{'foo': 42} 

3. What is the main difference between a dictionary and a list? 
Indexes for dictionaries use a lot different data types and not just integers.  Dictionaries are also unordered.

4. What happens if you try to access spam['foo'] if spam is {'bar': 100}? 
KeyError: ‘foo’

5. If a dictionary is stored in spam, what is the difference between the expressions 'cat' in spam and 'cat' in spam.keys()? 
Nothing, spam.keys() will just check if it is or isn’t a value in the dictionary.

6. If a dictionary is stored in spam, what is the difference between the expressions 'cat' in spam and 'cat' in spam.values()? 
‘cat’ in spam will search for a key called ‘cat’ in the dictionary and ‘cat’ in spam.values() will check for values called ‘cat’ in the dictionary.

7. What is a shortcut for the following code? if 'color' not in spam: spam['color'] = 'black' 
spam.setdefault('color', 'black')

8. What module and function can be used to “pretty print” dictionary values?
pprint.pprint()
