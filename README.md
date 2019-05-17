# homework0517

#C프로그래밍 과제
##문자열

##2019010891 원서영
```C
#include<stdio.h>

int my_strlen(char *src)
{
	int i = 0;
	while (src[i] != 0)
		i++;

	return i;
}

int main(void)
{
	char src[50] = "C language is hard.";
	
	int  i = my_strlen(src);
	int j = strlen(src);
	
	printf("문자열의 길이:%d = 문자열의 길이:%d",i, j);
	
	getch();
	return 0;

}
```
###설명
*src의 문자열의 길이를 반환하는 함수를 만들고
함수 strlen과 같은지 
