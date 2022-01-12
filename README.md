# Claw

This is a electrical claw project in APSC 101

What it does
  The claw it self has mainly five parts:
  - Claw body made with cardboard
  - Arduino Uno board on top
  - Sonar sensor
  - Servo motor
  - Handle for hanging at hands
  
  The code is running on a arduino uno board. It continuously reads signal from the sonar sensor facing the ground, and then open the claw through a servo motor when it's 30cm above the ground. It will then keep opend for a while, waiting you to put the claw around the object. Then it will close the claw and you can move it up with the object. Whenever the claw enters the 30cm distance range again from the ground, it will reopen and release the object.

PS. Partly contributed by APSC 101 teaching team
