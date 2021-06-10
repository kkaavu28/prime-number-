# prime-number-
Program to print prime numbers 
Lower = int ( input ( " Enter Lower range " ))
Upper = int ( input ( " Enter Upper range " ))
print ("Prime numbers between" ,Lower, "and", Upper, "are:" )
for num in range (lower , upper+1):
    if num > 1 :
        for i in range (2,num):
             if ( num % i ) == 0 :
                  break
        else :
             print ( num )
