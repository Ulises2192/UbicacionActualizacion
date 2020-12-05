# UbicacionActualizacion
En este ejemplo se realiza la solicitud de permisos de riesgo al usuario como lo son de la ubicación ya que utiliza el GPS para proporcionar las coordenadas geográficas del dispositivo.

Se obtiene la ubicación cada que se detecta una actualización del dispositivo por medio del GPS utilizando el permiso ACCES FINE LOCATION, esto cada 5 segundos.

En el archivo AndroidManifest.xml vrificar que estén los siguientes permisos:
```xml
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>
```
