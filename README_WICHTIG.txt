Der AP Mode scheint nicht richtig zu funktionieren.
Lösung: SSID und PW im Code eintragen, builden und aufspielen. 
Dann geht es.
Liegt möglicherweise noch an der Kompatibilität zum ESP32-C6.

----

das eigene Boardfile z.B. board = esp32-c6-myBoard  
muss unter
C:/Users/<USERNAME>/.platformio/platforms/espressif32<@COMMIT>/boards
abgelegt sein