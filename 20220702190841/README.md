# Time Module in Go.

We use the `time` module to measure time in Go.
Here is quick example of how to use it:

```golang
package main

import (
	"fmt"
	"time"
)

func main() {

    // Starts the timer
	var start = time.Now()

	var a = []string{1, 2, 3, 4}

    // Calculates the time Since the timer started
	var end = time.Since(start)

	fmt.Println("Execution Time:", end)
}
 ```
