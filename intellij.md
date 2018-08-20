

```
ashburndave@dphnuc4:~/Downloads$ 
ashburndave@dphnuc4:~/Downloads$ ls -latr idea* | tail
-rw-rw-r-- 1 ashburndave ashburndave 469330992 Jun  5 06:10 ideaIC-2018.1.4-no-jdk.tar.gz
-rw-rw-r-- 1 ashburndave ashburndave        96 Jun  5 06:10 ideaIC-2018.1.4-no-jdk.tar.gz.sha256
-rw-rw-r-- 1 ashburndave ashburndave 644700595 Jul 26 06:38 ideaIU-2018.2.tar.gz
-rw-rw-r-- 1 ashburndave ashburndave        87 Jul 26 06:38 ideaIU-2018.2.tar.gz.sha256
-rw-rw-r-- 1 ashburndave ashburndave 571076168 Jul 26 06:40 ideaIU-2018.2-no-jdk.tar.gz
-rw-rw-r-- 1 ashburndave ashburndave        94 Jul 26 06:40 ideaIU-2018.2-no-jdk.tar.gz.sha256
-rw-rw-r-- 1 ashburndave ashburndave 520591686 Jul 26 06:41 ideaIC-2018.2.tar.gz
-rw-rw-r-- 1 ashburndave ashburndave        87 Jul 26 06:41 ideaIC-2018.2.tar.gz.sha256
-rw-rw-r-- 1 ashburndave ashburndave 446966767 Jul 26 06:43 ideaIC-2018.2-no-jdk.tar.gz
-rw-rw-r-- 1 ashburndave ashburndave        94 Jul 26 06:43 ideaIC-2018.2-no-jdk.tar.gz.sha256
ashburndave@dphnuc4:~/Downloads$ 
ashburndave@dphnuc4:~/Downloads$ mkdir tmp
ashburndave@dphnuc4:~/Downloads$ cp -p ideaIU-2018.2-no-jdk.tar.gz tmp
ashburndave@dphnuc4:~/Downloads$ cd tmp
ashburndave@dphnuc4:~/Downloads/tmp$ ls -latr
total 557716
-rw-rw-r-- 1 ashburndave ashburndave 571076168 Jul 26 06:40 ideaIU-2018.2-no-jdk.tar.gz
drwxr-xr-x 3 ashburndave ashburndave     20480 Aug 20 07:57 ..
drwxr-xr-x 2 ashburndave ashburndave      4096 Aug 20 07:58 .
ashburndave@dphnuc4:~/Downloads/tmp$ 
ashburndave@dphnuc4:~/Downloads/tmp$ tar xzf ideaIU-2018.2-no-jdk.tar.gz 
ashburndave@dphnuc4:~/Downloads/tmp$ 
ashburndave@dphnuc4:~/Downloads/tmp$ ls -latr
total 557724
-rw-rw-r-- 1 ashburndave ashburndave 571076168 Jul 26 06:40 ideaIU-2018.2-no-jdk.tar.gz
drwxr-xr-x 3 ashburndave ashburndave     20480 Aug 20 07:57 ..
drwxr-xr-x 3 ashburndave ashburndave      4096 Aug 20 07:58 .
drwxr-xr-x 8 ashburndave ashburndave      4096 Aug 20 07:58 idea-IU-182.3684.101
ashburndave@dphnuc4:~/Downloads/tmp$ 
ashburndave@dphnuc4:~/Downloads/tmp$ cd idea-IU-182.3684.101/
ashburndave@dphnuc4:~/Downloads/tmp/idea-IU-182.3684.101$ 
ashburndave@dphnuc4:~/Downloads/tmp/idea-IU-182.3684.101$ ls -latr
total 48
-rw-r--r--   1 ashburndave ashburndave    15 Jul 24 11:00 build.txt
-rw-r--r--   1 ashburndave ashburndave  1944 Jul 24 11:00 Install-Linux-tar.txt
drwxr-xr-x   3 ashburndave ashburndave  4096 Aug 20 07:58 ..
drwxr-xr-x   2 ashburndave ashburndave  4096 Aug 20 07:58 help
drwxr-xr-x   3 ashburndave ashburndave  4096 Aug 20 07:58 license
drwxr-xr-x 132 ashburndave ashburndave  4096 Aug 20 07:58 plugins
drwxr-xr-x   3 ashburndave ashburndave  4096 Aug 20 07:58 redist
drwxr-xr-x   8 ashburndave ashburndave  4096 Aug 20 07:58 .
drwxr-xr-x   6 ashburndave ashburndave 12288 Aug 20 07:58 lib
drwxr-xr-x   2 ashburndave ashburndave  4096 Aug 20 07:58 bin
ashburndave@dphnuc4:~/Downloads/tmp/idea-IU-182.3684.101$ 
ashburndave@dphnuc4:~/Downloads/tmp/idea-IU-182.3684.101$ cd bin
ashburndave@dphnuc4:~/Downloads/tmp/idea-IU-182.3684.101/bin$ 
ashburndave@dphnuc4:~/Downloads/tmp/idea-IU-182.3684.101/bin$ ls -latr
total 7548
-rw-r--r-- 1 ashburndave ashburndave    2322 Jul 24 11:00 log.xml
-rw-r--r-- 1 ashburndave ashburndave     136 Jul 24 11:00 appletviewer.policy
-rwxr-xr-x 1 ashburndave ashburndave     808 Jul 24 11:00 restart.py
-rwxr-xr-x 1 ashburndave ashburndave     410 Jul 24 11:00 printenv.py
-rw-r--r-- 1 ashburndave ashburndave 3908380 Jul 24 11:00 libyjpagent-linux.so
-rw-r--r-- 1 ashburndave ashburndave 3654864 Jul 24 11:00 libyjpagent-linux64.so
-rwxr-xr-x 1 ashburndave ashburndave     275 Jul 24 11:00 inspect.sh
-rw-r--r-- 1 ashburndave ashburndave     382 Jul 24 11:00 idea.vmoptions
-rwxr-xr-x 1 ashburndave ashburndave    6849 Jul 24 11:00 idea.sh
-rw-r--r-- 1 ashburndave ashburndave   11293 Jul 24 11:00 idea.properties
-rw-r--r-- 1 ashburndave ashburndave    9701 Jul 24 11:00 idea.png
-rw-r--r-- 1 ashburndave ashburndave     374 Jul 24 11:00 idea64.vmoptions
-rwxr-xr-x 1 ashburndave ashburndave   26453 Jul 24 11:00 fsnotifier-arm
-rwxr-xr-x 1 ashburndave ashburndave   29648 Jul 24 11:00 fsnotifier64
-rwxr-xr-x 1 ashburndave ashburndave   23072 Jul 24 11:00 fsnotifier
-rwxr-xr-x 1 ashburndave ashburndave     224 Jul 24 11:00 format.sh
drwxr-xr-x 8 ashburndave ashburndave    4096 Aug 20 07:58 ..
drwxr-xr-x 2 ashburndave ashburndave    4096 Aug 20 07:58 .
ashburndave@dphnuc4:~/Downloads/tmp/idea-IU-182.3684.101/bin$ 
ashburndave@dphnuc4:~/Downloads/tmp/idea-IU-182.3684.101/bin$ 
ashburndave@dphnuc4:~/Downloads/tmp/idea-IU-182.3684.101/bin$ ./idea.sh
Aug 20, 2018 8:02:14 AM java.util.prefs.FileSystemPreferences$6 run
WARNING: Prefs file removed in background /home/ashburndave/.java/.userPrefs/prefs.xml
WARN: NodeJS not loaded: since build 182.3911 > IU-182.3684.101
```

```
ashburndave@dphnuc4:/usr/local/bin$ 
ashburndave@dphnuc4:/usr/local/bin$ pwd -P
/usr/local/bin
ashburndave@dphnuc4:/usr/local/bin$ ls -latr
total 12
drwxr-xr-x 10 root root 4096 Oct 18  2017 ..
-rwxr-xr-x  1 root root 3225 Aug 20 08:05 idea
drwxr-xr-x  2 root root 4096 Aug 20 08:05 .
ashburndave@dphnuc4:/usr/local/bin$ 
```

```
ashburndave@dphnuc4:~$ cd ~
ashburndave@dphnuc4:~$ ls -latr | tail
-rw-------  1 ashburndave ashburndave  5144 Aug 18 07:34 .ICEauthority
drwxr-xr-x  9 ashburndave ashburndave  4096 Aug 18 08:06 g2projects
-rw-r--r--  1 ashburndave ashburndave    13 Aug 18 08:12 .grails_history
-rw-r--r--  1 ashburndave ashburndave 22247 Aug 18 09:37 stuff-20180818.txt
drwxr-xr-x  3 ashburndave ashburndave 20480 Aug 20 07:57 Downloads
drwxr-xr-x  4 ashburndave ashburndave  4096 Aug 20 08:02 .IntelliJIdea2018.2
drwx------  3 ashburndave ashburndave  4096 Aug 20 08:05 .gnome
drwxr-xr-x  2 ashburndave ashburndave  4096 Aug 20 08:06 .android
drwxr-xr-x  3 ashburndave ashburndave  4096 Aug 20 08:12 IdeaProjects
drwxr-xr-x 53 ashburndave ashburndave  4096 Aug 20 08:12 .
ashburndave@dphnuc4:~$ 
ashburndave@dphnuc4:~$ ls -latr IdeaProjects/
total 12
drwxr-xr-x 53 ashburndave ashburndave 4096 Aug 20 08:12 ..
drwxr-xr-x  3 ashburndave ashburndave 4096 Aug 20 08:12 .
drwxr-xr-x  5 ashburndave ashburndave 4096 Aug 20 08:13 myfirstideaprj
ashburndave@dphnuc4:~$ 
```

