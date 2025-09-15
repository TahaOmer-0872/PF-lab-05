#include <stdio.h>\
int main (){\
	int i;\
	printf("enter an integer: ");\
	scanf("%d", &i);\
	i = (i %2==0)? printf("%d is Even", i):\
	i = (i %3==0)? printf("%d is divisible by 3", i): printf("%d odd and not divisible by 3", i);\
return 0;\
}
