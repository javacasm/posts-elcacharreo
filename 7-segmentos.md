 void loop()
 {

 
void muestraValor(int b1,int b2,int b3,int b4)
{
 // enviamos el 4º digito
 digitalWrite(latchPin, LOW);
 shiftOut(dataPin, clockPin, LSBFIRST, b4);
 shiftOut(dataPin, clockPin, LSBFIRST, B10000000);
 digitalWrite(latchPin, HIGH);
 // enviamos el 4º digito
 digitalWrite(latchPin, LOW);
 shiftOut(dataPin, clockPin, LSBFIRST, b3);
 shiftOut(dataPin, clockPin, LSBFIRST, B01000000);
 digitalWrite(latchPin, HIGH);
 digitalWrite(latchPin, LOW);
 shiftOut(dataPin, clockPin, LSBFIRST, b2);
 shiftOut(dataPin, clockPin, LSBFIRST, B00100000);
 digitalWrite(latchPin, HIGH);
 digitalWrite(latchPin, LOW);
 shiftOut(dataPin, clockPin, LSBFIRST, b1);
 shiftOut(dataPin, clockPin, LSBFIRST, B00010000);
 digitalWrite(latchPin, HIGH);
}