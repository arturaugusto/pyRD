# pyRD
Zero configuration easy to deploy remote desktop software.

Demo video: https://youtu.be/A_ZdcatcM4o

# Usage

1. Run app.py to start a flask server web application. This is your client application.
2. Run remote.py at the windows computer you want to control and provide the addr of flask server and a key command line arguments. (e.g: `python remote.py http://127.0.0.1:5000 1234`)
2. Navigate with a we browser to flask web app (e.g: http://127.0.0.1:5000) and provide the key to connect.
