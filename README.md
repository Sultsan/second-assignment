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
             z=`expr $x \* 10`
              c=`expr $z / 100`
              r=`expr $num - $c`
              echo " $r "
        else
              echo "No tax" 
        fi




4- 


       #!/bin/bash
       echo "Enter your number:"
       read n
       echo "Enter the power:"
       read num
       v=$n
       x=$num
       result=1
       while [ $x -gt 0 ]
       do
          result=`expr $v \* $result`
          x=`expr $x - 1`
       done
       echo "result =  $result" 
       
       
       
       
  5-
  
     5-

      #!/bin/bash
      echo "enter  your number:"
      read num
      x=$num
      temp=`expr $x % 2`
      if [ $x -eq 2 ]
      then 
            echo " $x is a primer number  "
      elif [ $temp -eq 0 ]
      then

            echo " $x is not a primer number  "

      else
            echo " $x is  a primer number  "
      fi 
 6- 
 
 
         #!/bin/bash
       
        read num
        if [ $num -lt 0 ]
        then 
              echo "Enter a positive integer"
              read num
        else 
              continue
        fi       
        sum=0
        number=0
        average=0
        while [  $num != 0 ]; 
        do              

         sum=`expr $num + $sum`
         number=`expr $number + 1`
         echo "Please Enter a number or 0 To exit :" | tr "\n" " " 
         read num
        if [ $num -lt 0 ]
        then 
              echo "Enter a positive integer "
              read num
        else 
              continue
        fi       
        done

        average=`expr $sum / $number` 

        echo "The average  : $average "

7-
            #!/bin/bash
            echo "Enter a number"
            read nu
            x=0
            re=0
            sum=0
            num=0
            while [ $num -gt 0 ]
            do
                x=$(( $n % 10 ))
                re=$(( $re *\ 10 + $x ))
                num=$(( $n / 10 ))
                sum=$(($sum + $d))
                num=$(($num + 1))
            done
            ave=$(( $sum / $num ))
            echo "Reverse number of entered digit is $re"
            echo " of the digits $sum"
            echo "average of the digits $ave"











  
