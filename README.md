# progettoTEM
void setup() 
{
  size(280, 250);
  smooth();
  noStroke();
  background(255, 222, 173);
}

void draw() 
{ 
  smooth();
  noStroke();
  
  stroke(0, 0, 0);
  fill(220, 20, 60);
  rotate(frameCount / 3);
  ellipseMode(CENTER);
  ellipse(120.0,120.0,160.0,160.0);

  ellipseMode(CENTER);
  fill(205, 92, 92);
  stroke(0, 0, 0);
  ellipse(120.0,120.0,30.0,30.0);
  
  //1
  pushMatrix();
  stroke(153, 51, 0);
  translate(120, 120);
  rotate(radians(frameCount * 0.1));
  fill(255, 255, 255);
  rect(0, 0, 2, 60, 2); 
  popMatrix(); 
  
  pushMatrix();
  stroke(153, 51, 0);
  translate(120, 120);
  rotate(radians(frameCount * (-0.1)));
  fill(255, 255, 255);
  rect(0, 0, 2, 60, 2); 
  popMatrix(); 
  
  //2
  pushMatrix();
  stroke(153, 51, 0);
  translate(120, 120);
  rotate(radians(frameCount * 0.2));
  fill(255,255,255);
  rect(0, 0, 2, 60, 2); 
  popMatrix();
  
  pushMatrix();
  stroke(153, 51, 0);
  translate(120, 120);
  rotate(radians(frameCount * (-0.2)));
  fill(255,255,255);
  rect(0, 0, 2, 60, 2); 
  popMatrix();
  
  //3
  pushMatrix();
  stroke(153, 51, 0);
  translate(120, 120); //parametri l e h
  rotate(radians(frameCount * 0.3));
  fill(255,255,255);
  rect(0, 0, 2, 60, 2); 
  popMatrix();
  
  pushMatrix();
  stroke(153, 51, 0);
  translate(120, 120); //parametri l e h
  rotate(radians(frameCount * (-0.3)));
  fill(255,255,255);
  rect(0, 0, 2, 60, 2); 
  popMatrix();

  //4
  pushMatrix();
  stroke(153, 51, 0);
  translate(120, 120); //parametri l e h
  rotate(radians(frameCount * 0.4));
  fill(255,255,255);
  rect(0, 0, 2, 60, 2); 
  popMatrix();
  
  pushMatrix();
  stroke(153, 51, 0);
  translate(120, 120); //parametri l e h
  rotate(radians(frameCount * (-0.4)));
  fill(255,255,255);
  rect(0, 0, 2, 60, 2); 
  popMatrix();


  fill(255, 222, 173);
  ellipseMode(CENTER);
  stroke(0, 0, 0);
  ellipse(120.0,120.0,10.0,10.0);
}
