# OPS-2023-2024
#define pot A5
#define led 2
void setup() {
  // put your setup code here, to run once:
pinMode(led, OUTPUT);
pinMode(pot, INPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(led, HIGH);
delay(analogRead(pot));
digitalWrite(led, LOW);
delay(analogRead(pot));
}
