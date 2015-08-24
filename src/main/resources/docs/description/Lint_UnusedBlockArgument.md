##Unused Block Argument

Checks for unused arguments inside a code block since they are redundant to have (unused arguments prefixed with '_' will be accepted though)

**Example:**


```
#remove unused variable

do_something do |used, unused, _unused_but_allowed|
  puts used
end
```