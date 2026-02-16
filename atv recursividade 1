#include <stdio.h>

float exponencial(float x, int y)
{
    if (y == 0)
    {
        return 1;
    }
    if (y < 0)
    {
        return 1/(exponencial(x, -y));
    }
    else 
    {
        return x * exponencial(x, y-1);
    }
}

/* 2 - escreva uma funcao recursiva p calcular uma sequencia de fibonacci */

int main()
{
    int y;
    float x, resultado;
    
    printf("Entre com a base X e o expoente Y\n");
    scanf("%f %d", &x, &y);

    resultado = exponencial(x,y);
    printf("Resultado = %.2f", resultado);
    
    return 0;
}
