int a=10;

void setup() {
  pinMode(a, OUTPUT);
}

void loop() {
  for(int i = 1000; i > 0; i = i - 100){
    blink1(10, i);
  }
}

void blink1(int pinLed, int time1){
  digitalWrite(pinLed, 1);
  delay(time1);
  digitalWrite(pinLed, 0);
  delay(time1);
}
