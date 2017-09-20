# Flask

## send email


from flask_mail import *
mail = Mail()
msg = Message("Hello", sender="test@flask.com", recipients=["errorcollectorapps.zina@nokia.com"])
mail.send(msg)

