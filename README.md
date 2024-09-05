# Aula-sobre-RGB
RGB codigo desenvolvido para rodar cores.

// C++ code
//

#define R 2
#define G 5
#define B 6

void setup(){
  
  pinMode(R, OUTPUT);
  pinMode(G, OUTPUT);
  pinMode(B, OUTPUT);
  Serial.begin(9600);

}

void loop ()
  
{
  analogWrite(R, 55);
  analogWrite(G,127);
  analogWrite(B,0);
  Serial.println("Cor = Verde");
  delay(500);
  
  analogWrite(R, 255);
  analogWrite(G,0);
  analogWrite(B,0);
  Serial.println("Cor = Vermelho");
  delay(500);
  
  analogWrite(R, 100);
  analogWrite(G,255);
  analogWrite(B,200);
  Serial.println("Cor = Ciano");
  delay(500);
  
  analogWrite(R, 0);
  analogWrite(G,0);
  analogWrite(B,255);
  Serial.println("Cor = Azul");
  delay(500);
  
  analogWrite(R, 143);
  analogWrite(G,0);
  analogWrite(B,255);
  Serial.println("Cor = Rosa");
  delay(500);
  
  analogWrite(R, 230);
  analogWrite(G,70);
  analogWrite(B,110);
  Serial.println("Cor = Salmao");
  delay(500);
  
  analogWrite(R, 175);
  analogWrite(G,96);
  analogWrite(B,5);
  Serial.println("Cor = Laranja");
  delay(500);
  
  analogWrite(R,12);
  analogWrite(G,6);
  analogWrite(B,7);
  Serial.println("Cor = Cinza");
  delay(1000);
  
  
  
  
}
  
