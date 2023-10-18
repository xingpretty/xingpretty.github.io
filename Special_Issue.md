Mockito mock method 
```java
- doReturn(target).when(object).someMethod(any(),any())
```
  can't replace by 
```java
  doReturn(target).when(object).someMethod(any(),
  any())
```
which will cause mock entity return null. 
