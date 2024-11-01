Function is a specific block of code you can call it when ever we want without repeating teh instructions.

* Syntax

There are 2 ways of writing Functions in bash

**Type-1**

  ```
#!/bin/bash

function  Movie_Name {

echo "$1 $2 are my favourite movies" // -> Prints 1st and 2nd Arguments

echo $@ // ->  Prints the Total Arguments Passed (O/P=KGF Salaar Bhagera)

echo $#  // -> Prints the total number of arguments (O/P=3)

}
 Movie_Name "KGF" "Salaar" "Bhagera" // Way of passing parameters
    
  ```

**Type-2**

```
#!/bin/bash

Movie_Name(){

echo "Same as above $1"

}

Movie_Name "KGF"
```


