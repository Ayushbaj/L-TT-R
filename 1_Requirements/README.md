UNIT CONVERSION

Use this Conversion Calculator to convert between commonly used units.many different systems of units have been used,
where a system of units is defined as a collection of units of measurement with rules that relate them to each other. 
A unit of measurement is a defined magnitude of a quantity that it used as a standard for measurement for the same kind of quantity, 
such as measurements of length, weight, and volume,tempurature etc.

It will convert celsius to fahrenheit,fahrenheit to celsius,Meter to Feet,Feet to Meter,KM toM/CM/MM.

          
          
         
         /* Convert Celsius to Fahrenheit */


#include<stdio.h>

void main()
{

   float c,f;
   printf("Enter the temperature in Celcius: ");
   scanf("%f", &c);
   f = c*9/5 + 32;
   printf("Temperature in Farenheit: %f", f);
}


         /* Convert Farenheit to Celcius */
          

#include<stdio.h>
void main()
{

    float c, f;
    scanf("%f",&f);
    printf("Farenheit : "); 
    c = (f 32)*5/9; 
    printf("Celcius: %f",c);
}


       /Convert Meter to Feet/

#include<stdio.h>
void main()
{
  float m, f;
  printf("Meter: ");
  scanf("%f", &m);
  f = 3.2808399
  printf("Feet: %f".f);
}

          /* Convert Feet to Meter */

#include<stdio.h>
void main()
{
  float m, f;
  printf("Feet: "); 
  scanf("%f",&f); 
  m = f/3.2808399; 
  printf("Meter: %f",m);
}
      
      /*Convert Km to M/cm/mm */
      
 #include<stdio.h>

void main()

{

  float km;
  
  char vi
  
  float ans;
  
  printf("K.M. : "):
  
  scanf("%f",&km);
  
  printf("KM will be changed in (M-Meter, c-Centimeter, milimeter)
  
  fflush(stdin); 
  
  scanf("%c", &v);
  
  if(v=='M') 
  
  
 ans-km 1000; 
 
 if(v=='c')
 ans-km 100000; 
 ans km 1000000;
 printf("Answer %.2f", ans);
}
