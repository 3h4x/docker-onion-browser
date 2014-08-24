docker-onion-browser
====================

It is a chromium browser in container which connects via privoxy to tor network.

    XSOCK=/tmp/.X11-unix/X0
    sudo docker run -it -v $XSOCK:$XSOCK 3h4x/onion-browser

Wait few seconds for Tor and Privoxy to start and enjoy anon network.
