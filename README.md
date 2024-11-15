# Earring-November-2024

There are 6 lines that control the charlieplexed leds.
Namely, NETLED01, NETLED02, NETLED03, NETLED04, NETLED05, NETLED06.
This is how the leds are connected:
- LED01 has his positive (+) side connected to NETLED01, while negative (-) to NETLED02
- LED02 has his positive (+) side connected to NETLED02, while negative (-) to NETLED01
- LED03 has his positive (+) side connected to NETLED02, while negative (-) to NETLED03
- LED04 has his positive (+) side connected to NETLED03, while negative (-) to NETLED02
- LED05 has his positive (+) side connected to NETLED03, while negative (-) to NETLED04
- LED06 has his positive (+) side connected to NETLED04, while negative (-) to NETLED03
- LED07 has his positive (+) side connected to NETLED04, while negative (-) to NETLED05
- LED08 has his positive (+) side connected to NETLED05, while negative (-) to NETLED04
- LED09 has his positive (+) side connected to NETLED05, while negative (-) to NETLED06
- LED10 has his positive (+) side connected to NETLED06, while negative (-) to NETLED05
- LED11 has his positive (+) side connected to NETLED01, while negative (-) to NETLED03
- LED12 has his positive (+) side connected to NETLED03, while negative (-) to NETLED01
- LED13 has his positive (+) side connected to NETLED02, while negative (-) to NETLED04
- LED14 has his positive (+) side connected to NETLED04, while negative (-) to NETLED02
- LED15 has his positive (+) side connected to NETLED03, while negative (-) to NETLED05
- LED16 has his positive (+) side connected to NETLED05, while negative (-) to NETLED03
- LED17 has his positive (+) side connected to NETLED04, while negative (-) to NETLED06
- LED18 has his positive (+) side connected to NETLED06, while negative (-) to NETLED04
- LED19 has his positive (+) side connected to NETLED01, while negative (-) to NETLED04
- LED20 has his positive (+) side connected to NETLED04, while negative (-) to NETLED01
- LED21 has his positive (+) side connected to NETLED02, while negative (-) to NETLED05
- LED22 has his positive (+) side connected to NETLED05, while negative (-) to NETLED02
- LED23 has his positive (+) side connected to NETLED03, while negative (-) to NETLED06
- LED24 has his positive (+) side connected to NETLED06, while negative (-) to NETLED03
- LED25 has his positive (+) side connected to NETLED01, while negative (-) to NETLED04
- LED26 has his positive (+) side connected to NETLED04, while negative (-) to NETLED01
- LED27 has his positive (+) side connected to NETLED02, while negative (-) to NETLED06
- LED28 has his positive (+) side connected to NETLED06, while negative (-) to NETLED02
- LED29 has his positive (+) side connected to NETLED01, while negative (-) to NETLED06
- LED30 has his positive (+) side connected to NETLED06, while negative (-) to NETLED01

- NETLED01 is connected to Pin PA3 (9) of the microcontroller (STM32L031G6U6)
- NETLED02 is connected to Pin PA8 (18) of the microcontroller
- NETLED03 is connected to Pin PA9 (19) of the microcontroller
- NETLED04 is connected to Pin PA10 (20) of the microcontroller
- NETLED05 is connected to Pin PB0 (14) of the microcontroller
- NETLED06 is connected to Pin PA7 (13) of the microcontroller

