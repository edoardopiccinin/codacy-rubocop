Enforces the removal of unused code inside your methods since they are pointless to maintain

**Example**

```
def something
  x = true
  return x

  #You can remove this since it is unreachable
  if x == true
    puts 'Hello World'
  end
end

```

[Source](http://www.rubydoc.info/gems/rubocop/RuboCop/Cop/Lint/UnreachableCode)