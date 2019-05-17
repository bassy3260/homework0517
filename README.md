# homework0517

# C프로그래밍 과제
## 문자열

## 2019010891 원서영
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
### 설명
* src의 문자열의 길이를 반환하는 함수를 만들고
함수 `strlen`과 같은지 비교하라.

### 사용법 
* `my_strlen` 함수를 만든다.
* `main`함수에서 `strlen` 함수와 같은 값이 나오는지 비교한다.
