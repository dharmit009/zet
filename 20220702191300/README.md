# What is Liner Time or O(n)?

When number of inputs is equal to number of operations
the algorithm is said to be linear or O(n).

**Hint:** No. Of Operations == No. Of Elements.

**Code Snippet:**

``` Golang
package main

import "fmt"

func main() {
	var a = []string{"lookup", "nemo", "testing"}
	for i := 0; i < len(a); i++ {
		if a[i] == "nemo" {
			fmt.Printf("Found Nemo @ %d\n", i)
		}
	}
}

```
