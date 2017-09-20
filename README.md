# Flask

## send email

""
from flask_mail import *
msg = Message("Hello", sender="test@flask.com", recipients=["errorcollectorapps.zina@nokia.com"])
mail.send(msg)
""
