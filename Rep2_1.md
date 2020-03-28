```
void setup() {
  size(800,300);
  textSize(128);
}
int i, dir=1,sp=1;
void draw() {
  fill(0);
  background(255,100,255);
  fill(0,100,0);
  text("Graphics", i, 200);
  if(i>width-550) dir=-1;
  if(i<0) dir=1;
  i=i+dir*sp;
  if(keyPressed)
    sp=key-'0';
}
```
