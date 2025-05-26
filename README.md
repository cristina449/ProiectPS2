# ProiectPS2
Se va afișa pe interfața serială (SerialMonitor) temperatura curentă citită de la un senzor de temperatura (LM35) și se va implementa controlul unui LED prin comenzi UART (ie: ‘A’ -> va aprinde LED-ul, ‘S’ -> va stinge LED-ul). 

Implementarea unei interfețe WEB folosind Flask (Python) prin care se vor putea vizualiza starea curentă a LED-ului și temperatura curentă. Interfața va permite de asemenea și controlul LED-ului de la distanță.

Trimiterea mesajelor din interfața WEB către microcontroller. Ultimele 10 mesaje vor fi stocate în memoria EEPROM. 

Detectarea inundațiilor și trimiterea unei notificări prin e-mail. Ultimele 10 evenimente vor fi stocate în EEPROM. Interfața WEB va permite ștergerea individuală a fiecărui eveniment.  

Implementarea interfeței WEB dezvoltată anterior în Cloud folosind Azure for Students.
