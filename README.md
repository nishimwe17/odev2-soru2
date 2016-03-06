#include <stdio.h>

int main()
{
  int sayi,enb ,enk ;
    
  printf("sayi giriniz:\n");
  scanf("%d",&sayi);
  enb = sayi;
  enk = sayi;
  while(sayi !=0)
  {
     printf("sayi giriniz:\n");
     scanf("%d",&sayi);
    if (sayi>enb)
    enb = sayi;
    
    else if (sayi<enk)
    enk = sayi;
  }

  printf("en buyuk sayi:%d\n", enb);
  printf("en kucuk sayi:%d\n", enk);
  
  return 0;
}
