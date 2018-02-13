# logorama
Light-weight python colored logging package

Here is a simple example

```
from logorama import logger, BaseLogger

logger.debug("Debugging...")
logger.info("Hello from Logorama")
logger.warning("This is a warning")
logger.error("THis is an ERRORRRRRRRR!!!!!")
logger.critical("THis is an EXCEPTIONNNNNNNNN!!!!!")


class LogExample(BaseLogger):
    def hello(self):
        self.logger.debug("Debugging...")
        self.logger.info("Hello from Logorama")
        self.logger.warning("This is a warning")
        self.logger.error("THis is an ERRORRRRRRRR!!!!!")
        self.logger.critical("THis is an EXCEPTIONNNNNNNNN!!!!!")

log_ex = LogExample()
log_ex.hello()

```

