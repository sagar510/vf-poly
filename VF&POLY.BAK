#include<iostream.h>
#include<conio.h>

class weapon
{
 public:
 virtual void weaponload()
 {
  cout<<"weapon loaded\n";
 }
};

class gun : public weapon
{
 public:
 void weaponload()
 {
  cout<<"gun loaded\n";
 }
};

class bomb : public weapon
{
 public:
 void weaponload()
 {
  cout<<"bomb loaded\n";
 }
};

void main()
{
 clrscr();
/* weapon *bptr;

 bptr=new weapon();
 bptr->weaponload();

 bptr=new gun();
 bptr->weaponload();

 bptr=new bomb();
 bptr->weaponload();

 delete bptr;        */

 weapon w;gun g;bomb b;
 weapon *bptr;
 bptr=&w;
 bptr->weaponload();

  bptr=&g;
 bptr->weaponload();

  bptr=&b;
 bptr->weaponload();

 getch();
}