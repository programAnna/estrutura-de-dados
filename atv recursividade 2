#include <stdio.h>

int fibonacci(int n)
{
    if (n == 0)
    {
        return 0;
    }
    if (n == 1)
    {
        return 1;
    }
    else 
    {
        return fibonacci (n-1) + fibonacci(n-2);
    }
}


int main()
{
    int n, i;
    
    printf("Digite a quantidade de numeros da sequencia: \n");
    scanf("%d", &n);
    
    printf("Aqui está a sequencia: ");
    
    for(i=0; i<n;i++){
        printf("%d, ", fibonacci(i));
    }

    return 0;
}
