# Voltage controlled power latch

This circuit was designed to monitor the main voltage and trigger an enable signal when it is reached, which is then latched and won't disengage until the transistors reset, or a shutdown signal is applied.

The latch circuit was borrowed from https://github.com/lab11/monjolo project, specifically the gecko\_power\_supply revision E hardware. Parts were upgraded to use ones that draw even less power than the ones used in the monjolo project.
