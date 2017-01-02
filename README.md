119# Smoothieboard
Ein neues Steuerboard für meinen 3D Drucker


Es gibt noch andere Modifikatoren für Pins:

Beispiel: my_pin_name                     [ 19!]     Hier ist Pin 19 invertiert

Alle Optionen
*   !	Invert-pin
*   O set Stift Drain zu öffnen
*   ^ Stellen Sie den Stift nach oben ziehen
*   v Stellen Sie den Stift nach unten ziehen
*   - keine Pull-up zu setzen
*   @ einstellen Repeater-Modus




* M119  ausgabe der Hommingschalter
* M190 S{print_bed_temperature} ;Uncomment to add your own bed temperature line  
* M109 S{print_temperature} ;Uncomment to add your own temperature line  
* G21        ;metric values  
* G90        ;absolute positioning  
* M82        ;set extruder to absolute mode  
* M107       ;start with the fan off  
* G28        ;home the printer head  
* G29        ; auto bed leveling  
* G1 Z15.0 F{travel_speed} ;move the platform down 15mm  
* G92 E0                  ;zero the extruded length  
* G1 F200 E3              ;extrude 3mm of feed stock (prime the printer head)  
* G92 E0                  ;zero the extruded length again  
* G1 F{travel_speed}  ;Put printing message on LCD screen  
* M117 ;Printing...  
