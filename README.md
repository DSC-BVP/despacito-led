# despacito-led
blinking led

this is the project which shows how led blinks on songs.
first of all u need to remember these points.

  1.You should have an arduino, any board type- no restrictions
  
  2.leds of 3 colors.
  
  3.breadboard.
  
  4.jumper wires- mostly male to male.
  
  5.resistors(not necessary, its as per ur wish)
  
  6.Arduino IDE.
  
  7.processing software. - link below.
    (https://processing.org/download/), download as per ur system reqirement
  
  8.Two arduino libraries.(links given respectively)
      1. Minim (http://code.compartmental.net/tools/minim/)
      2. processing-arduino(http://playground.arduino.cc/Interfacing/Processing)
      
      
      Import both the libraries to the Arduino IDE.
  
these were the pre-requisite.Now lets come to the steps.
    
    1.first of all open arduino IDE., then go to file > examples > firmata > standard firmata.
    
    2.upload the code of standard firmata into your arduino board.
    
    3.now make a folder with the name- BeatWrite , i recommend you to make the folder on the desktop.
    
    4.Now copy the two file- 1.BeatWrite.pde, 2.BeatListener.pde to the made folder.
    
    5. Now create another folder name- "data" , inside the same folder, the data folder will contain the song which you have to play.
    
    6. now open Beatwriter.pde file in processing.
    
    7.now you will get a line "song = minim.loadFile("xyz", 2048);"
      instead of xyz write the name of the song in the data folder ending with ".mp3"
    
    8.you need not change the BeatListener file.
    
    9.now run the code and see the magic...
    
    
## video links
### 1. https://drive.google.com/open?id=1Bagyc5QlbsTCEx_U3ZXNI5qulNKZOyMh
### 2. https://drive.google.com/open?id=1BQcawZ-JhjW1n7gwdFCqgCt6dAYihXyZ
