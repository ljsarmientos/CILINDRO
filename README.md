#include <stdio.h>
#define PI 3.14159

int main() {
    float radio, altura, areaBase, areaLateral, areaTotal;

    printf("Radio de la base: ");
    scanf("%f", &radio);

    printf("Altura del cilindro: ");
    scanf("%f", &altura);

    areaBase = PI * radio * radio;
    areaLateral = 2 * PI * radio * altura;
    areaTotal = 2 * areaBase + areaLateral;

    
    printf("Área total del cilindro: %.2f\n", areaTotal);

    return 0;
}
