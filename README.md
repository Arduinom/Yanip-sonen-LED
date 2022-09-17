// #Yanip-sonen-LED 
//ARDUİNOM 


void setup ()

{

pinMode (8, OUTPUT) ;   // 8. PİNİ GİRİŞ OLARAK TANIMLADIK

}
void loop ()
{
digitalWrite (8,HIGH);  // 8. PİNE GÜÇ VERDİK
delay(1000);           // 1 SANİYE BOYUNCA BEKLE
digitalWrite (8,LOW); // 8. PİNDEKİ GÜCÜ KAPATTIK
delay(1000);         // 1 SANİYE BOYUNCA BEKLE
}
