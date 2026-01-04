Using a 555 timer, a vairiable resistor and some fixed resistors, I made a clock signal that pulses every second (1hz) to 1000 times a second (1khz).


I have made a 16 bit counter that counts up to 65536 (or 2^16) as my logisim ROM can store 64k x 16 bit instructions. When I branch I can only access the first 128 (2^8 (because of using an 8 bit ram in logisim)) but I don't think I'll be using anywhere near that many instructions, and even if I do then I just need to make sure I don't need to branch to them.
<img width="1719" height="1284" alt="image" src="https://github.com/user-attachments/assets/0f0609e7-ca4b-4fe1-a587-350eb012afe9" />


This is a square wave which shows the peaks as logic 1 and the bottom as logic 0, the rising edge is the veritcal line from the bottom to the peak and falling edge is the vertical line from the peak to the bottom.
<img width="855" height="1143" alt="image" src="https://github.com/user-attachments/assets/683a4a85-d127-4d63-86ea-3e8f19b69b28" />
