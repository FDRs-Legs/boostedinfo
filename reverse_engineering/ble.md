# BLE

## Services

### Battery `65A8EAA8-C61F-11E5-9912-BA0BE0483C18` 
| Characteristic UUID | Name | Notes |
|--|--|--|
| `65A8EEAE-C61F-11E5-9912-BA0BE0483C18` | Battery SOC | |
| `65A8F3C2-C61F-11E5-9912-BA0BE0483C18` | Battery capacity | |
| `65A8F5D4-C61F-11E5-9912-BA0BE0483C18` | Battery charging | |
| `65A8F832-C61F-11E5-9912-BA0BE0483C18` | Battery is large | |
| `65A8F833-C61F-11E5-9912-BA0BE0483C18` | Battery firmware version | |
| `65A8F834-C61F-11E5-9912-BA0BE0483C18` | Battery serial number | |
| `65A8F835-C61F-11E5-9912-BA0BE0483C18` | Battery RTC | |

### Board `7DC55A86-C61F-11E5-9912-BA0BE0483C18` 
| Characteristic UUID | Name | Notes |
|--|--|--|
| `7DC59643-C61F-11E5-9912-BA0BE0483C18` | Board model name | |
| `7DC55DEC-C61F-11E5-9912-BA0BE0483C18` | Number of ride modes | |
| `7DC55F22-C61F-11E5-9912-BA0BE0483C18` | Current ride mode | |
| `7DC56594-C61F-11E5-9912-BA0BE0483C18` | Odometer | Value is in number of wheel rotations |
| `7DC56B34-C61F-11E5-9912-BA0BE0483C18` | Speed | |
| `7DC56BFC-C61F-11E5-9912-BA0BE0483C18` | Power | |
| `7DC573EC-C61F-11E5-9912-BA0BE0483C18` | OTAUMD | |
| `7DC5BB39-C61F-11E5-9912-BA0BE0483C18` | Vehicle ID | |
| `7DC5C19D-C61F-11E5-9912-BA0BE0483C18` | Vehicle units | |
| `7DC5C201-C61F-11E5-9912-BA0BE0483C18` | Motor driver serial number | |
| `7DC5C202-C61F-11E5-9912-BA0BE0483C18` | Motor driver firmware version | |


### Debug Serial `588560E2-0065-11E6-8D22-5E5517507C66` 
| Characteristic UUID | Name | Notes |
|--|--|--|
| `58856524-0065-11E6-8D22-5E5517507C66` | Debug serial | |
| `58856525-0065-11E6-8D22-5E5517507C66` | Debug serial auth | |


### Lights `EA32B817-D410-42E2-848A-1218201468FC` 
| Characteristic UUID | Name | Notes |
|--|--|--|
| `EA32B761-D410-42E2-848A-1218201468FC` | Default mode | |
| `EA324D8C-D410-42E2-848A-1218201468FC` | Brake pattern | |
| `EA32DCAC-D410-42E2-848A-1218201468FC` | Light status | |
| `EA326B96-D410-42E2-848A-1218201468FC` | Brightness | |

### Firmware update/bootloader/??? `00001016-d102-11e1-9b23-00025b00a5a5`
| Characteristic UUID | Name | Notes |
|--|--|--|
| `00001010-d102-11e1-9b23-00025b00a5a5` |  | |
| `00001017-d102-11e1-9b23-00025b00a5a5` |  | |
| `00001014-d102-11e1-9b23-00025b00a5a5` |  | |
| `00001015-d102-11e1-9b23-00025b00a5a5` |  | |
| `00001099-d102-11e1-9b23-00025b00a5a5` |  | |
| `00001011-d102-11e1-9b23-00025b00a5a5` | Bootloader version | |
| `00001013-d102-11e1-9b23-00025b00a5a5` | Operational mode | Value is `0x01` in regular operation mode. Changing it to `0x00` puts the board into update mode. |