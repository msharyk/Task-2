# Task-2

this is the circuit in tinkercad 
https://www.tinkercad.com/things/brY9tW9UGd6-exquisite-crift-waasa/editel?sharecode=-IhWYwaRc4eRi6aq2Yunmka-qjSlPHvvqAFFxeCC2vI

i used 1 Arduino
1 bread board
2 Gear motors for arms
1 Power supply 

----

Code
--
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
