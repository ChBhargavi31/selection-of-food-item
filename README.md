#include<stdio.h>
int main()
{
printf("choose an food item:\n 1.Pizza,cost=239  \n 2.Burger,cost=129 \n 3.Pasta,cost=179 \n 4.French Fries,cost=99 \n 5.Sandwich,cost=149");
int choice=0;
scanf("%d",&choice);
switch(choice)
{
  case 1:
   printf("you picked Pizza,cost=239");
   break;
  case 2:
   printf("you picked Burger,cost=129");
   break;
  case 3:
   printf("you picked Pasta,cost=179");
   break;
  case 4:
   printf("you picked French Fries,cost=99");
   break;
  case 5:
   printf("you picked Sandwitch,cost=149");
   break;
  default:
   printf("invalid choice");
}
return 0;
}
