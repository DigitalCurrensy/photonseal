# Photonseal

Is the record signed?

The signature covers the meter, the work order, the start, the length, the energy, and the clock. The key is not in the record. No key means no signature. Checking a signature with an empty or wrong key returns false.

It signs only after Unitcommit has passed, Fiberlock has wrapped the line, and Phasepin has a clock that is good enough. It will not sign a failed power check, an unwrapped path, a clock that is too wide, or GPS alone.

This is not a coin and not a token.

Copyright 2026 DIGITAL CURRENSY INC / Module Kinetic Ltd. Apache-2.0. See [LICENSE](LICENSE).
Parent: [module-kinetic-ltd](https://github.com/DigitalCurrensy/module-kinetic-ltd)
