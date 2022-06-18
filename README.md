#include<stdio.h>
#include<conio.h>

void main()
{

struct  EMP
{
  int   eno;
  char  ename[20];
  float sal;
 }e1,e2;

   clrscr();
   printf("\n Enter First Employee Record information : \n");
   printf("\n Eno : ");
   scanf("%d",&e1.eno);
   printf("\n Ename : ");
   scanf("%s",&e1.ename);
   printf("\n Salary : ");
   scanf("%f",&e1.sal);
   printf("\n Enter Second Employee Record Information : \n");
   printf("\n Eno : ");
   scanf("%d",&e2.eno);
   printf("\n Ename : ");
   scanf("%s",&e2.ename);
   printf("\n Salary : ");
   scanf("%f",&e2.sal);
   printf("\n **** AMC Computer Employee Records *****\n");
   printf("\ Rec#1 Employee information :\n");
   printf("\n Employee Number      : %d",e1.eno);
   printf("\n Name of the Employee : %s",e1.ename);
   printf("\n Salary               : %f",e1.sal);
   printf("\n -------------------------------------------");
   printf("\n Rec#2 Employee information : \n");
   printf("\n Employee Number      : %d",e2.eno);
   printf("\n Name of the Employee : %s",e2.ename);
   printf("\n Salary               : %f",e2.sal);
   getch();
   }
