```
PGraphics pg;

void setup() {
  size(400, 200);
  pg = createGraphics(100,100);
}

void draw() {
  pg.beginDraw();
  pg.background(100,100,255);
  pg.stroke(255);
  pg.line(50, 50, mouseX, mouseY);
  pg.endDraw();
  image(pg, 10, 50); 
  image(pg, 130, 50);
}
```
