##Useless Access Modifier

Checks for useless access modifiers without any code since they are redundant

**Example:**

```
class Foo
  private #this is not being used remove it

  def self.some_method
  end
end
```