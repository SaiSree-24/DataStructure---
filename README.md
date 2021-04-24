# DataStructure---
created by saisree

#include <stdio.h>
struct empolyees
{
    int empno,age;
    char empname[100];
    float salary;
};
main()
{
    int i;
    struct empolyees e1[20];
    for(i=0;i<10;i++)
    {
        printf("\nEnter the details of empolyee%d=",i+1);
        printf("\nName=");
        scanf("%s",e1[i].empname);
        printf("\nAge");
        scanf("%d",&e1[i].age);
        printf("\nPhone Number=");
        scanf("%d",&e1[i].empno);
        printf("\nSalary=");
        scanf("%f",&e1[i].salary);
    }
    for(i=0;i<=20;i++)
    {
        printf("\nEmployee Details%d=",i+1);
        printf("\n\tName=%s",e1[i].empname);
        printf("\n\tAge=%d",e1[i].age);
        printf("\n\tPhone Number=%d",e1[i].empno);
        printf("\n\tSalary=%.2f",e1[i].salary);
    }
}
