# Battery

## Models
| Name | Model number | Voltage | Wh
|--|--|--|--|
| Standard range | B2SR | 39.6V | 99Wh |
| Extended range | B2XR | 46.8V | 267Wh |

## Cells
| Model | Manufacturer | Part number |
|--|--|--|
| B2SR | ? | ? |
| B2XR | LG | INR18650HG2 |

## Power button combinations
| Process | Result |
|--|--|
| Fast click | Shows battery level indicator |
| 1 second hold | Turns on battery |
| 3 second hold | Turns off battery |
| 5 fast clicks | Puts the board into Bluetooth pairing mode |
| While plugged in, holding the power button until all lights turn off | Hard resets the battery |

## Status lights
### Standard range battery
| Power button LED | Battery level indicator | Meaning |
|--|--|--|
| Solid green | * | Battery is either fully charged or powered on |
| Solid red | * | Battery is charging |
| Pulsing blue | * | Board is in Bluetooth pairing mode |
| Solid yellow | * | Connection issue between battery and motor controller |
| Blinking red | 00001 | Connection issue between battery and motor controller |

### Extended range battery
| Power button LED | Battery level indicator | Meaning |
|--|--|--|
| Solid green | * | Battery is either fully charged or powered on |
| Solid red | * | Battery is charging |
| Pulsing blue | * | Board is in Bluetooth pairing mode |
| Solid yellow | * | Connection issue between battery and motor controller |
| Blinking yellow | 01110 | Connection issue between battery and motor controller |