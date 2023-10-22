# EX-03 SIMULATION OF PUSHBUTTON-AND-LED INTERFACE WITH ARM CONTROLLER AND PROTEUS 
### Aim: 
To Interface a Digital output (LED) and Digital input (Pushbutton) to ARM development board , and simulate it in Proteus 
### Components required: 
- STM32 CUBE IDE, Proteus 8 simulator .
### Theory: 
The full form of an ARM is an advanced reduced instruction set computer (RISC) machine, and it is a 32-bit processor architecture expanded by ARM holdings. The applications of an ARM processor include several microcontrollers as well as processors. The architecture of an ARM processor was licensed by many corporations for designing ARM processor-based SoC products and CPUs. This allows the corporations to manufacture their products using ARM architecture. Likewise, all main semiconductor companies will make ARM-based SOCs such as Samsung, Atmel, TI etc.
What is an ARM7 Processor?
ARM7 processor is commonly used in embedded system applications. Also, it is a balance among classic as well as new-Cortex sequence. This processor is tremendous in finding the resources existing on the internet with excellence documentation offered by NXP Semiconductors. It suits completely for an apprentice to obtain in detail hardware & software design implementation.STM32F401xB STM32F401xC ARM® Cortex®-M4 32b MCU+FPU, 105 DMIPS, 256KB Flash/64KB RAM, 11 TIMs, 1 ADC, 11 comm.
interfaces Datasheet - production data Features
• Core: ARM® 32-bit Cortex®-M4 CPU with FPU, Adaptive real-time accelerator (ART Accelerator™) allowing 0-wait state execution from Flash memory, frequency up to 84 MHz, memory protection unit, 105 DMIPS/ 1.
25 DMIPS/MHz (Dhrystone 2.
1), and DSP instructions
• Memories – Up to 256 Kbytes of Flash memory – Up to 64 Kbytes of SRAM
### Procedure:
<table>
  <tr>
    <td width="30%">
      1. click on STM 32 CUBE IDE, the following screen will appear.
    </td>
    <td width="70%">
      <img src="https://user-images.githubusercontent.com/36288975/226189166-ac10578c-c059-40e7-8b80-9f84f64bf088.png">
    </td>
  </tr>
  <tr>
    <td width="50%">
      2. click on FILE, click on new stm 32 project.
    </td>
    <td width="50%">
  <img src="https://user-images.githubusercontent.com/36288975/226189215-2d13ebfb-507f-44fc-b772-02232e97c0e3.png">
    <img src="https://user-images.githubusercontent.com/36288975/226189230-bf2d90dd-9695-4aaf-b2a6-6d66454e81fc.png">
    </td>
  </tr>
  <tr>
    <td width="50%">
      3. select the target to be programmed  as shown below and click on next.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189280-ed5dcf1d-dd8d-43ae-815d-491085f4863b.png">
    </td>
  </tr>
   <tr>
    <td width="50%">
      4.select the program name.
    </td>
    <td >
      <img height=10% width=50% src="https://user-images.githubusercontent.com/36288975/226189316-09832a30-4d1a-4d4f-b8ad-2dc28f137711.png">
    </td>
  </tr>
     <tr>
    <td width="50%">
      5. corresponding ioc file will be generated automatically.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189378-3abbdee2-0df6-470f-a3cd-79c74e3d3ad8.png">
    </td>
  </tr>
    <tr>
    <td width="50%">
      6.select the appropriate pins as gipo, in or out, USART or required options and configure.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189403-f7179f1a-3eae-4637-826b-ab4ec35ba1e1.png">
    </td>
  </tr>
    <tr>
    <td width="50%">
      7.click on cntrl+S , automaticall C program will be generated.
    </td>
    <td width="50%">
<img src="https://user-images.githubusercontent.com/36288975/226189443-8b43451d-0b14-47e4-a20b-cc09c6ad8458.png">
    </td>
  </tr>
    <tr>
    <td width="50%">
      8. edit the program and as per required.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189461-a573e62f-a109-4631-a250-a20925758fe0.png">
    </td>
  </tr> 
  <tr>
    <td width="50%">
      9. Add necessary library files of LCD 16x2 , write the program and use project and build.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189554-3f7101ac-3f41-48fc-abc7-480bd6218dec.png">
    </td>
  </tr>   
  <tr>
    <td width="50%">
      10. once the project is bulild.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189577-c61cc1eb-3990-4968-8aa6-aefffc766b70.png">
    </td>
  </tr>  
  <tr>
    <td width="50%">
      11. click on debug option.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189625-37daa9a3-62e9-42b5-a5ce-2ac63345905b.png">
    </td>
  </tr>  
  
  <tr>
    <td width="50%">
      
  12.  Creating Proteus project and running the simulation.
  We are now at the last part of step by step guide on how to simulate STM32 project in Proteus.
13. Create a new Proteus project and place STM32F40xx i.e. the same MCU for which the project was created in STM32Cube IDE. 
14. After creation of the circuit as per requirement as shown below
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/233856847-32bea88a-565f-4e01-9c7e-4f7ed546ddf6.png">
    </td>
  </tr>  
  <tr>
    <td width="50%">
      15. Double click on the the MCU part to open settings. Next to the Program File option, give full path to the Hex file generated using STM32Cube IDE. Then set the external crystal frequency to 8M (i.e. 8 MHz). Click OK to save the changes.
https://engineeringxpert.com/wp-content/uploads/2022/04/26.png

16. click on debug and simulate using simulation as shown below 


    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/233856904-99eb708a-c907-4595-9025-c9dbd89b8879.png">
    </td>
  </tr>  
  
</table>

### STM 32 CUBE PROGRAM :
```
ROHIT JAIN D
212222230120
```

```C
#include "main.h"
#include "stdbool.h"
bool pb;

int main(void)
{
  HAL_Init();
  SystemClock_Config();
  MX_GPIO_Init();
  while (1)
  {
	  pb=HAL_GPIO_ReadPin(GPIOA, GPIO_PIN_0);
	  if(pb==0)
	  {
		  HAL_GPIO_WritePin(GPIOA, GPIO_PIN_1, GPIO_PIN_SET);
		  HAL_Delay(300);
		  HAL_GPIO_WritePin(GPIOA, GPIO_PIN_1, GPIO_PIN_RESET);
		  HAL_Delay(300);
	  }
	  else
	  {
		  HAL_GPIO_WritePin(GPIOA, GPIO_PIN_1, GPIO_PIN_RESET);
		  HAL_Delay(300);
	  }
  }
}
```
### Proteus layout :
<img height=60% width=85% src="https://github.com/ROHITJAIND/EX-03-SIMULATION-OF-PUSHBUTTON-AND-LED-WITH-PROTEUS/assets/118707073/73b7b7a5-6030-4e95-98d4-da718483baab">

### Result :
Interfacing a digital output and digital input  with ARM microcontroller are simulated in proteus and the results are verified.


