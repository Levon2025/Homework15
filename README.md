# Homework15
#include <stdio.h>

int main(){
	int num = 0;
	for(int i = num ; i <= 100;i++){
	if(i % 3 == 0 && i % 5 ==0){
	        printf("Fizzbuzz\n");
}	else if(i % 3 == 0){
		printf("Fizz\n");
}       else if( i % 5 == 0){
	        printf("Buzz\n");
}else {
	printf("%d\n",i);
	
}
}
	return 0;
}
