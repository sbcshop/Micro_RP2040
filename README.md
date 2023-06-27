# Micro_RP2040
<img src="https://cdn.shopify.com/s/files/1/1217/2104/files/banner1.png?v=1687787715">
Introducing the Micro RP2040 - a small and compact version of the popular Raspberry Pi Pico. This github includes Micro RP2040 Hardware Details and resources.

With 23 multifunction GPIO pins and a Type-C port, the Micro RP2040 has all the functionality of the Raspberry Pi Pico but in a smaller size. With its breadboard-friendly design, you can easily integrate it into your prototyping setup and explore endless possibilities for creating interactive and innovative projects.

<img src="https://github.com/sbcshop/Micro_RP2040/blob/main/Images/mirco%20rp2040%20breadboard.jpg" width = "288" height="264" >

In short, the Micro RP2040 is a versatile and powerful microcontroller that packs all the features of the Raspberry Pi Pico into a smaller and more compact form factor. Whether you're building a robot, controlling a smart home device, or experimenting with electronics, the Micro RP2040 is the perfect tool for the job.

### Features:
- Small and compact form factor, making it perfect for embedded projects and applications.
- Features the powerful RP2040 microcontroller, which provides a dual-core Arm Cortex-M0+ processor and 264KB of SRAM.
- Includes 23 multifunction GPIO pins, giving you plenty of options for connecting sensors, displays, and other peripherals.
- Comes with a Type-C port for easy connectivity and data transfer.
- Supports a wide range of programming languages and development environments, including C, C++, MicroPython and CircuitPython.
- Includes all the standard features of the Raspberry Pi Pico, including support for hardware and software PWM, I2C, SPI, and UART communications.
- Offers exceptional value for money, making it an ideal choice for hobbyists, students, and professionals alike.
- Breadboard compatible, making it versatile and suitable for incorporating into a wide range of DIY electronics projects
- The board includes 2MB of onboard Flash memory, which can be used to store programs and data. This provides plenty of space for complex applications and projects.
  
### Specifications:
- RP2040 microcontroller which is dual-core Arm Cortex-M0+ processor
- Operating Voltage 3.3V/5V, GPIO Pins operating voltage 3.3V
- 22 Multipurpose GPIOs 
- PWM, I2C, SPI, and UART communications protocol 
- Type C for power, Drag & Drop Programming 
- 2MB of onboard Flash memory
- Cross platform development and multiple programming language support
- Operating temperature: -40°~+85°
- Weight: 4g (0.2oz)


## Micro RP2040 GPIO Breakout:
<img src="https://github.com/sbcshop/Micro_RP2040/blob/main/Images/Gpio_breakout.jpg">

22 Multifunction GPIO pin breakout available, so easily use to interface external peripheral.
At the bottom Serial Wire Debug (SWD) is a standard interface on Cortex-M-based microcontrollers exposed, which can be use for debugging purpose.

### Pinout :
<img src="https://github.com/sbcshop/Micro_RP2040/blob/main/Images/PINOUT.jpg">

1. **Type-C Connector** : A USB Type-C connector is included on the board, which allows for easy connection to a computer or power source.
2. **RP2040 MCU (Dual-core Arm Cortex M0+ processor)** : The RP2040 is a powerful microcontroller unit that features dual-core Arm Cortex M0+ processors. It has a clock speed of up to 133 MHz and includes a variety of built-in peripherals and interfaces, including USB, SPI, I2C, and UART.
3. **BOOTSEL Button** : The board features a boot button, which can be used to enter the bootloader mode when the board is powered on. This allows for easy programming of the RP2040 MCU using the Raspberry Pi Pico's USB port.

## How to install Boot Firmware 
- Push and hold the BOOTSEL button and plug your Pico into the USB port of your Raspberry Pi or other computer. Release the BOOTSEL button after your Pico is connected.

  <img src="https://github.com/sbcshop/Micro_RP2040/blob/main/Images/bootmode_step.gif"  width= "635" height= "321">
  
- It will mount as a Mass Storage Device called RPI-RP2.
- Drag and drop the [MicroPython UF2 file](https://github.com/sbcshop/Micro_RP2040/blob/main/firmware_pico.uf2) onto the RPI-RP2 volume. Your Pico will reboot. You are now running MicroPython.

  <img src="https://github.com/sbcshop/Micro_RP2040/blob/main/Images/firmware_install.gif"  width= "720" height= "382">

## Testing
-  Download and install [Thonny IDE](https://thonny.org/) from official site.
-  Write simple code in Thonny IDE, select MicroPython board with suitable com port (maybe different in your case). Then click on run button
   
   <img src="https://github.com/sbcshop/Micro_RP2040/blob/main/Images/test_run_code.gif" width= "720" height= "382">
  
## Resources
  * [Schematic](https://github.com/sbcshop/Micro_RP2040/blob/main/Design%20Data/SCH%20Micro%20RP2040.pdf)
  * [PCB 3D File](https://github.com/sbcshop/Micro_RP2040/blob/main/Mechanical%20Data/3D%20PCB%20Micro%20RP2040.pdf)
  * [Step File](https://github.com/sbcshop/Micro_RP2040/blob/main/Mechanical%20Data/STEP.step)
  * [MicroPython getting started for RPi Pico](https://docs.micropython.org/en/latest/rp2/quickref.html)
  * [Pico Getting Started](https://projects.raspberrypi.org/en/projects/getting-started-with-the-pico)


## Related Products
  * [BME Breakout](https://shop.sb-components.co.uk/products/bme280-breakout-temperature-pressure-humidity-sensor?_pos=1&_sid=f54b3965c&_ss=r) 
 
   ![BME-breakout](https://cdn.shopify.com/s/files/1/1217/2104/files/Untitled-1_cd2b11f7-ca81-4dd8-87d8-f84c0d1660fd.jpg?v=1686831477&width=300)   

  * [MicroSD Card Breakout](https://shop.sb-components.co.uk/products/sd-card-breakout?_pos=1&_sid=be5068526&_ss=r) 
 
   ![SDCardBreakout](https://cdn.shopify.com/s/files/1/1217/2104/products/SDCardBreakout.png?v=1643699904&width=300) 

  * [1.3" LCD Breakout](https://shop.sb-components.co.uk/products/1-3-lcd-breakout?_pos=2&_sid=23eee937e&_ss=r) 
 
   ![1.3" LCD Breakout](https://cdn.shopify.com/s/files/1/1217/2104/products/01_1_a486ba53-c02b-4491-b110-a9b64736ad39.png?v=1677241189&width=300) 


## Product License

This is ***open source*** product. Kindly check LICENSE.md file for more information.

Please contact support@sb-components.co.uk for technical support.
<p align="center">
  <img width="360" height="100" src="https://cdn.shopify.com/s/files/1/1217/2104/files/Logo_sb_component_3.png?v=1666086771&width=300">
</p>
