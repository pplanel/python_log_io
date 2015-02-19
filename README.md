log.io logging handler
======================

Handler for the python logging framework for log.io stateless TCP API

http://logio.org/

*Example usage:*

1. The defaults
```python
import logging
from log_io_handler import LogIOHandler

Logger = logging.getLogger("my_logio_logger")
logging.basicConfig(level=logging.DEBUG)
Logger.addHandler(LogIOHandler)
```
