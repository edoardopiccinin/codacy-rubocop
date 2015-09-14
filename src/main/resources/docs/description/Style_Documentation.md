You should have top-level documentation of classes and modules. Classes with no body are exempt from the check and so are namespace modules - modules that have nothing in their bodies except classes or other modules.

The documentation requirement is annulled if the class or module has a "#:nodoc:" comment next to it. Likewise, "#:nodoc: all" does the same for all its children.

[Source](http://www.rubydoc.info/gems/rubocop/RuboCop/Cop/Style/Documentation)