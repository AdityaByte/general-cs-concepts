# Functional Style

> Definition: In this style `Computation is done by functions, often pure functions, and output depends only on input`.

### Things that exists in the functional style.

1. Immutability
2. In pure functional languages every statement returns something.
3. There is no concepts of loops in functional languages.
4. Method chaining exists in the functional style.

```elixir
# In elixir

defmodule TestModule do
    def test do
        sum = [1,2,3,4,5]
            |> Enum.sum()
        IO.puts("Sum is #{sum}")
    end
end
```

