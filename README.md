# EchoClock
;A clock that talks. 
..........................................................................
Een toegankelijk auditief tijdsapparaat voor blinden en slechtzienden

EchoClock is een open-source hulpmiddel dat met één druk op de knop de huidige tijd hoorbaar uitspreekt, zonder internet en zonder visuele bediening.
Ontwikkeld als onderdeel van een Research & Development project voor de opleiding HBO-ICT op Hogeschool Windesheim.

Doelgroep:
* blinden
* slechtzienden
* situaties waar schermen of spraakassistenten onhandig zijn
* Zorg

🎯 Features
* Tijd wordt hardop uitgesproken via DFPlayer Mini
* Zeer nauwkeurige tijd dankzij DS3231 RTC
* Eén-knops bediening
* Werkt volledig offline
* Laadbaar via LiPo + TP4056
* Compact & draagbaar

🛠️ Hardware componenten
* Component	-> Functie
* ESP32-C3 Super mini ->	Microcontroller
* DFPlayer -> Mini	Audio playback
* DS3231 RTC ->	Tijdregistratie
* 3.7V LiPo	-> Voeding
* TP4056	-> Batterijlader
* Speaker	-> Audio output
* Drukknop ->	Input
