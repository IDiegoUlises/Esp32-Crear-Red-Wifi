# Esp32-Crear-Red-Wifi

```c++
#include <WiFi.h>

const char* ssid     = "Hogar"; //Nombre de la red
const char* password = "password"; //Null para red abierta

void setup()
{
    WiFi.mode(WIFI_AP); //Establece el modo de access point
    WiFi.softAP(ssid, password); //Inicia la red
}

void loop()
{
  
}
```

### Telefono
<img src="https://github.com/IDiegoUlises/Esp32-Crear-Red-Wifi/blob/main/Images/Red.jpg" width="300" height="500" />
