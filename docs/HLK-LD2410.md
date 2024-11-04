# HLK-LD2410 24GHz mmWave presence sensor

??? failure "This feature is not included in precompiled binaries"  

    When [compiling your build](Compile-your-build) add the following to `user_config_override.h`:
    ```c++
    #ifndef USE_LD2410 
    #define USE_LD2410               
    #endif
    ```

![HLK-LD2410(B)](_media/devices/HLK/LD2410/board_2410b.jpg)
![HLK-LD2410C](_media/devices/HLK/LD2410/board_2410c.png)

### Wiring
![HLK-LD2410-wiring](_media/devices/HLK/LD2410/2410_wiring.png)

| HLK-LD2410(B,C)  | ESP |
|---|---|
|GND   |GND   
|VCC   | 5V
|TX   | GPIOx
|RX   | GPIOy
|OUT    | GPIOz

