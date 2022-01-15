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

//new program 1

#incude <cs50.h>
#include <stdio.h>

    int main(void)

{

    char c = get_char("Do you agree? ");

//|| equals syntaxical "or"

     if (c == 'y' || c == 'Y')
  
  {
  
    printf("Agreed.\n");
    
  }
  
    else if (c == 'n'|| or c == 'N')
  
  {
  
    printf("Not agreed.");
    
  }
 
 }


//new program 2


    while (true)

{

        printf("hello, world\n")
        
}

    int counter = 0;

    int i = 

    while (i < 50)

{

        printf("hello, world\n");
        
        i++; || i-- if we want to count down from 50
}


    for (int i = 0; i < 50; i++)

{

        printf("hello, world\n");
        
}


#include <stdio.h>

    void meow(void);

    int main(void)

{

    for (int = 0; i < 3; i++)
    
    {
    
        meow();
     
    }
        
}

    void meow(void)

{

    printf("meow\n");
    
}


//another variation of this code



#include <stdio.h>

    void meow(void);

    int main(void)

{

    for (int = 0; i < 3; i++)
    
    {
    
        meow(3);
     
    }
        
}

    void meow(int n)

{
    for (int i = 0; i < n; i++)
    
    {

    printf("meow\n");
    
    }
    
}



//new program 3


#include <cs50.h>
#include <stdio.h>


    int get_positive_int(void);
    
    int main(void)
    
 {
 
    int i = get_positive_int();
    
    printf("%i\n", i);
    
 }
 
 
    int get_positive_int(void)
    
 {
 
    int n;
    
    do
    
    {
    
        n = get_int("Positive Integer: ");
        
     }
     
     while (n < 1);
     
     return n;
     
}



//new program 4 (make 4 question marks)


#include <cs50.h>
#include <stdio.h>

    int main(void)

{

    for (int i = 0; i < 4; i++)
    
    {
    
        printf("?");
        
     }
     
     printf("\n");
     
}


//another variation of ^


#include <cs50.h>
#include <stdio.h>

    int main(void)

{

    int n;
    
    do
    
    {
    
    n = get_int(Width: ")
    
    }
    
    while (n < 1);
    
    for (int i = 0; i < n; i++)
    
    {
    
        printf("?");
        
    }
    
    printf("\n");
    
}



//another program 5 (make bricks)


#include <cs50.h>
#include <stdio.h>

    int main(void)

{

    for (int i = 0; i <3; i++)
    
    {
    
        for (int j = 0; j <3; j++)
    
    
            {
            
                printf("#");
             
            }
            
            printf("\n";
    }
    
}


//new code
/* [make mario(2:04:12)]


#include <stdio.h>
#include <cs50.h>

int main(void)
{
    //Get positive integer from user
   int n;
   do
   {
       n = get_int("Width: ");
   }
   while (n < 1);

   //Print out that many question marks
   for (int i = 0; i < n; i++)
   {
       printf("?");
   }
   printf("\n");
}
