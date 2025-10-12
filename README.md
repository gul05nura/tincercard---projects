const int ledpin = 13;
const int buttonpin = 6;

void setup()
{
  pinMode(ledpin, OUTPUT);
}

void loop()
{
  digitalWrite(ledpin, HIGH);
  delay(500); // Wait for 1000 millisecond(s)
  digitalWrite(ledpin, LOW);
  delay(500); // Wait for 1000 millisecond(s)
}
  
