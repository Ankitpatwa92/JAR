# JAR
Jar Commands

#### How to see content inside jar
```
jar tf jar-file
```
#### How to extract jar
```
jar xf jar-file
```

#### How to extract jar
```
jar xf jar-file
```


#### How to create jar file
```
jar cvf input-jar-file     //c is to create , V for verbose
```

#### How to run jar file
```
java -jar jar-name
```

#### How to update jar file
```
jar uf jar-file input-file(s)    //u for update content
```
#### Disabling jar compression
```
jar cfv0 jar-file input-file(s)
```

####  Include manifest file in jar file

create manifest file for example MANIFEST.txt with following content
```
Main-Class: MyPackage
```

Warning: The text file must end with a new line or carriage return. The last line will not be parsed properly if it does not end with a new line or carriage return.

```
jar cvfm  jar-file MANIFEST.txt org
```

