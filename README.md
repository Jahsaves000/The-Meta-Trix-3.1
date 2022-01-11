# The-Meta-Trix-3.1

a continuation of cs50 lecture 1 "C"

%c = char

%f = floating point value

%i = integer

%s = string

%li = long integer

//new file;

#include <cs50.h>
#include <stdio.h>

    int main(void)

{

    int x = get_int("x: ");
    
    int y = get_int("y: ");
    
    printf("%i\n", x + Y);
}

//new file

#include <stdio.h>
#include <cs50.h>

    int main(void)

{

    long x = get_long("x: ");
    
    long y = get_long("y: ");
    
      printf(%li\n", x + y);
}

//new line

#include <stdio.h>
#include <cs50.h>

    int main(void)

{

    
    int x = get_int("x: ");
  
    int y = get_int("y: ");
 
    float z = (float) x / (float) y;
  
    printf("%f\n", z);
  
 }


//new code


    if (x < y)  

{

    printf("x is less than y\n");
  
 }


    if (x < y)
  
{

    printf("x is less than y\n");
   
}

    else

{

    printf("x is not less than y\n")
    
}


//new code
 
 
    if (x < y)
 
 {
 
    printf(x is less than y);
      
}
 
    else if (x > y)
 
{
 
    printf(x is greater than y);
      
}
 
    else (x == y)
 
 {
 
    printf(x is equal to y)
      
 }
 
 //another format of this ^ code
 
#include <stdio.h>
#include <cs50.h>

    int main(void)

{

    int x = get_int("x: ");

    int y = get_int("y: ");
  
    if (x < y)

{

    printf("x is less than y\n");
  
}
  
    if (x > y)

{

    printf("x is greater than y");
  
}

    If (x == Y)
{

    printf("x is equal to y");
  
}  

//new program

#incude <cs50.h>
#include <stdio.h>

    int main(void)

{

    char c = get_char("Do you agree? ");

     if (c = "y")
  
  {
  
    printf("Agreed.\n");
    
  }
  
    else if (c = "n")
  
  {
  
    printf("Not agreed.");
    
  }
 
 }
