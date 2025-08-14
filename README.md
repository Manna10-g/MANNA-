Solution number f:
```c
#include<stdio.h>
int main()
{
    int i, N, count = 0;
    scanf("%d",&N);

    for( int i=1; i < N ; i++)
        {
            if(N % i == 0)
            {
                count++;
            }
        }

    {
        printf("%d",count);
    }
    return 0;
}
```
solution number E :
```c
#include<stdio.h>
int main ()
{
    float r, pie=3.14159,c,d,ratio;
    scanf("%f",&r);
    c = 2*pie*r;
    d = 2*r;
    ratio = c/d;
    printf("%.5f\n",ratio);
    return 0;
}
```
