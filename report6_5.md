```
PGraphics pg;
void setup(){
  size(400,400);
  pg = createGraphics(200,200);
}
void draw(){
  pg.beginDraw();
  pg.background(195,100,192);
  pg.stroke(255);
  pg.strokeWeight(5);
  pg.line(100, pg.height*0.5,
    mouseX-100, mouseY-100);
  pg.endDraw();
  image(pg, 100,100);
}
```
