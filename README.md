# Write-a-program-to-calculate-the-value-of-the-following-expression-
S(n) = 1 + 3 + 5 + … +(2n+1), with any n input from the keyboard.
#include<stdio.h>
#include<conio.h>
main()
{
    int i,n,s=0;
    printf("Nhap n=");
    scanf("%d",&n);
    for(i=1;i<=2*n+1;i=i+2)
    {
        s=s+i;
    }
    printf("Gia tri bieu thuc la: %d ", s);
    getch();
}
