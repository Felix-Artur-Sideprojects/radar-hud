# Planning notes

## 22 October 2026

The initial idea was a Raspberry Pi with a small display showing where a
person might be behind a wall, inspired by a handheld game radar.
The discussion separated a low-cost position-display prototype from a
validated through-wall radar.

RD-03D and LD2450 were considered for position reports. A Waveshare
presence sensor and LD2410C were discussed but did not meet the same
left/right positioning goal. Servos were not needed for the first version.

## 23 October 2026

The final supplier proposal was TinyTronics: RD-03D, CH340E USB-UART adapter,
and a 4-pin PicoBlade-to-DuPont cable. A Waveshare 2-inch, 240 × 320 SPI
display was then recommended. A 2.8-inch touch display was an alternative,
not the primary recommendation.

The order and exact part revisions are still to be confirmed.

## 11 November 2026

A possible later experiment is to look for breathing or heartbeat
signals. The listed parts are planned for the first motion tracking
prototype. We have yet to test whether they support vital-sign sensing.

Check the earlier four-pin cable suggestion against the actual hardware
revision and the manufacturer's pinout before connecting the sensor.
