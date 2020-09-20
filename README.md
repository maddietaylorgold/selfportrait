function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(0);
  
   //hair
    noStroke();
	fill('#301607');
	ellipse(200, 130, 150, 190);
	fill('#301607');
    rect(125, 130, 150, 130);
	
  //face
  stroke(242,211,188);
  fill(242,211,188);
 ellipse(200,107,100,106);
  rect(188,130,20,50)
  
  //hair
  noStroke();
	fill('#301607');
  ellipse(220, 55, 50, 20);
  fill('#301607');
  ellipse(178, 63, 50, 25);
 
	fill('#301607');
  ellipse(235.8, 157, 54.8, 50);
  fill('#301607');
  ellipse(160, 157, 54.8, 50);
  strokeWeight(18)
  stroke('#301607');
  line(140,100,165,140);
  line(257,100,232,140);
  
 //chin
  strokeWeight(.5);
  stroke(101, 67, 33);
  noFill();
  arc(198,145,23,10, TWO_PI,PI,OPEN);
  
  //Eyebrows
  stroke(101, 67, 33);
  strokeWeight(2.5);
  noFill();
  arc(178, 82, 26, 6, PI, TWO_PI, OPEN);
  arc(223, 82, 26, 6, PI, TWO_PI, OPEN);
  
  //eyes
  stroke(255);
  fill(255);
  ellipse(180, 95, 22, 6);
  ellipse(220, 95, 22, 6);
  
  //eyelash
   strokeWeight(.5);
  stroke(0);
  line(212, 88, 210, 92);
  line(221, 87, 218, 91);
  line(230, 87, 226, 91);
  line(237, 90, 233, 92);
  
   strokeWeight(.5);
  stroke(0);
  line(167, 92, 163, 90);
  line(176, 91, 172, 87);
  line(185, 91, 182, 87);
  line(192, 92, 190, 88);
  
  
   stroke(0,255,0);
  fill(0,150,0);
  ellipse(180, 95, 12, 9);
  ellipse(220, 95, 12, 9);
  
  stroke(0);
  fill(0);
  ellipse(180, 95, 5, 4);
  ellipse(220, 95, 5, 4);
  
  stroke(254,127,156,110);
  fill(254,127,156,172);
  ellipse(180, 113, 14, 9);
  ellipse(220, 113, 14, 9);
  
    stroke(255);
  fill(255);
  ellipse(180, 93, .01, .01);
  ellipse(220, 93, .01, .01);
  
  //nose
  strokeWeight(1);
  stroke(101, 67, 33);
  line(200,107,200,120);
  
  //cheek
  stroke(255);
  fill(255);
  ellipse(180, 110, 3, 1);
  ellipse(220, 110, 3, 1);
  
  //mouth
  stroke(223,82,134);
  fill(223,82,134);
  ellipse(200, 130, 20, 5);
}
