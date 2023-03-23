#2023-03-23 4주차 C언어 수업

```
#include <stdio.h>

int main(void)
{
    int a,b,c1,c2,c3;

    printf("두 수를 입력하세요: ");
    scanf("%d %d", &a, &b);

    c1 = a * (b % 10);
    printf("%d\n", c1);

    c2 = a * ((b / 10) % 10);
    printf("%d\n", c2);

    c3 = a * (b / 100);
    printf("%d\n", c3);

    printf("%d", c1 + c2*10 + c3*100);

    return 0;
}
