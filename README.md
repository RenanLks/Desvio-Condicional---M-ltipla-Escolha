#include <stdio.h>
 
int main (){
    int local;
    printf("Digite a localização, valor entre 1 e 10: ");
    scanf("%d",&local);
    switch(local){
        case 1:
            printf("%d - Sul",local);
            break;
        case 2:
            printf("%d - Norte", local);
            break;
        case 3:
            printf("%d - Leste", local);
            break;
        case 4:
            printf("%d - Oeste", local);
            break;
        case 5:
        case 6:
            printf("%d - Nordeste", local);
            break;
        case 7:
        case 8:
        case 9:
            printf("%d - Sudeste", local);
            break;
        case 10:
            printf("%d - Centro-Oeste", local);
            break;
        default:
            printf("%d - número não encontrado",local);
    }
      return 0;
}
