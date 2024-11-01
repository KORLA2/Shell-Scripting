## If-Else

If else are the conditional statements bash also has if else .

* Syntax

  ```
  #!/bin/bash
Movie="KGF"
  
  if (( Movie=="KGF"))  // (()) is used only for string comparision > < symbols can be used here and variable Movie can be accessed without $ .
  then
  echo "$Movie: Voilence Voilence Voilence I dont like it.."

  else if [[ $Movie -eq "KGF" ]]  // [[]]  is preffered for number comparision both (()),[[]] will work fine have to use -eq instead of ==.
  then
  echo "I avoid but Voilence like me"
  
  else 
  echo "I cant avoid"
  
  fi
  
  ```


![image](https://github.com/user-attachments/assets/ae487784-858d-4492-9125-8c0da9cc2713)




