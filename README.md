# AVALIA-O-01-Introdu-o-a-Computa-o
Este projeto apresenta uma solução tecnológica integrada para resolver um dos maiores gargalos da gestão hospitalar moderna: a lentidão e a falta de priorização no fluxo de exames diagnósticos. Através da união de Inteligência Artificial, Sistemas de Gestão Integrados e Hardware de Segurança. 


# Pseudocódigo


int Buzzer = 8;

void setup()
{
  pinMode(7, INPUT);
  pinMode(9, OUTPUT);
}

void loop()
{	
	ButtonState = digitalRead(7);
  if(ButtonState == HIGH){
    digitalWrite(9, HIGH);
    tone (Buzzer,150,1000);
    delay(1000);
  }
  else{
    digitalWrite(9, LOW);
  }
}
