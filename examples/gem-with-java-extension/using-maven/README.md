# using maven-3.3.x to build jar and pack gem

the ruby DSL for maven is configured by .mvn/extensions.xml

## build compile and create jar

```
mvn prepare-package
```

## pack gem

```
mvn package
```

## deploy gem tio rubygems.prg

```
mvn push
```