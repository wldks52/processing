```
PFont f;
void setup(){
  size(800,300);
  f=createFont("굴림",50);
  textFont(f);
}
int i, dir=1, sp=1;
void draw(){
  fill(0);
  background(0,0,255);
  text("안동대 컴공 사랑합니다",10,i);
   if(i>height-10) dir=-1;
  if(i<0) dir=1;
  i=i+dir*sp;
}
void keyPressed(){
  sp = key - '0';
}
```
