```
void setup() {
size(800, 300);
textSize(200);
}

int i, dir=1, sp=1;
void draw() {
fill(0);
background(255,0,255);
text("jian", i, 200);
if(i>width-350) dir=-1;
if(i<0) dir=1;
i = i+dir*sp;
}

void keyPressed(){
sp = key-'0'; 
}
```
