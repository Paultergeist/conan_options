```conan create . test/test -o option1=value2```
Prints this in the log:
```
[options]
option1=value2
...
...
conan-options/1.0@test/test: Calling build()
conan-options/1.0@test/test: self.options.option1=value1
```
