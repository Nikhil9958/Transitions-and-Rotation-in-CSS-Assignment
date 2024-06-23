/* Qs1. Add a 2s transition on box1 for width changes.
       It should have 'ease-in' speed curve & 0.5s delay  */

#box1 {
  width: 100px;
  height: 100px;
  background: green;
  transition: width 2s ease-in 0.5s;
}

#box1:hover {
  width: 600px;
}

/* Qs2. Using transform, move box2 200px to the right  & 
        200px down. Also rotate it 90deg.*/

#box2 {
  width: 100px;
  height: 100px;
  background: red;
  transform: translate(200px,200px) rotate(90deg);

}

/* Qs3. Using transform, skew box3 20deg along the x axis.*/

#box3 {
  width: 100px;
  height: 100px;
  background: lightblue;
  transform: skewX(20deg);
}

/* Qs4. Set a 2px horizontal & 2px vertical, green shadow 
        for box4, with a 5px blur radius.*/

#box4 {
  width: 100px;
  height: 100px;
  background: lightgreen;
  box-shadow: 2px 2px 5px green;
  margin-bottom: 25px;
}

/* Qs5. Set Your picture or any picture as the background of the div
        "myPic". Also, set transparency of this div to 50%. */

#myPic {
  width: 200px;
  height: 200px;
  background: pink;
  background-image: url("pexels-thatguycraig000-1563356.jpg");
  background-size: cover;
  opacity: 0.5;
}
