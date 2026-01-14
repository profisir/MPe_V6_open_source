# MPeV7 - DIY ebike computer
FORK of #MPeV6 (Atmega328p)

EN: More info https://bikel.pl/en/mpe-computer-for-e-bike/
PL: Więcej informacji: https://bikel.pl/komputer-mpe-do-e-bike/

#MPE_BT 6.14.
- Nowa Apka Android 2in1 Licznik + Menu - MPeV6_BT_614.apk < kompatybilna z org Firmware 6.10.
Do pobrania tu:
https://github.com/profisir/MPe_V6_open_source/blob/master/smartphone_app/MPeV6_BT_614.apk

###

#MPeV7 - FORK DIY ebike computer.
- Atmega328p / ESP32.
  
- Micro moduł PCB ESP32 do instalacji w środku Kontrolera.
  ESP32s3_ZERO WiFi + externalBT_06 .
  + ADS1115 - 4 wejścia Analogowe
  + INA226 - Pomiar prądu na "drucie" pomiarowym w kontrolerze
  + komunikacja Serial Kontroler <> ESP <> LCD dla Prot#2:
    - zmiana trybu wsp. w LCD zmienia tryb w MPe.
    - MPe ustawia nastawy w kontrolerze po zasilaniu.
  + MPE_BT > 6.14 
  + Wyłączony i2c OLED i możliwość wyłączenia Przycisków. 
  + Tryb LEGAL WalkAssist - manetka gazu działa w trybie LEGAL do 7km/h (ustawialne ON/OFF + Limit manetki).
  + PAS_DIR - Czujnik Tensometr z PAS dostaje wejście DIR - 0 / 1 aktywujące.
  + EBRAKE STOP LIGHT - wyjście do sterowania tranzystorem Lampą STOPu.
  + ENABLE HIDDEN LEGAL - SHORT TO GND - ACTIVATE FULL POWER - szybkie wejście np z kontaktronu na magnes DEZaktywujące tryb LEGAL. 
  + Hebel + DN_Button - Dezaktywacja trybu LEGAL.
  + Duotts C29 V2 Slow Start FIX , z silnika HALL SPD in > <ESP> > Kontroler Hal SPD in 


