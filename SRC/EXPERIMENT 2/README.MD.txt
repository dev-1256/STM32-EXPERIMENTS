# Experiment 02 — Push Button and LED Interfacing

## Aim
To interface a push button as digital input with an LED as digital output for simple sensor-actuator control.

## Apparatus
- STM32 Discovery Kit
- STM32CubeIDE
- STM32CubeMX

## Theory
GPIO input pins can detect button states and control output devices such as LEDs.

## Procedure
1. Configure button pin as GPIO_Input.
2. Configure LED pin as GPIO_Output.
3. Read button state using HAL_GPIO_ReadPin().
4. Turn LED ON/OFF based on button press.

## Code Snippet

```c
if(HAL_GPIO_ReadPin(GPIOC, GPIO_PIN_13))
{
    HAL_GPIO_WritePin(GPIOA, GPIO_PIN_5, GPIO_PIN_SET);
}
```

## Result
LED responded correctly to push button input.

## Output
![Button LED](../../images/button_led_output.jpg)