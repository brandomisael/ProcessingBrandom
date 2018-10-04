# ProcessingBrandom
Ejercicio 1.1
int x1=125, y1=125;
int x2=125, y2=375;
int x3=375, y3=125;
int x4=375, y4=375;
int tam=1;
int b=255;
int g=#A7A7AA;

void setup(){
  size (500,500);
  smooth();
}

void draw (){
  background(b);
  ellipse(x1,y1,125,125);
  fill(g);
  ellipse(x2,y2,125,125);
  fill(g);
  ellipse(x3,y3,125,125);
  fill(g);
  ellipse(x4,y4,125,125);
  fill(g);
  x1=x1+tam;
  x2=x2+tam;
  x3=x3-tam;
  x4=x4-tam;
  y1=y1+tam;
  y2=y2-tam;
  y3=y3+tam;
  y4=y4-tam;
}






Ejercicio 1.2
void setup()
{
  size(600,600);
  rectMode(CENTER);
  background(255);
  fill(255,100,0);
  rect(300,300,300,500,50);
}


//rojo
void rojo()
{
  fill(255,0,0);
  stroke(0);
  ellipse(300,150,100,100);
}

//amarillo
void amarillo()
{
  fill(255,255,0);
  stroke(0);
  ellipse(300,300,100,100);
}

//verde
void verde()
{
  fill(0,255,0);
  stroke(0);
  ellipse(300,450,100,100);
}
void draw ()
{
  if(mousePressed){
    delay(200);
  int x;
  x=round(random(1,3));
  println(x);
  //rojo en blanco
  fill(255);
  stroke(0);
  ellipse(300,150,100,100);
  //amarillo en blanco
  fill(255);
  stroke(0);
  ellipse(300,300,100,100);
  //verde en blanco
  fill(255);
  stroke(0);
  ellipse(300,450,100,100);
  switch(x)  {
    case 0:
    break;
  
    case 1:
      rojo ();
    break;
  
    case 2:
      amarillo ();
    break;
    
    case 3:
      verde ();
    break;
              }
  }
}



Ejercicio 2
void setup()
{
  size(600,600);
  rectMode(CENTER);
  background(255);
  fill(255,100,0);
  rect(300,300,300,500,50);
}


//rojo
void rojo()
{
  fill(255,0,0);
  stroke(0);
  ellipse(300,150,100,100);
}

//amarillo
void amarillo()
{
  fill(255,255,0);
  stroke(0);
  ellipse(300,300,100,100);
}

//verde
void verde()
{
  fill(0,255,0);
  stroke(0);
  ellipse(300,450,100,100);
}
void draw ()
{
  if(mousePressed){
    delay(200);
  int x;
  x=round(random(1,3));
  println(x);
  //rojo en blanco
  fill(255);
  stroke(0);
  ellipse(300,150,100,100);
  //amarillo en blanco
  fill(255);
  stroke(0);
  ellipse(300,300,100,100);
  //verde en blanco
  fill(255);
  stroke(0);
  ellipse(300,450,100,100);
  switch(x)  {
    case 0:
    break;
  
    case 1:
      rojo ();
    break;
  
    case 2:
      amarillo ();
    break;
    
    case 3:
      verde ();
    break;
              }
  }
}

