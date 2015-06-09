//Bastian Escalona Morales
//Tarea Numero 4 , Lenguaje de Programacion.
#include <stdio.h>
#define N 30
int main(){
	char array[N];
        int i=0,j=0,k=0;
        for(i=0;i<N;i++) array[i]=0; //Recorre arreglo llenandolo con 0
        printf("Ingrese la palabra\n");
        scanf("%s",array); //Pide la palabra por teclado.
        char temp[N];
        for(i=0;i<N;i++) temp[i]=0; //Recorre arreglo llenandolo con 0
        int cont = 0;
	int aux[N];
        for(i=0;i<N;i++) aux[i]=0; //Recorre arreglo llenandolo con 0
	while(j<N){
                aux[j] = 0;
		cont=0;
		temp[k]=array[j];
		for(i=0 ; i<N; i++){ //Ve si las letras son iguales sin contar la primera.
                        if (temp[k] == 0) break;
			if (temp[k] == array[i]){
				cont++;
			}
		}
                aux[j] = cont;
		j++;
                for(i=0;i<k && j<N;i++){
                        if( array[j] == temp[k]){
                                j++;
                                i=0;
                        }
                }
                k++;
	}
        cont = 0;
        for(i=0;i<N;i++) if( aux[i]%2 == 1 ) cont++; //Se ve si es palindromo o no, si lo es arrojara un 1.
        if (cont <= 3) cont = 1;
        else cont = 0;
	printf("%d\n", cont );
	return 0;
}
