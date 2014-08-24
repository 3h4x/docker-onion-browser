docker-onion-browser
====================

run it

    XSOCK=/tmp/.X11-unix/X0
    sudo docker run -it -v $XSOCK:$XSOCK 3h4x/onion-browser

if you get error 500 then wait few seconds. tor and privoxy need to start first
