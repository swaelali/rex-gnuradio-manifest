# rex-gnuradio-manifest

Getting started 
---------------
* __1- Install Repo__

  * *Download the Repo script.*

  * `$ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > repo`

  * *Make it executable.*

  * `$ chmod a+x repo`

  * *Move it on to your system path.*

  * `$ sudo mv repo /usr/local/bin/`

* __2- Initialize a Repo Client__

  * *Create an empty directory to hold your working files.*

  * `$ mkdir rex-repo`
  
  * `$ cd rex-repo`

  * *Tell Repo where to find the manifest*

  * `$ repo init -u git://github.com/swaelali/rex-gnuradio-manifest.git -b krogoth`


* __3-Fetch all the repositories.__

  * `$ repo sync`
