# Experiment 03 — USART Serial Communication

## Aim
To configure the USART peripheral for asynchronous serial transmission of text data to a terminal.

## Apparatus
- STM32 Discovery Kit
- STM32CubeIDE
- STM32CubeMX
- RealTerm

## Theory
USART enables serial communication between STM32 and external devices or PC terminals.

## Procedure
1. Enable USART peripheral in CubeMX.
2. Configure baud rate.
3. Generate project code.
4. Use HAL_UART_Transmit() to send text.
5. Observe output in RealTerm.

## Code Snippet

```c
char msg[] = "Hello STM32\r\n";
HAL_UART_Transmit(&huart2, (uint8_t*)msg, strlen(msg), 100);
```

## Result
Serial text data transmitted successfully.

## Output
![USART Output](../../images/usart_terminal_output.png)