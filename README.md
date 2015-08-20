# exoclick_toutrix_media
Get publisher CPM on ExoClick and update them on TouTrix Media AdServer.

This script connect to your ExoClick account, get all the CPMs you are earning and update your TouTrix Media account with those CPMs.

ExoClick is paying us every week since years. You don't have an account yet?
http://www.exoclick.com/signup/?login=AdPornMedia

If you don't have a TouTrix account yet, get one here:
http://www.toutrix.com/media/

SETUP

change directory to your workspace

git clone https://github.com/c3rv3au/exoclick_toutrix_media.git

cd exoclick_toutrix_media

mkdir classes && cd classes

git clone https://github.com/c3rv3au/toutrix_php


This script is using the Toutrix PHP API connector :

https://github.com/c3rv3au/toutrix_php

cd ..

edit run.php and update the variable at the beginning of the file.

Launch run.php, it will create campaigns at TouTrix Media and one flight per country per campaign. It's only done one time. After, it will update your CPM each time your launch run.php.
