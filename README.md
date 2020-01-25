var ellipse;
var r = 0;
var g = 50;
var b = 255;

function setup() {
  createCanvas(1200,600);
}

function draw() {
  r = map(mouseX,200,1200,0,2055);
  g = map(mouseX,50,1200,50,1000);
  b = map(mouseX,0,1200,255,00);
  background(r,g,b);
  fill(10);
  ellipse(mouseX,200,50,50);
  ellipse.debug=true;
}
