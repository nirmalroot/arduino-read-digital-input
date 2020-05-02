void setup() {
pinMode (2, INPUT_PULLUP);
pinMode (3, OUTPUT);
}

void loop() {
  if (digitalRead(2)==0)
  {
    digitalWrite (3, HIGH);
    }
  else if (digitalRead(2)==1)
  {
    digitalWrite (3, LOW);
    }
}
