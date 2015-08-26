##Array#join over Array#*

Choose Array#join over Array#* since the * is a more cryptic notation and therefore may affect the readability
of your code

**Example:**

```
#bad
%w(one two three) * ','

#good
%w(one two three).join(',')
```