#include<studio.h> 
#include< conio.h>
#include<math.h>

void nhap(int a[], int &n) { 
do
}
printf("\n Nhập só phần tử:");
scanf("%d , &n);
if(n<=0 || n > max) {
printf("\n Số phần tử không hợp lê, mời kiểm tra lại:"); }
} while (n<=0 || n > max);
for ( int i=0; i<n;i++) 
{
printf("\n Nhập a [%d]:",i);
scanf("&d,&a [i]);
 }
} void xuat (int [a],int n)
{ 
for ( int i=0; i<n;i++) 
{
ptinf("%4d",a [i])
 }
}
int TongChan(int [a], int n) {
if( n == 0)
return 0;
float s = TongChan(a, n-1);
if (a [n-1] % 2 == 0)
s= s+a [n-1];
return s;
}
int main()
{ 
int n;
int a [max]
nhap (a,n);
xuat (a,n);
int Tong = TongChan (a,n);
printf("\ Tổng số chẵn = %d",Tong);
getch():
return 0;
}

