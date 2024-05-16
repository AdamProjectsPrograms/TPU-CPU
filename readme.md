# TPU CPU

## 1. Learn the Basic Functionality
This is a 10 bit CPU. The first two bits of an instruction are the instruction themselves:


**01**01011101
The rest of the bits are the operands:


01**01011101**
There are two operands for each instruction meaning one instruction takes 4 bits:


  *__OP1 _OP2*

01**01011101**

## 2. Modes: Input, Firmware, and output mode
*Why this CPU is special?* you might ask. That's beacuse it has three modes: Firmware Mode, Input Mode, Output mode
### 1. Firmware Mode
Firmware mode was made for changing the firmware or changing its appearance to devices. Similar to UnoJoy, You have
to make the computer think that its a controller.
### 2. Input Mode
Input makes the Digital pins input.
### 3. Output Mode
Output makes the Digital pins Output.