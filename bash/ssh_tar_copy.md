Copy a temporary tar:ed folder over ssh
=======================================

   ssh user@server "tar zcf - /somedir/on/server" > /my/local/machine/somedir/file.tar.gz