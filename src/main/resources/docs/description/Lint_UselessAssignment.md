Checks for useless assignments to local variable in every scope

**Example:**

```
def something
  sum = 4 + 5 #you don't need the variable therefore useless assignment
end
```

[Source](http://www.rubydoc.info/gems/rubocop/RuboCop/Cop/Lint/UselessAssignment)