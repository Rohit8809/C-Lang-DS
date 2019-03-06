#include<stdio.h>
#include<conio.h>
void main()
{
		int r,c,i,ch,k;
		r=c=0;
		clrscr();
		gotoxy(c,r);
		textcolor(YELLOW);
		cprintf("%c",201);
		gotoxy(80,1);
		textcolor(YELLOW);
		cprintf("%c",187);
		gotoxy(1,24);
		textcolor(YELLOW);
		cprintf("%c",200);
		gotoxy(80,24);
		textcolor(YELLOW);
		cprintf("%c",188);
		for(i=2;i<80;i++)
	{
		gotoxy(i,1);
		textcolor(YELLOW);
		cprintf("%c",205);
	}
		for(i=2;i<24;i++)
		{
			gotoxy(1,i);
			textcolor(YELLOW);
			cprintf("%c",186);
		}
		for(i=2;i<80;i++)
		{
		gotoxy(i,24);
		textcolor(YELLOW);
		cprintf("%c",205);
		}
		for(i=2;i<24;i++)
			{
				gotoxy(80,i);
				textcolor(YELLOW);
				cprintf("%c",186);
			}
				for(i=2;i<80;i++)
			{
				gotoxy(i,4);
				textcolor(YELLOW);

				cprintf("%c",196);
			}
				gotoxy(65,2);
				printf("%s",__TIME__);
				gotoxy(65,3);
				printf("%s",__DATE__);

gotoxy(35,2);
textattr(128+RED);
cprintf("Tutorial of C");
gotoxy(35,3);
textcolor(RED);
cprintf("_____________");
gotoxy(75,23);
textcolor(BLUE);
cprintf("Rohit");
gotoxy(2,20);
textcolor(RED);
cprintf("Please select your choice");
gotoxy(2,21);
textcolor(RED);
cprintf("0.Exit");
gotoxy(2,22);
textcolor(RED);
cprintf("1.Introduction to C");
gotoxy(2,23);
textcolor(RED);
cprintf("2.Data Type");/*
gotoxy(2,18);
textcolor(RED);
cprintf("3.");
gotoxy(2,19);
textcolor(RED);
cprintf("4.");
gotoxy(2,19);
textcolor(RED);
cprintf("5.");
gotoxy(2,20);
textcolor(RED);
cprintf("6.");
gotoxy(2,21);
textcolor(RED);
cprintf("7."); */
gotoxy(2,5);
textattr(BLUE);
cprintf("Enter your choice=");
scanf("%d",&ch);
switch(ch)
{
case 1:
	gotoxy(2,6);
      printf("* C is a Structural programing language.");
	gotoxy(2,7);
      printf("* C Language developed by Sir Dennis Richiee in 1972 at AT & T Bell Lab.");
	gotoxy(2,8);
      printf("* It is a physics lab sitituated in U.S.A.");
      gotoxy(2,9);
      printf("* C is a high level programing language as well as low level programing ");
      gotoxy(2,10);
      printf("  language.Hence, it is also known as midddle level programing language.");
      gotoxy(2,11);
      printf("* C is a case sensitive  programing language.");
      gotoxy(2,12);
      printf("* In C all library function , keywords & escape sequence are  pre-defined");
      gotoxy(2,13);
      printf("  in lower case letter."); break;

case 2:
	gotoxy(2,6);
      printf("*C Language ");break;
case 0:
	exit(0);
      default:
      gotoxy(2,6);
      printf("Sorry Invalid option ");
      }

getch();
}
