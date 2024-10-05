# Embedded-Systems-internship-task-1-
Embedded Systems Internship task 1
// Define pin for LED
int ledPin = 9; // LED connected to digital pin 9
// Time intervals for LED blink in milliseconds
int onTime = 500; // LED ON for 500 milliseconds
int offTime = 1000; // LED OFF for 1000 milliseconds
void setup() {
 // Initialize the LED pin as an output
 pinMode(ledPin, OUTPUT);
}
void loop() {
 // Turn the LED ON
 digitalWrite(ledPin, HIGH);
 delay(onTime); // Wait for the ON time
 // Turn the LED OFF
 digitalWrite(ledPin, LOW);
 delay(offTime); // Wait for the OFF time
 }
 
