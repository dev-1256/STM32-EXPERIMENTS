# Experiment 09 — Multi-Sensor Telemetry Frame

## Aim
To aggregate data from multiple onboard sensors and format it as a structured telemetry frame.

## Apparatus
- STM32 Discovery Kit
- STM32CubeIDE
- STM32CubeMX
- RealTerm

## Theory
Telemetry frames organize sensor values into structured data packets for communication and monitoring.

## Procedure
1. Read values from multiple sensors.
2. Format data into telemetry string.
3. Send telemetry data through USART.

## Example Frame

```text
TEMP:29 HUM:50 PRESS:1001 ACCX:12
```

## Result
Structured telemetry data generated successfully.

## Output
![Telemetry Output](../../images/telemetry_frame_output.png)