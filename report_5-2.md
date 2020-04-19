```
void setup(){
  size(800,800);
}
float f;
void draw() {
  background(30);
  translate(mouseX, mouseY);
  scale(3);
  rotate(tan(f));
  f = f+0.01;
  fill(255,228,0);
  stroke(165,138,0);
  strokeWeight(2);
  beginShape();
  vertex(0, -50);
  vertex(14, -20);
  vertex(47, -15);
  vertex(23, 7);
  vertex(29, 40);
  vertex(0, 25);
  vertex(-29, 40);
  vertex(-23, 7);
  vertex(-47, -15);
  vertex(-14, -20);
  endShape(CLOSE);
}
```
