# Imperative Style:

> Note: Most of the example code is in languages like Java, Python, Javascript, Go and Elixir as I know these languages.

<hr>
Definition: In this style `You define how to do something, step by step.`
Like you have been creating an algorithm and you're defining each step how you are implementing each things.

In this style, we often change the value of variables state and the till from start to the end we defines the step and state change.

Example: Like creating a for loop and getting the sum of numbers.

```java
List<Integer> nums = List.of(1,2,3,4);
int sum = 0;
for (Integer num: nums) {
    sum += num;
}
System.out.println("Sum is " + sum);
```