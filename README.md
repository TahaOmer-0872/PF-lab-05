#include <stdio.h>

int main(){
	char characters[3];\
	int Vowelcount = 0;\
	int Consonantcount = 0;\
	printf("Enter three alphabets: ");\
	scanf("%c %c %c", &characters[0], &characters[1], &characters[2]);\
	
	if (characters[0] == 'a' || characters[0] == 'e' || characters[0] == 'i' || characters[0] == 'o' || characters[0] == 'u' ||
	    characters[0] == 'A' || characters[0] == 'E' || characters[0] == 'I' || characters[0] == 'O' || characters[0] == 'U') {
	    	Vowelcount ++;
		}
	else {
		Consonantcount++;
	}
	
	if (characters[1] == 'a' || characters[1] == 'e' || characters[1] == 'i' || characters[1] == 'o' || characters[1] == 'u' ||
	    characters[1] == 'A' || characters[1] == 'E' || characters[1] == 'I' || characters[1] == 'O' || characters[1] == 'U') {
	    	Vowelcount ++;
		}
	else {
		Consonantcount++;
	}
	
	if (characters[2] == 'a' || characters[2] == 'e' || characters [2] == 'i' || characters[2] == 'o' || characters[2] == 'u' ||
	    characters[2] == 'A' || characters[2] == 'E' || characters [2] == 'I' || characters[2] == 'O' || characters[2] == 'U') {
	    	Vowelcount ++;
		}
	else {
		Consonantcount++;
	}
	
	printf("Vowel Count: %d\n", Vowelcount);
	printf("Consonant Count: %d\n", Consonantcount);
	return 0;
	
}
