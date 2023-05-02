# InstructionFirmware
Instruction Firmware Atmega328P USBASP, adapter ISP


### Step 1 - Connect the programmer to the computer.
### Step 2 - Download "Zadig".
2. Download "Zadig" https://zadig.akeo.ie/ <br>
    2.1. Open the program and select "USBASP" from the list.<br>
    ![zadig-0](img/zadig-0.png)<br>
    2.2. If USBASP is not in the list, go to the Options -> List All Device tab.<br>
    ![zadig-2](img/zadig-2.png)<br>
    2.3. Select Target driver libusbK and click on the button "Upgrade Driver".<br>
    ![zadig-1](img/zadig-1.png)<br>
    2.4. Upon completion, the message "The driver was installed successfully" will appear.<br>
    ![zadig-3](img/zadig-3.png)<br>
### Step 3 - Download "ProgISP".
3. Download and unpack the archive "progisp172.rar".<br>
    3.1. Open the program "progisp.exe" and select "ATmega328P".<br>
    ![progisp-0](img/progisp-0.png)<br>
    3.2. Make sure "PRG ISP" is active.<br>
    ![progisp-1](img/progisp-1.png)<br>
    3.3. Click on the window (look image).<br>
    ![progisp-2](img/progisp-2.png)<br>
    3.4. Set the fuses as in the picture and click on the "Write" button.<br>
    ![progisp-3](img/progisp-3.png)<br>
    3.5. Check the box next to "Program Flash".<br>
    3.6. Set File -> Load Flash. Select "firmware.hex" file.<br>
    3.7. Click the button "Auto" for download firmware.
   
    
