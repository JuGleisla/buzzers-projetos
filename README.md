# Buzzers
## Intro "Pull me Under" - Dream Theater

```c

// Definindo as notas

#define NOTE_E3  165  // Mi 
#define NOTE_A4  440  // Lá 
#define NOTE_G4  392  // Sol 
#define NOTE_FS4 370  // Fá# 
#define NOTE_CS4 277  // Dó# 
#define NOTE_C4  262  // Dó Natural 
#define NOTE_D4  294  // Ré 
#define NOTE_B4  494  // Si 
#define NOTE_F4 349 // Fá 

const int pinoBuzzer = 25;

void setup() {
  pinMode(pinoBuzzer, OUTPUT);
}

void loop() {

  // --- PARTE 1: Mi - Lá - Sol ---
  tone(pinoBuzzer, NOTE_E3, 500);
  delay(500);
  noTone(pinoBuzzer);
  delay(50); // Intervalo extra

  tone(pinoBuzzer, NOTE_A4, 250);
  delay(250);
  noTone(pinoBuzzer);
  delay(50); // Intervalo extra

  tone(pinoBuzzer, NOTE_G4, 600);
  delay(500);
  noTone(pinoBuzzer);

  delay(1000); // PAUSA LONGA

  // --- PARTE 2: Mi - Fá# - Sol ---
  tone(pinoBuzzer, NOTE_E3, 500);
  delay(500);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_FS4, 250); // Fá Sustenido
  delay(250);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_G4, 600);
  delay(500);
  noTone(pinoBuzzer);

  delay(1000); // PAUSA LONGA

  // --- PARTE 3: Mi - Dó# - Sol ---
  tone(pinoBuzzer, NOTE_E3, 500);
  delay(500);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_CS4, 250); // Dó Sustenido
  delay(250);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_G4, 600);
  delay(500);
  noTone(pinoBuzzer);

  delay(1000); // PAUSA LONGA

  // --- PARTE 4: Mi - Dó Natural - Sol ---
  tone(pinoBuzzer, NOTE_E3, 500);
  delay(500);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_C4, 250); // Dó Natural
  delay(250);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_G4, 600);
  delay(500);
  noTone(pinoBuzzer);

  delay(100); // Pausa menor para emendar o final

  // --- FINAL: Ré - Lá - Si ---
  tone(pinoBuzzer, NOTE_D4, 250);
  delay(250);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_A4, 250);
  delay(250);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_B4, 250); // Si
  delay(250);
  noTone(pinoBuzzer);

  delay(50); // Fim da primeira parte 

   // --- PARTE 1: Mi - Lá - Sol ---
  tone(pinoBuzzer, NOTE_E3, 500);
  delay(500);
  noTone(pinoBuzzer);
  delay(50); // Intervalo extra

  tone(pinoBuzzer, NOTE_A4, 250);
  delay(250);
  noTone(pinoBuzzer);
  delay(50); // Intervalo extra

  tone(pinoBuzzer, NOTE_G4, 600);
  delay(500);
  noTone(pinoBuzzer);

  delay(1000); // PAUSA LONGA

  // --- PARTE 2: Mi - Fá# - Sol ---
  tone(pinoBuzzer, NOTE_E3, 500);
  delay(500);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_FS4, 250); // Fá Sustenido
  delay(250);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_G4, 600);
  delay(500);
  noTone(pinoBuzzer);

  delay(1000); // PAUSA LONGA

  // --- PARTE 3: Mi - Dó# - Sol ---
  tone(pinoBuzzer, NOTE_E3, 500);
  delay(500);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_CS4, 250); // Dó Sustenido
  delay(250);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_G4, 600);
  delay(500);
  noTone(pinoBuzzer);

  delay(1000); // PAUSA LONGA

  // --- PARTE 4: Mi - Dó Natural - Sol ---
  tone(pinoBuzzer, NOTE_E3, 500);
  delay(500);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_C4, 250); // Dó Natural
  delay(250);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_G4, 600);
  delay(500);
  noTone(pinoBuzzer);

  delay(100); // Pausa menor para emendar o final

  // --- FINAL: Fá - Lá - Si ---
  tone(pinoBuzzer, NOTE_F4, 250);
  delay(250);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_A4, 250);
  delay(250);
  noTone(pinoBuzzer);
  delay(50);

  tone(pinoBuzzer, NOTE_B4, 250); // Si
  delay(250);
  noTone(pinoBuzzer);

  delay(50); // Fim do loop
}
```
