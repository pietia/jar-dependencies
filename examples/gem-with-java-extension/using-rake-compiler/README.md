# using rake and ruby-maven gem

## build compile and create jar

```
rake jar
```

## pack gem

```
rake package
```

## just run the code

make sure you use jruby (via rbenv, rvm, etc)
```
ruby -Ilib -e "require 'mygem'"
```