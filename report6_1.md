```
 void setup(){
  size(500,500);
  background(255,255,255);
  stroke(255,0,0);
  strokeWeight(7);
}
void draw(){
  if(mousePressed)
      line(pmouseX,pmouseY,mouseX,mouseY);  
}
```
