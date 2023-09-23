# c code 
Great and easy to work program for total mark.


#include <stdio.h>

int main() {
    
    int english;
    printf("enter your English mark:");
    scanf("%d",& english);
    printf("your English mark is %d",english);
    printf("\n enter your tamil mark:");
    int tamil;
    scanf("%d",&tamil);
    printf("\n your tamil mark is %d ",tamil);
    int maths;
    printf("\n enter your maths mark:");
    
    scanf("%d",&maths);
    printf("\nyour maths mark is %d",maths);
    printf("\n your computer science mark or biology mark :");
    int biocs;
    scanf("%d",&biocs);
    printf("your computer science or biology mark is %d",biocs);
    int phy;
    printf("\n enter your physics mark:");
    scanf("%d",&phy);
    printf("your physics mark is %d",phy);
    int che;
    printf("\n enter your chemistry mark:");
    scanf("%d",&che);
    printf("your chemistry mark is %d",che);
    int total=english+tamil+maths+biocs+phy+che;
    printf("\n\nyour total is %d",total);
   // int cut=phy+che+maths/3;
 //  printf("\n your cuttoff is %d ",cut);
   int per=total/6;
   printf("\n your percentage is %d",per);
    
    }
