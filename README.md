# Multi-sport tracing app 
A open source multi-sport tracing app uses IMU-based sensors to trace the movement of any board (surf, kiteboard, snowboard, skatebaord...), providing the user with live feedback on inportant performance parameters. It can be used by coaches or athletes.
## HOW
The app is open source and free, and connects to commercial off-the-shelf motion sport tracking sensors (such as Movesense).
This solves a couple of issues most such sensors had in the past.
- No propriotory sensor development costs
- Increased user numbers, due to the use for multiple board sports
- No business case that needs to earn a short-term ROI
- Programmers passionate about difference board sports can develop different versions of the app, or modes within the app.
The app should be able to measure:
- Board speed
- Trick type
- Jump height
- Jump distance
- Air time
- Foot timing and more...
- Include social element, which ads to more fun :-)

## SPECIAL REQUIREMENTS
- Code needs to be as modular as possible, so that it can be shared between the different sports
- Coded mostly in Flutter, to enable deployment on various operating systems.
- Use AI to continuously learn and get better
- Give useful feedback to the users
- Protect user data as much as possible

## BUSINESS MODEL
Users buy sensors directly from commercial suppliers. Find solutions enabling the app to always stay free, while generating enough funds to support continous improvement.
- Sport brands sponsor certain spots
- Sell clips to fix the sensor to the boards.
- Show classic adds
- Earn money via a coaching or premium platform

## SENSORS
Aim to support as many commercial sensors as possible, starting with those providing easy APIs and SDKs.

### Movesense
Movesense is an established sports sensor with a well-documented API and integrations (Android, iOS, Flutter & Unity)
It is a battery powered device that incorporates low power sensor components with Bluetooth Low Energy (BLE) enabled Micro Controller Unit (MCU). Currently commercially available Movesense Sensor is based on Nordic Semiconductor's nRF52 BLE chip fitted with 9-axis motion sensor, heart rate unit, extra memory and more...
![Move sense sensor](https://www.movesense.com/wp-content/uploads/2017/05/movesense-front1000px-296x300.png)
   
https://www.movesense.com/technology/
