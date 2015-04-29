# PlotclockDraw
<b>Setup:</b>
  1. Based on Joo's Plotclock at Thingiverse. http://www.thingiverse.com/thing:248009
  2. Servo motors on PIO#2,3,4
  3. HC-06 on PIO#10,11(RX,TX) with SoftwareSerial.
  4. LCD1602_I2C module on An#4,5 with I2C

<b>Code:</b>
  1. Android App: bt_clockdraw.aia for http://ai2.appinventor.mit.edu/
  2. Arduino Uno: plotDraw.ino

<b>Note:</b>
  1. The positions of lift-servo motor are changed as...
// lift positions of lifting servo<br>
#define LIFT0 1900 // on drawing surface<br>
#define LIFT1 1725  // between numbers<br>
#define LIFT2 1225  // going towards sweeper<br>
  2. L1 length is changed to 40 cause of my L1 arm is just a bit longer than original design.
// length of arms<br>
#define L1 <b>40</b>  //35<br>
#define L2 55.1<br>
#define L3 13.2<br>

