# second-assignment 


 
        #!/bin/bash
        echo "Enter any number"
        read num
        x=$(( $n / 3600 ))
        y=$(( $n % 3600))
        z=$(( $b / 60 ))
        c=$(( $b % 60 ))
        echo "$x "
        echo "$y "
        echo "$z "

        echo " $x : $y : $z " 
        
2- 



        #!/bin/sh

        echo " Please Enter a temperature in degrees Celsius: "
        read d
        num=`expr $d \* 5`
        num3=`expr $num / 9`
        num2=`expr $num3 + 32` 
        echo "$num2"
        
        

3-
            #!/bin/bash
            echo "enter  The salary:"
           read num
           x=$num

        if [ $x -gt 2000 ]
        then
              y=`expr $x \* 15`
              s=`expr $y / 100`
              r=`expr $num - $s`
              echo " $r "
        elif [ $x -lt 2000 -a $x -gt 1000 ]
        then 
              c=`expr $x \* 10`
              p=`expr $c / 100`
              r=`expr $num - $p`
              echo " $r "
        else
              echo "No tax" 
        fi
