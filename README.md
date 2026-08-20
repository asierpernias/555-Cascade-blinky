# 555-Cascade-blinky

## Description

## How it works
- The first 555 works in monostable mode, when it gets an extern pulse it generates an unique pulsation of a determined duration **t1**.
- The second 555 is in astable mode, so it generates a continued oscillation in a **f** , but in this case it stays off (reset) until it recieves the pulse from the first 555.
- At the end, what happens is that the monostable controls the reset pin **rst** of the astable. While the monostable is active the astable can oscillate freely and when it ends it cycle it sets the astable in reset so the oscillation is finished.

The practice result is that the when activating the circuit you don't give an only pulse but a rush within a determined **t1** and after it finishes without any external interaction.

## Link to the project
[Here it is!](https://www.falstad.com/s.php?s=5m3lyf)

## Screenshots
<img width="748" height="546" alt="image" src="https://github.com/user-attachments/assets/48bec81f-f0b0-499a-8483-9515467387dd" />
https://github.com/user-attachments/assets/fa1b637f-39d4-49fa-b3f9-551a6ba1491d

## License
This project is under **MIT** License. Read `LICENSE.txt` for more information. 

