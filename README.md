# ProjetoLop3
//nome:João André Da Silva Júnior; subturma:D
etapa 3


var x=200
var t=0
function setup() { createCanvas(800, 800); }
function draw() { 
  background(220); 
  rect(t,100,100,200) 
t=t+2
if(t>800)
  {
    t=0
  }
    ellipse(x,190,50,50)
if ( keyIsDown(RIGHT_ARROW) )
{
x = x + 3;
}
}
