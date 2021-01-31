# Vespa Velutina Shooter

## Objectif du PCB

- Détection acoustique du vol de frelon (micro)
- Localisation du point le plus sombre de l'image prise avec la caméra de l'ESP-32
- balayage de la zone avec le pan-tilt (2 servos)
- détection du frelon par capteur laser
- collage du relais
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
