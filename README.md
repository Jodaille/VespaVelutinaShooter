# Vespa Velutina Shooter

## Objectif du PCB

- Détection acoustique du vol de frelon (micro sur ADS1115)
- Localisation du point le plus sombre de l'image prise avec la caméra de l'ESP32-Cam
- balayage de la zone avec le pan-tilt (2 servos controllés par PCA9685)
- détection du frelon par capteur laser (Dout sur ADS1115)
- collage du relais (PCA9685)
- ouverture electrovanne d'air comprimé
- sauvegarde de l'image sur la carte Sd
- projection d'une bille d'airsoft
- ré-enclenchement d'une bille


## Composants

- ESP-32 Cam
http://www.ai-thinker.com/pro_view-24.html

- Adafruit 16-Channel 12-bit PWM/Servo Driver - I2C interface - PCA9685
https://www.adafruit.com/product/815

- ADS1115 16-Bit ADC - 4 Channel with Programmable Gain Amplifier
https://www.adafruit.com/product/1085

- Waveshare Laser Sensor
https://www.waveshare.com/laser-sensor.htm

- Electret Microphone Amplifier - MAX9814 with Auto Gain Control
https://www.adafruit.com/product/1713

## Composants complémentaires

- horloge RTC: Adafruit DS3231 Precision RTC Breakout
https://www.adafruit.com/product/3013

Permttrait:
- Activation pendant la journée
- conserver l'heure des détections (recouper avec un enregistrement video par exemple)

# PCB prévisualisation

![Rendu 3D KiCad v0.3](ESP32-CAM-SHOOTER_0.3.png?raw=true "Rendu 3D KiCad du PCB v0.3")

![Rendu 3D KiCad v0.2](ESP32-CAM-SHOOTER_0.2.png?raw=true "Rendu 3D KiCad du PCB v0.2")


![Rendu 3D KiCad v0.1](ESP32-CAM-SHOOTER.png?raw=true "Rendu 3D KiCad du PCB")

# Projets liés/utilisés

Le détecteur de Bernard:

https://github.com/Barrois/Detecteur-ESP32-Cam-Blob-Detector

Enregistrements audio de Vespa Velutina:

https://github.com/Jodaille/VespaVelutinaAudioRecords

Merci à EloquentArduino pour son projet de détection dans l'image avec un ESP-32 !

https://github.com/eloquentarduino/EloquentArduino
