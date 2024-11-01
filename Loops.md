When we want to repeat the block of code for many times we use loops

In bash there are 3 loops 

* For-Loop
* While Loop
* Until Loop


## For-Loop

**Traditional-Way**

* Syntax

```
#!/bin/bash

for (( i=0;i<10;++i )) 
do

if (( i%2 == 0 ))
echo $i

<< Arithmetic Operations // Like this we have to comment the part of code

let i=i+1;

(( i++ )) 

i= $(( i+1 ))
 
Arithmetic Operations //Same text has to be written

// All three are used to increment i by 1 .

done

```
  
