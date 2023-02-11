# This is an `<h1>` header, which is the largest

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

```go
package main

import "fmt"

func normalFunction(message string) { 
  fmt.Println(message)
}

func tripeArgument(a, b int, c string) {
fmt.Println(a, b, c)
}  
func returnValue(a int) int {
return a * 2 
} 
func doubleReturn(a int) (c,d int) {
return a, a * 2 
} 
func main() { 

normalFunction("Hola mundo")
tripeArgument(1, 2, "hola")

value := returnValue(2)
fmt.Println("Value:", value)

value1, _ := doubleReturn(2)
fmt.Println("value1", value1)
}
```

- [x] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world

