# Declarative Style

> Definition: In this style `You define what to do, not how to do it`.
As we talk about java specific this style was mainly came after Java8 some functions were introduced.

In this we don't care about the inner implementation like how we are doing the things we mainly takes care about the output.

Example: Think of it we have a list of numbers and we have to take the sum of the numbers.

```python
# In python
sum = sum([1,2,3,4,5])
print(sum)
```

```java
# In Java

List<Integer> nums = List.of(1,2,3,4);

int sum = nums
.stream()
.mapToInt(i -> i.intValue())
.sum();

System.out.println("sum is " + sum);
```