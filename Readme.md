# About
x11vnc on alpine linux

FORK FROM: https://github.com/danielguerra69/alpine-vnc

# Usage

docker run -d -p 5900:5900 danielguerra/alpine-vnc

After this use vnc-client to connect to your alpine.
Right click shows the menu

Every runs as user alpine. This user has sudo rights.
The password=alpine you can change is with passwd in
the xterm.

Default it runs alpine 3.5 (changed). If you want to
use alpine 3.4 run

docker run -d -p 5900:5900 danielguerra/alpine-vnc:3.4
