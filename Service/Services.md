# Services 
- Services in linux helps to run the things in the background even when the server is rebooted. As well as, they will try to start them in the right order
```
systemctl start httpd # helps to start the apche webserver
service start https # starts the webserver as well
```
---
- Systemctl commands Usage:
   - `start` — Starts the service immediately.
   - `stop` — Stops the service immediately.
   - `enable` — Configures the service to start automatically on boot.
   - `disable` — Prevents the service from starting automatically on boot.
