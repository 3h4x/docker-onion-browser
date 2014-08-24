docker-onion-browser
====================

    XSOCK=/tmp/.X11-unix/X0
    sudo docker build -t onion-browser git://github.com/3h4x/docker-onion-browser.git
    sudo docker run -it -v $XSOCK:$XSOCK onion-browser`

