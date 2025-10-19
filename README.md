# Trust ICS-2000 Python library

Forked from https://github.com/Stijn-Jacobs/ICS2000-Python

Example usage:
```
from ics2000.Core import get_hub
import logging

logging.basicConfig(level=logging.DEBUG)

hub = get_hub(
    'Mac address of ics2000',
    'email',
    'password'
)
```

This will also list the devices connected
```
hub.turn_on(id of device to turn on)
  
hub.turn_off(id of device to turn off)

print(hub.get_lamp_status(id of device))
```

Heavily WIP
