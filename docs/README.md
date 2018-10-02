# In docs/README.md

This content should be Introduction because of `/book.json`


**Write some codes**

## C++

```cpp
#include <iostream>

int main(){
    for(int i = 0; i < 10; i++){
        std::cout << "hello, world" << std::endl;
    }
    return 0;
}
```



## Ruby

```ruby
10.times{
    puts "hello, world"
}
```

## Python 3

```python
for _ in range(10):
    print("hello, world")
```

## Haskell

```haskell
main = mapM_ putStrLn (replicate 10 "hello, world")
```

## Scala

```scala
object Main extends App{
    for(_ <- 1 to 10){
        println("hello, world")
    }
}
```