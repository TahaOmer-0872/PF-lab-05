#include <stdio.h>
int main (){
	int marks1, marks2, marks3;
	int highest;
	printf("enter marks af all three students: ");
	scanf("%d %d %d", &marks1, &marks2, &marks3);
    highest = (marks1 > marks2)
	?((marks1 > marks3)? marks1 : marks3) 
	:((marks2 > marks3) ? marks2 : marks3);
            
    printf("Highest marks: %d\n", highest);
return 0;
}
