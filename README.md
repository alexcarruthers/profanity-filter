profanity-filter
================

Python module that replaces inappropriate words with something more PG rated.
Can also check if a string contains swear words 

Usage
-----   
```python
f = Filter(clean_word='unicorn')
safe_string = f.clean('badword and bad words')
print safe_string
f.check('badword and notbadword')
```
