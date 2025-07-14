// Replace with your info
#define BLYNK_TEMPLATE_ID "YourTemplateID"
#define BLYNK_TEMPLATE_NAME "CatFeeder"
#define BLYNK_AUTH_TOKEN "YourAuthToken"

#include <WiFi.h>
#include <BlynkSimpleEsp32.h>
#include <Servo.h>

char ssid[] = "YourWiFiName";        // Your Wi-Fi name
char pass[] = "YourWiFiPassword";    // Your Wi-Fi password

Servo myservo;

BLYNK_WRITE(V0) {
  int value = param.asInt(); // From button
  if (value == 1) {
    myservo.write(90);  // Open
    delay(2000);        // Wait 2 sec
    myservo.write(0);   // Close
  }
}

void setup() {
  Serial.begin(115200);
  myservo.attach(13);      // GPIO 13
  myservo.write(0);        // Start closed
  Blynk.begin(BLYNK_AUTH_TOKEN, ssid, pass);
}

void loop() {
  Blynk.run();
}
