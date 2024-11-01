# Switch Case:

**This is useful when we want to chain multiple if else blocks .**

* Syntax
  
```

#!/bin/bash
Movie_Name="KGF"

case $Movie_Name in

 "KGF")  echo "Movie is KGF";;    // ;; -> statement will end here 

 "Salaar") echo "Movie is Salaar";;

 "Bhaggera") echo "Movie is Bhageera";;

 *) echo "None of the above";; // * -> None of the above was a match.
  
  
```
