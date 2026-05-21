# Experiment 01 — LED Blinking using GPIO

## Aim
To configure a GPIO pin as digital output and implement LED blinking to illustrate basic edge-node operation.

## Apparatus
- STM32 Discovery Kit
- STM32CubeIDE
- STM32CubeMX

## Theory
GPIO pins on STM32 microcontrollers can be configured as digital outputs to control LEDs and other external devices.

## Procedure
1. Open STM32CubeMX.
2. Configure onboard LED pin as GPIO_Output.
3. Generate project code.
4. Open project in STM32CubeIDE.
5. Use HAL_GPIO_TogglePin() inside while loop.
6. Build and flash code into STM32 board.

## Code Snippet

```c
HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_5);
HAL_Delay(500);
```

## Result
LED blinked successfully with fixed delay.

## Output
![LED Blink](../../images/led_blink_setup.jpg)