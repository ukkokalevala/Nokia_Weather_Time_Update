Pin Connections:

   Pin Connections:

    Pin 1 (VCC) to 3.3V on Wemos D1
    Pin 2 (GND) to GND on Wemos D1
    Pin 3 (SCE) to D6 (Chip Select)
    Pin 4 (RST) to D7 (Reset)
    Pin 5 (D/C) to D5 (Data/Command)
    Pin 6 (DN/MOSI) to D2 (SPI MOSI)
    Pin 7 (SCLK) to D1 (SPI Clock)
    Pin 8 (LED) to 3.3V (or through a resistor for backlight control).

I have incorporate both OpenWeather data and NTP-based date and time display in this project, we can use the NTPClient library to fetch the time. the code integrates NTP time display along with weather data from OpenWeather:
