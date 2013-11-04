Zadania z if 

zad 1 
Program, który wczyta liczbę całkowitą i wypisze, czy jest ona większa od 5. 


...c
``
#include <stdio.h>

int main()

{

  int licz;
  printf("Podaj liczbe calkowita: ");
  scanf("%d", &licz);

  if (licz > 5) printf("Liczba jest wieksza od 5");
  if (licz < 5) printf("Liczba jest mniejsza od 5");
  if (licz = 5) printf("liczna jest rowna 5");

  return 0;

}``

zad 2
Program, który wczyta liczbę całkowitą i wypisze, czy jest ona dodatnia czy ujemna;

``#include <stdio.h>

int main()

{
   int licz ;


   printf("Podaj liczbe calkowita: ");

   scanf("%d", &licz);
   

   if (licz > 0) printf("Liczba jest dodatnia");

   if (licz < 0) printf("Liczba jest ujemna");
   

   return 0;
}``
