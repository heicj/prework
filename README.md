# prework

codecademy Unit 3: PygLatin - part 10
'''python
pyg = 'ay'

original = raw_input('Enter a word:')


if len(original) > 0 and original.isalpha():
  word = original.lower()
  first = original[0]
  new_word = word + first + pyg
  new_word = new_word[1:len(new_word)]
  print original
else:
  print 'empty'
'''
