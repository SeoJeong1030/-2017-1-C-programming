**-2017-1-C-programming**
1번.
```c
/*센티미터를 인치로 변환하는 프로그램*/
#include <stdio.h>

int main(void)
{
	float cm;             //센티미터
	float inch;               //인치

	printf("센티미터를 입력하시오:");
	scanf_s("%f", &cm);

	inch = cm / 2.54;

	printf("%f cm는 %f 인치입니다\n", cm, inch);

	return 0;
}
```
