# nhom14
// Nguyen Trong Duc
#include <stdio.h>
#define PI 3.14
int main()
{
 FILE*p=fopen("D:\\Bankinh.txt","r");
 float r, s, c;
 fscanf(p,"%f",&r);
 fclose(p);
 //printf("Nhap ban kinh r: ");
 //scanf("%f", &r);
 c = r * 2 * PI;
 s = r*r*PI;
 printf("Chu vi va dien tich cua hinh tron lan luot la %0.2f va %0.2f", c, s);
 return 0;
}
