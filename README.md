# 150W Elektronische Last von DIYMORE.CC

Die soll eine übersetzte und geteste Anleitung werden.

## Lieferumfang

[150W LDM Digital Electronic Load Discharge Capacity Tester USB Voltmeter Ammeter](https://www.diymore.cc/products/150w-ldm-digital-electronic-load-discharge-capacity-tester-usb-voltmeter-ammeter?_pos=3&_sid=74f1b38ee&_ss=r)

1 x Elektronische Last _Bild von Last !!_

1 x Steckernetzteil 12V 2A mit US auf EURO Adapter (Nicht verwenden, da bei nicht richtig gestecktem Netzteil die Kontakte berührt werden können und die Netzspannung berührt werden kann.) _Bild von Netzteil mit Finger !!_

1 x Einfache Anleitung

## Parameter

Größe |  Bereich | Auflösung
--- |  --- | ---
Spannung |  0 bis 150V  | 0,05V
Strom    |  maximal 10A | 0,05A
Leistung (Aufnahme) |  0 bis 150W  | 0,01W
Leistung (Messbereich) | 0 bis 2999.9W | 0,01W
Kapazität | 0 bis 999.999Ah | 0,001Ah
Energie | 0 bis 99999.9Wh | 0,01Wh
Impedenz | 0 bis 999.9Ω | 0,01Ω
Temperatur | 0 bis 99°C | 1°C  
Dauer | 999:59:59 (h:min:s)| 1s

**Die Leistung ist auf 150W begrenzt. Ein Strom von 10A ist nur über die Schraubanschlüsse erlaubt.**  
Die Zeit wird erst ab einer Leistung von 0,5W begonnen.

![Arbeitsbereich][Diagramm_Arbeitsbereich]

## Anschlüsse

Versorgung mit 6 - 12Vdc (Minus außen, plus innen) 

**Messanschlüsse**

1. Schraubklemmen (bis 10A)
2. Hohlstecker 5,5mm (Innen 2,1mm) (Je nach Typ bis 5A)  
3. USB Micro  
4. USB-C  
5. USB-Mini  
6. USB-A  

**weitere Anschlüsse**

Serielle Schnittstelle 3,3V Pegel, Baudrate?, Funktion? 

## Bedienelemte

### Taste

1. einfache Betätigung: Menüseite weiter blättern  
2. Auf den Seiten 2 bis 4  
  * lange (_Dauer??_) Betätigung: löschte alle Aufzeichungen  
  * doppelte Betätigung: Kapazität auf 0 Ah setzen  
  * dreimal betätigen: Energie auf 0 Wh setzen  
  * viermal betätigen: Messdauer auf 00:00:00 setzen  
  * siebenmal betätigen ohne Last: Strom abnullen (kalibireren)
  * zehnmal betätigen: Werksreset aller Parameter  
3. Auf den Seiten 6, 7, 9, 11 und 13 
  * zweimal betätigen: Wert erhöhen
  * dreimal betätigen: Wert reduzieren
  * festhalter der Taste führt die letzte Funktion (erhöhen oder reduzieren) kontinuierlich durch

### Potentiometer
Die Stromeinstellung erfolgt mit den Potentiometern grob (coarse) und fein (fine). Beim Drehen gegen den Uhrzeigersinn sinkt der Strom bis auf 0A. Durch Drehen im Uhrzeigersinn wird der Strom auf bis zu 10A erhöht. Der Maximalwert ist unabhängig von der eingestellten Stromgrenze, so kann man bei kleinen Strömen schnell über die eingestellte Begrenzung erreichen.  

## Menueseite und Funktion der Taste

1. Begrüßung _Bild einfügen !!_
   
2. Übersicht 1 _Bild einfügen !!_

3. Übersicht 2 _Bild einfügen !!_

4. Englische Seite mit phy. Größen _Bild einfügen !!_

5. Chinesische Seite mit phy. Größen _Bild einfügen !!_

6. Hintergrundbeleuchtung _Bild einfügen !!_  
   Dauer der Beleuchtung nach dem letzten Tastendruck:  
   1. Aus (OFF)  
   2. 01 - 59s  
   3. Dauer ein (ON)  

7. Spannungsobergrenze _Bild einfügen !!_  
   &gt; 150V
   
8. Überspannungswarnung **wird bei Überschreiten der Grenze von Seite 7 angezeigt**  
   &gt; 150V!  
   
9. Spannungsuntergrenze _Bild einfügen !!_  
   &lt; 5.00V  
   z.B. Tiefendladungsgrenze bei Akkumulatoren  
   
10. Unterspannungswarnung **wird bei Unterschreiten der Grenze von Seite 9 angezeigt**    
   &lt; 5.00V!  
   
11. Stromobergrenze _Bild einfügen !!_  
   &gt; 10,0A  

12. Überstromwarnung **wird bei Überschreiten der Grenze von Seite 11 angezeigt**  
   &gt; 10,0A!  
   
13. Leistungsbegrenzung _Bild einfügen !!_  
   &gt; 150W  
   
14. Leistungswarnung **wird bei Überschreiten der Grenze von Seite 13 angezeigt**  
   &gt; 150W!  
    
## Arbeitsschritte

1. Die elektronische Last mit Spannung versorgen. Bei der Potentiometer auf 0 drehen (gegen den Uhrzeigersinn).  
2. Die Taste lange betätigen um die gespeicherten Daten zu löschen.  
3. Grenzwerte kontrollieren bzw. einstellen.  
4. Die zutestende Quelle anschließen und die Potentiometer im Uhrzeigersinn auf den gewünschten Endladestrom einstellen. (Erst grob dann fein)  
5. Beim Erreichen eines Grenzwertes wird die Last abgeschaltet und die Messung beendet.  


[Diagramm_Arbeitsbereich]:https://github.com/kirk-loeten/150W-Elektronische-Last-von-DM/blob/85e13ad64ef386654d56cab99040c5b73d60fa3f/bilder/ElektronischeLast.png
