# Glowing-New-Year-Ornaments-with-Arduino-and-LEDs
Creating glowing New Year ornaments using Arduino and LEDs.
const int ledPin = 9;

void setup() {
    pinMode(ledPin, OUTPUT);
}

void loop() {
    digitalWrite(ledPin, HIGH);
    delay(1000);
    digitalWrite(ledPin, LOW);
    delay(1000);
}
