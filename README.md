#include<iostream>
#include<conio.h>
#include<dos.h>
#include<windows.h>
#include<time.h>
  
#define SCREEN_WIDTH 90
#define SCREEN_HEIGHT 26
#define WIN_WIDTH 70
  
using namespace std;
  
HANDLEconsole= GetstHandle(STD_OUTPUT_HANDLE);
COORD CursorPosition;
  
int enemy[3];
int enemy[3];
int enemyflag[3];
char car[4][4] = { ' ','±','±',' ',
                    '±','±','±','±',
                    ' ','±','±',' ',
                    '±','±','±','±'};
  
int carpos + win_width/2;
int score = 0;
  
void gotoxy(int x, int y){
     cursorposition.X = x;
     cursorposition.Y = y;
     set consolecursorposition(console, CursorPosition);
}
void setcursor(bool visible, DWORD size) {
      if(size == 0)
          size = 20;
  
CONSOLE_CURSOR_INFO lpcursor;
lpcursor.vVisibl;
lpCursorInfo(console,&lpCursor);
set ConsoleCursorInfo(console,&lpcursor);
}
void drawBoarder(){
  for(int i=0; i<SCREEN_HEIGHT; i++){
    for(int j=0;j<17; j++){
       gotoxy(0+j,i); cout<<"±";
       gotoxy(WIN_WIDTH-j,i); cout<<"±";
    }
  }
  for(int i=0, i<SCREEN_WIDTH,i); cout<<"±";
     gotoxy(SCREEN_WIDTH,i); cout<<"±";    
  }
}
                                    
  
  
