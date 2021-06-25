- 👋 Hi, I’m @Harishlearner
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Harishlearner/Harishlearner is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <stdio.h>

float calcbonus
 (float yearsworked);

int main() 
{
  
 float rafiquebonus = calcbonus (15);
  
 float sammerbonus = calcbonus (10);

   float harishbonus = calcbonus (5);

   
   printf("rafiques bonus : %.2f \n \n",rafiquebonus);
  
 
   printf("sammers bonus : %.2f \n\n",sammerbonus);
  
 
   printf("harish bonus : %.2f \n\n ",harishbonus);
   
 
    return 0;

}


float calcbouns (float yearsworked){
  
  float bonus = yearsworked * 500;

    if (yearsworked >5){

        bonus += 5000;

    }
else if(yearsworked >10)
{
   
     bonus +=1000;
 
   }
 
   return bonus;

}
