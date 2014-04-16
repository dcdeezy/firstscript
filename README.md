firstscript
===========

First Script: Pyg Latin Translator

print "Welcome to the Pyg Latin Translator!"

pyg = 'ay'

original = raw_input('Enter a word:')

if len(original) > 0 and original.isalpha():
    word = original.lower()
    first = word [0]
    new_word = word + first + pyg
    print new_word [1:len(new_word)]

elif not original.isalpha():
    print "Please only enter letters."
    
else:
    print "You've entered no value."
