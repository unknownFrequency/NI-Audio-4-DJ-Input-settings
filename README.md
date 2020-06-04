# NI-Audio-4-DJ-Input-settings for Linux (tested in Arch)

chmod +x phono.sh

./phono.sh [line|phono|timecode]

If there is not loopback you can try the following command:

````pacmd load-module module-loopback latency_msec=5````
