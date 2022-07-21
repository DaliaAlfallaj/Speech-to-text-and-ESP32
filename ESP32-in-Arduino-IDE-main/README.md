# ESP32-in-Arduino-IDE




# 1-Install Arduino IDE
###### Download [Arduino IDE](https://www.arduino.cc/en/software)

# 2-Installing ESP32 Board in Arduino IDE
 - ###   Open the Arduino IDE, go to the File menu. Select File > Preferences
<img width="623" alt="Screen Shot 2022-07-21 at 8 39 12 pm" src="https://user-images.githubusercontent.com/98902283/180285892-8e1d8dfe-6e74-4983-b66d-f1db82c9c587.png">


- ### Type in the following URL link inside the Additional Board Manager URLs textbox and click OK.
<img width="803" alt="Screen Shot 2022-07-21 at 8 41 29 pm" src="https://user-images.githubusercontent.com/98902283/180286791-5cff5456-7940-4580-aece-b6cfb9dedd23.png">


- ###  Open the board manage menu. Tools > Board > Boards Manager. Search for “esp32” and make sure it’s by espressif and click install.

<img width="809" alt="Screen Shot 2022-07-21 at 8 44 20 pm" src="https://user-images.githubusercontent.com/98902283/180286929-ea7cc661-b2e9-48a2-9f0f-d6a3c9507028.png">


# 3- Now open Arduino IDE 

- ### Open the tools menu Tools > Board > Your Board

<img width="939" alt="Screen Shot 2022-07-21 at 8 48 42 pm" src="https://user-images.githubusercontent.com/98902283/180287339-2dd78d51-ee95-4051-afd8-d034c43d09a6.png">

- ###  check the COM port and paste this example code in the editor.
<img width="880" alt="Screen Shot 2022-07-21 at 8 50 09 pm" src="https://user-images.githubusercontent.com/98902283/180287570-b2c58afd-8743-4eb4-9383-21e901cecef4.png">





#### Hit upload and press the BOOT button until Arduino IDE starts flashing the code and display log messages at the bottom window, then you can release the BOOT button.

  #### After flashing completion, the board will reset by hardware               command by order of the loader tool in Arduino IDE or you’ll have to restart the board yourself by pressing the EN button once
  
  
  
  
  # reference:
 [DeepBlue article](https://deepbluembedded.com/installing-esp32-arduino-ide-steps-guid)
  
 [Youtube video](https://www.youtube.com/watch?v=tkDJQkB9eEY)


