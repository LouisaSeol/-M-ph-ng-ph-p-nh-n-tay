# -M-ph-ng-ph-p-nh-n-tay
p trình in ra màn hình mô phỏng phép nhân tay 2 số nguyên dương có 3 chữ số nhập từ bàn phím. Ví dụ với 2 số nhập vào là 763 và 589 thì phải in ra màn hình như sau:
#include<stdio.h>
#include<conio.h>
void
main ()
{
  int a, b;
  char dv, chuc, tram;#include<stdio.h>
#include<conio.h>
void
main ()
{
  int a, b;
  char dv, chuc, tram;
  clrscr ();
  printf ("Nhap so bi nhan co 3 chu so a=");
  scanf ("%d", &a);
  printf ("Nhap so nhan co 3 chu so b=");
  scanf ("%d", &b);
  dv = b % 10;
  chuc = b % 100 / 10;
  tram = b / 100;
  printf ("\nMo phong phep nhan tay\n\n");
  printf ("%20d\n", a);
  printf ("%15c%5d\n", 'x', b);
  printf ("%20s\n", "-------");
  printf ("%20d\n", a * dv);
  printf ("%19d\n", a * chuc);
  printf ("%18d\n", a * tram);
  printf ("%20s\n", "-------");
  printf ("%20ld\n", long (a) * b);
  getch ();

}
  clrscr ();
  printf ("Nhap so bi nhan co 3 chu so a=");
  scanf ("%d", &a);
  printf ("Nhap so nhan co 3 chu so b=");
  scanf ("%d", &b);
  dv = b % 10;
  chuc = b % 100 / 10;
  tram = b / 100;
  printf ("\nMo phong phep nhan tay\n\n");
  printf ("%20d\n", a);
  printf ("%15c%5d\n", 'x', b);
  printf ("%20s\n", "-------");
  printf ("%20d\n", a * dv);
  printf ("%19d\n", a * chuc);
  printf ("%18d\n", a * tram);
  printf ("%20s\n", "-------");
  printf ("%20ld\n", long (a) * b);
  getch ();

}
