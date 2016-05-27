1. To get all divisors of a number

   var number = 120;
   for(var i = 2; i <= number/2 ; i++){
     if(number % i == 0){
       console.log(i + " is a divisor of " + number);
     }
   }
