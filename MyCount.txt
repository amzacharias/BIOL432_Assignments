 #!/bin/bash

# This script will output numbers 1-20 and describe whether they are a single 
# or double-digit number. 

# Things I found difficult: syntax.
#  Ex. three spaces for each indent
#  Ex. spaces surrounding "[" of "[ ... ]"

for i in {1..20}
do 
   if [ $i -lt 10 ]
   then 
      echo "$i is a single-digit number."
   else
      echo "$i is a double-digit number."
   fi
done
