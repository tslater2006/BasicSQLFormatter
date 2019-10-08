# BasicSQLFormatter
Basic SQL Formatting Library for .NET

This is a simple port of the Hibernate BasicFormatterImpl

[Link to original sources](https://github.com/hibernate/hibernate-orm/blob/881eec83fe8f72ffd495fa460894de30c52b252a/hibernate-core/src/main/java/org/hibernate/engine/jdbc/internal/BasicFormatterImpl.java)

Basic usage

```c#
var formattedText = new SQLFormatter("SELECT * FROM DUAL").Format();
```