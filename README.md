### Hello there 👋

#### A Backend-Focused Full Stack Developer. Who's Always Learning and Growing.

Passionate Full-Stack in the **TypeScript** and **Golang** ecosystem.
Focused on building scalable, modern web applications with clean architecture and ensuring high-quality, reliable software through robust testing practices.

 <!-- ### Connect With Me
-  [Stack Overflow](https://stackoverflow.com/users/19853138/fdhliakbar)  
-  [HackerRank](https://www.hackerrank.com/profile/fadhliakbar125)  
-  [Codechef](https://instagram.com/fdhliakbar)  
-  [LeetCode]() -->

```go
package main
import "fmt"

func main() {
    myself := map[string]interface{}{
        "name":     "Fadhli Akbar",
        "nickname": "fdhliakbar",
        "pronouns": "He/Him",
        "skills":   []string{"TypeScript", "Golang", "C++", "Docker", "PostgreSQL"},
        "role":     "Software Developer",
    }

    sayHello := func() string {
        return fmt.Sprintf("Hello, my name is %s. You can call me %s", myself["name"], myself["nickname"])
    }
    fmt.Println(sayHello())
}
```