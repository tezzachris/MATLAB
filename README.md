## Some Matlab remarks 

1) How to get non-empty elements from an array
2) How to do multiple assignments ex. function "deal" 

   [a,b] = deal(1,2);  
   returns a=1 and b=2  
    
   but,  
   coeff = [1,2];   
   [a,b] = deal(coeff);   
   returns a = [1,2] and b=[1,2]  
   instead of a=1 and b=2  

4) Let A = [1,2;3,4]    
   B = [5;6]    
   then A + B    
   returns [6,7;9,10]    
   However, this operation should not be possible 


