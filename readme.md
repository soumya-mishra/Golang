## GO
- statically types
- compiled language , Fast compilation 
- memory safety
- grabage collection
- structural typing
- concurrency - builtin 
- variable initialization - x:= 0  or var x = 0

package main

  import (
    "fmt"
    "time"
    )
    
 func manin(){
 
    fmt.Println("1st prog")
  
    fmt.Println("time is time.now())
  
 }

import package "fmt" "math" 

func main(){

    fmt.Println(math.Pi)
    
}
   
- function as func 

package main

import "fmt"

func add(x int, y int) int {
	return x + y
}

func main() {
	fmt.Println(add(42, 13))
}


- x,y int  also possible in func 
- multiple return 
  package main
  import "fmt"
  
  func swap(x,y string) (string,string){
      return y, x
  }
  
  func main() {
  a,b:= swap("hello" ,"world")
  fmt.Println(a, b)
  

- Named return values
  
  package main

import "fmt"

func split(sum int) (x, y int) {
	x = sum * 4 / 9
	y = sum - x
	return
}

func main() {
	fmt.Println(split(17))
}

- variable declaration 
  var c, python, java bool
  
- variable with initializer 
  var i, j int = 1, 2
  
 - var c, python, java = true, false, "no!" 
  
