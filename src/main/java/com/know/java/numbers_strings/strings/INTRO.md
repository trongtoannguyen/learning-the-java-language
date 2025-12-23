# Strings

## Creating Strings

Strings are a sequence of characters, are objects and widely used in Java.
Java provide __String__ class to create and manipulate strings.

You can create a string using a **new** keyword, constructor or a string literal—a series of characters in your code
that is enclosed in double quotes. Java has thirteen constructors that allow you to init a string object's value.

> __Note:__ The **String** class is immutable in Java, so once a string object is created, it can not be changed.
> _String_ class provides some methods for modifying purpose. Since strings are immutable, what these methods really do
> is to create and return a new string that contains the result of operations.

## String Length

Methods used to obtain object information are known as accessor methods. One accessor method used with string to return
the number of characters contained in the string object is `length()`.

## Concatenating Strings

`String` class includes `concat()` method to concatenate two strings, which return a new string object.

```java
s1.concat(s2);
```

Strings are most commonly concanated with `+` operator. You can also concat string with mixed data types. Such a
concatenation can be a mixture of any objects. For each object that is not a String, its `toString()` method is called to
convert it to a String.