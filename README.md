# r_pi_go_server

this is a server in golang for an in home raspberry pi 4

### steps to build:

- install the raspberry pi imager
- use advanced setting to set SSH login creds
- after installing, insert SD card into pi and confirm connection
- to build this server binary use the following for rasp 4: `GOOS=linux GOARCH=arm64 go build -o server`
- to transfer files (on mac) use the scp command, ex: `scp server yourservername@192.168.1.105:/home/pi/`
