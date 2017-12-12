# Larson-scanner

https://www.youtube.com/watch?v=60ab3kF-zPM


## Video, Code & Codebender link:
http://20524.hosts.ma-cloud.nl/bewijzenmap/jaar1/periode4/R&D/larson/

### Code:
int del=100; // delay between LED movements

void setup()
{
  DDRD = B11111111; // D0~D7 outputs
}

void loop()
{

  //links
  PORTD = B00000001;
  delay(del);
  PORTD = B00000011;
  delay(del);
  PORTD = B00000111;
  delay(del);
  PORTD = B00001110;
  delay(del);
  PORTD = B00011100;
  delay(del);
  PORTD = B00111000;
  delay(del);
  PORTD = B01110000;
  delay(del);
  PORTD = B11100000;
  delay(del);
  PORTD = B11000000;
  delay(del);
  PORTD = B10000000;
  delay(del);

  PORTD = B00000000;
  delay(del);

  //rechts
  PORTD = B11000000;
  delay(del);
  PORTD = B11100000;
  delay(del);
  PORTD = B01110000;
  delay(del);
  PORTD = B00111000;
  delay(del);
  PORTD = B00011100;
  delay(del);
  PORTD = B00001110;
  delay(del);
  PORTD = B00000111;
  delay(del);
  PORTD = B00000011;
  delay(del);
  
  PORTD = B00000000;
  delay(del);
} 
