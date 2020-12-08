

# Exercise 3
We have to display our team name on the Oled with big font and add a random logo

## Schematic 
![Test Image](https://github.com/LamJustine/2020-B-Bad-and-Boudji/blob/main/lab/3/130713720_392383541845137_8753653957114174938_n.jpg)

## Code
 ```Arduino
 
const int led = 12;
 
// the setup routine runs once when you press reset:
void setup() {                
  // initialize the digital pin as an output.
  pinMode(led, OUTPUT);     
}
 
// the loop routine runs over and over again forever:
void loop() {
  digitalWrite(led, HIGH);      // turn the LED on (HIGH is the voltage level)
  delay(1000);                  // wait for a second
  digitalWrite(led, LOW);       // turn the LED off by making the voltage LOW
  delay(1000);                  // wait for a second
}

```
