// --------------------------
// Blink an LED in Morse code
// --------------------------

int led = D7;


void setup()
{
    pinMode(led, OUTPUT);
}


void loop()
{
    /*
    . = 250ms high
    - = 750ms high
    between blinks = 250ms low
    between characters = 750ms low
    between words = 1750ms low
    
    To blink ONUR in Morse code:
    O: - - -
    N: - .
    U: . . -
    R: . - .
    */
    
    //O:
    digitalWrite(led, HIGH);
    delay(750);
    digitalWrite(led, LOW);
    delay(250);
    digitalWrite(led, HIGH);
    delay(750);
    digitalWrite(led, LOW);
    delay(250);
    digitalWrite(led, HIGH);
    delay(750);
    digitalWrite(led, LOW);
    delay(750);
    
    //N:
    digitalWrite(led, HIGH);
    delay(750);
    digitalWrite(led, LOW);
    delay(250);
    digitalWrite(led, HIGH);
    delay(250);
    digitalWrite(led, LOW);
    delay(750);
    
    //U:
    digitalWrite(led, HIGH);
    delay(250);
    digitalWrite(led, LOW);
    delay(250);
    digitalWrite(led, HIGH);
    delay(250);
    digitalWrite(led, LOW);
    delay(250);
    digitalWrite(led, HIGH);
    delay(750);
    digitalWrite(led, LOW);
    delay(750);
    
    //R:
    digitalWrite(led, HIGH);
    delay(250);
    digitalWrite(led, LOW);
    delay(250);
    digitalWrite(led, HIGH);
    delay(750);
    digitalWrite(led, LOW);
    delay(250);
    digitalWrite(led, HIGH);
    delay(250);
    digitalWrite(led, LOW);
    delay(750);
    
    //End of word:
    delay(1000);
}
