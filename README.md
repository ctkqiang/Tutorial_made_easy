# Anatomy of [Golang] Made Simple
### By John Melody
---

1. Hello World Programme:</br>
    ```golang
    package main  // the name of the package as "Java-like"
    
    import "fmt" // the Module used import like Python

    func main() {  // Main function as in C/C++
    	fmt.Println("Hello, World") // Prints String , no semi colon required
    }

    // output :

    // Hello, World
    // Program exited.
    ```

2. Variable: </br>
    a. Specific:
    > var 'name' 'type' = 'value' 
    ```golang
    func main() {
	    var i int = 12
        fmt.Println(i)
    }
    ```

    b. Automatic:
    > 'name' := 'value'
    ```golang
    func main() {
        i := 12
        fmt.Println(i)
    }
    ```

    Both of Specific declared and Automatically declared variable gave the same output value of ```i``` which equals to ```12```.


3. Printing: </br>
    The most Common printing in Golang will be  ```%v, %T, %t, %s``` which stands for ```value, boolean, type, string```. As sample programme below explains:
    ```golang
    func main() {
	    x := 12
	    y := "Hello"
	    z := false
    fmt.Printf("%v, %T, %t", x, y, z)
    
    // output:
    // 12, string, false
    // Program exited.
    }
    ```