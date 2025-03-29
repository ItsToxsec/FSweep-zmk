this is my code to make nrf52840 with 1.3 inch screen work as a dongle with ferris sweep

what you need
nrf52840 pro micro
1.3 inch oled screen with i2c connect

Step 1 connect the screen to the controller, using pro micro pinout to identify sda and scl pin out ( SDA=P0.17, SCL=P0.20)
Step 2 Fork my repo 
Step 3 Enable Actions, then build the firmware
Step 4 download the firmware zip file, unzip.
Step 5 press reset on NRF52840 twice to make it go to boot mode. A new folder will appear
Step 6 copy uf2 file into the folder ( center dongle, peripheral L-R)


If you don't have the dongle yet, you can copy left center to make sweep run without dongle.





