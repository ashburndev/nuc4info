# nuc4info

## eclipse

		ashburndave@dphnuc4:~/Downloads$ ls -latr | grep jee
		-rw-rw-r--  1 ashburndave ashburndave  316866453 Jul  6 05:23 eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz
		-rw-rw-r--  1 ashburndave ashburndave         77 Jul  6 05:23 eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz.md5
		-rw-rw-r--  1 ashburndave ashburndave         85 Jul  6 05:23 eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz.sha1
		-rw-rw-r--  1 ashburndave ashburndave        173 Jul  6 05:23 eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz.sha512
		-rw-rw-r--  1 ashburndave ashburndave  346253117 Jul  6 05:28 eclipse-jee-oxygen-3a-linux-gtk-x86_64.tar.gz
		-rw-rw-r--  1 ashburndave ashburndave         80 Jul  6 05:28 eclipse-jee-oxygen-3a-linux-gtk-x86_64.tar.gz.md5
		-rw-rw-r--  1 ashburndave ashburndave         88 Jul  6 05:29 eclipse-jee-oxygen-3a-linux-gtk-x86_64.tar.gz.sha1
		-rw-r--r--  1 ashburndave ashburndave        176 Jul  6 05:33 eclipse-jee-oxygen-3a-linux-gtk-x86_64.tar.gz.sha512
		-rw-rw-r--  1 ashburndave ashburndave  357776781 Jul  6 05:39 eclipse-jee-photon-R-linux-gtk-x86_64.tar.gz
		-rw-r--r--  1 ashburndave ashburndave        175 Jul  6 05:40 eclipse-jee-photon-R-linux-gtk-x86_64.tar.gz.sha512
		-rw-rw-r--  1 ashburndave ashburndave         79 Jul  6 05:41 eclipse-jee-photon-R-linux-gtk-x86_64.tar.gz.md5
		-rw-rw-r--  1 ashburndave ashburndave         87 Jul  6 05:41 eclipse-jee-photon-R-linux-gtk-x86_64.tar.gz.sha1
		ashburndave@dphnuc4:~/Downloads$ 
		ashburndave@dphnuc4:~/Downloads$ shasum -a 512 eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz.sha512
		d31dc7f22dc9ff57dd974ebeb0aac627fc19c100bdaa436e575d0918c7095f1c8dd96f871cc4d3418fa7b60fee47cb1d530efab565ac907147039834284555fe  eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz.sha512
		ashburndave@dphnuc4:~/Downloads$ 
		ashburndave@dphnuc4:~/Downloads$ shasum -a 512 -c eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz.sha512
		eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz: OK
		ashburndave@dphnuc4:~/Downloads$ 
		ashburndave@dphnuc4:~/Downloads$ shasum -a 512 -c eclipse-jee-oxygen-3a-linux-gtk-x86_64.tar.gz.sha512
		eclipse-jee-oxygen-3a-linux-gtk-x86_64.tar.gz: OK
		ashburndave@dphnuc4:~/Downloads$ 
		ashburndave@dphnuc4:~/Downloads$ shasum -a 512 -c eclipse-jee-photon-R-linux-gtk-x86_64.tar.gz.sha512
		eclipse-jee-photon-R-linux-gtk-x86_64.tar.gz: OK
		ashburndave@dphnuc4:~/Downloads$ 
		ashburndave@dphnuc4:~/Downloads$ mkdir tmp
		ashburndave@dphnuc4:~/Downloads$ cp -p *jee*.gz tmp
		ashburndave@dphnuc4:~/Downloads$ cd tmp
		ashburndave@dphnuc4:~/Downloads/tmp$ ls -latr
		total 997000
		-rw-rw-r-- 1 ashburndave ashburndave 316866453 Jul  6 05:23 eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz
		-rw-rw-r-- 1 ashburndave ashburndave 346253117 Jul  6 05:28 eclipse-jee-oxygen-3a-linux-gtk-x86_64.tar.gz
		-rw-rw-r-- 1 ashburndave ashburndave 357776781 Jul  6 05:39 eclipse-jee-photon-R-linux-gtk-x86_64.tar.gz
		drwxr-xr-x 3 ashburndave ashburndave     12288 Jul  7 08:43 ..
		drwxr-xr-x 2 ashburndave ashburndave      4096 Jul  7 08:43 .
		ashburndave@dphnuc4:~/Downloads/tmp$
		ashburndave@dphnuc4:~/Downloads/tmp$ tar xzf eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz
		ashburndave@dphnuc4:~/Downloads/tmp$ ls -latr
		total 997004
		drwxr-xr-x 8 ashburndave ashburndave      4096 Mar 14  2017 eclipse
		-rw-rw-r-- 1 ashburndave ashburndave 316866453 Jul  6 05:23 eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz
		-rw-rw-r-- 1 ashburndave ashburndave 346253117 Jul  6 05:28 eclipse-jee-oxygen-3a-linux-gtk-x86_64.tar.gz
		-rw-rw-r-- 1 ashburndave ashburndave 357776781 Jul  6 05:39 eclipse-jee-photon-R-linux-gtk-x86_64.tar.gz
		drwxr-xr-x 3 ashburndave ashburndave     12288 Jul  7 08:43 ..
		drwxr-xr-x 3 ashburndave ashburndave      4096 Jul  7 08:44 .
		ashburndave@dphnuc4:~/Downloads/tmp$ 
		ashburndave@dphnuc4:~/Downloads/tmp$ mv eclipse eclipse-jee-neon-3-linux-gtk-x86_64
		ashburndave@dphnuc4:~/Downloads/tmp$ ls -latr
		total 997004
		drwxr-xr-x 8 ashburndave ashburndave      4096 Mar 14  2017 eclipse-jee-neon-3-linux-gtk-x86_64
		-rw-rw-r-- 1 ashburndave ashburndave 316866453 Jul  6 05:23 eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz
		-rw-rw-r-- 1 ashburndave ashburndave 346253117 Jul  6 05:28 eclipse-jee-oxygen-3a-linux-gtk-x86_64.tar.gz
		-rw-rw-r-- 1 ashburndave ashburndave 357776781 Jul  6 05:39 eclipse-jee-photon-R-linux-gtk-x86_64.tar.gz
		drwxr-xr-x 3 ashburndave ashburndave     12288 Jul  7 08:43 ..
		drwxr-xr-x 3 ashburndave ashburndave      4096 Jul  7 08:45 .
		ashburndave@dphnuc4:~/Downloads/tmp$ 
		ashburndave@dphnuc4:~/Downloads/tmp$ tar xzf eclipse-jee-oxygen-3a-linux-gtk-x86_64.tar.gz
		ashburndave@dphnuc4:~/Downloads/tmp$ mv eclipse eclipse-jee-oxygen-3a-linux-gtk-x86_64
		ashburndave@dphnuc4:~/Downloads/tmp$ 
		ashburndave@dphnuc4:~/Downloads/tmp$ tar xzf eclipse-jee-photon-R-linux-gtk-x86_64.tar.gz
		ashburndave@dphnuc4:~/Downloads/tmp$ mv eclipse eclipse-jee-photon-R-linux-gtk-x86_64
		ashburndave@dphnuc4:~/Downloads/tmp$ 
		ashburndave@dphnuc4:~/Downloads/tmp$ ls -latr
		total 997012
		drwxr-xr-x 8 ashburndave ashburndave      4096 Mar 14  2017 eclipse-jee-neon-3-linux-gtk-x86_64
		drwxr-xr-x 8 ashburndave ashburndave      4096 Apr  5 11:13 eclipse-jee-oxygen-3a-linux-gtk-x86_64
		drwxr-xr-x 8 ashburndave ashburndave      4096 Jun 20 08:12 eclipse-jee-photon-R-linux-gtk-x86_64
		-rw-rw-r-- 1 ashburndave ashburndave 316866453 Jul  6 05:23 eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz
		-rw-rw-r-- 1 ashburndave ashburndave 346253117 Jul  6 05:28 eclipse-jee-oxygen-3a-linux-gtk-x86_64.tar.gz
		-rw-rw-r-- 1 ashburndave ashburndave 357776781 Jul  6 05:39 eclipse-jee-photon-R-linux-gtk-x86_64.tar.gz
		drwxr-xr-x 3 ashburndave ashburndave     12288 Jul  7 08:43 ..
		drwxr-xr-x 5 ashburndave ashburndave      4096 Jul  7 08:58 .
		ashburndave@dphnuc4:~/Downloads/tmp$ 
		ashburndave@dphnuc4:~/Downloads/tmp$ rm *.gz
		ashburndave@dphnuc4:~/Downloads/tmp$ sudo mv * /opt
		[sudo] password for ashburndave: 
		ashburndave@dphnuc4:~/Downloads/tmp$ ls -latr /opt
		total 52
		drwxr-xr-x  8 uucp                143 4096 Apr 10  2015 jdk1.7.0_79
		drwxr-xr-x 10 root        root        4096 Mar  3  2016 grails-2.5.4
		drwxr-xr-x  8 ashburndave ashburndave 4096 Mar 14  2017 eclipse-jee-neon-3-linux-gtk-x86_64
		drwxr-xr-x  8 uucp                143 4096 Dec 20  2017 jdk1.8.0_162
		drwxr-xr-x  7 root        root        4096 Apr  4 16:52 grails-3.3.4
		drwxr-xr-x  8 ashburndave ashburndave 4096 Apr  5 11:13 eclipse-jee-oxygen-3a-linux-gtk-x86_64
		drwxr-xr-x  6 root        root        4096 Apr  9 07:08 ggts-bundle
		drwxr-xr-x 11 root        root        4096 Apr  9 07:41 grails-2.4.4
		lrwxrwxrwx  1 root        root          12 Apr 10 19:28 jdk -> jdk1.8.0_162
		drwxr-xr-x  7 root        root        4096 Jun 15 18:19 grails-3.3.6
		drwxr-xr-x  4 root        root        4096 Jun 19 08:32 sublime_text
		drwxr-xr-x  8 ashburndave ashburndave 4096 Jun 20 08:12 eclipse-jee-photon-R-linux-gtk-x86_64
		drwxr-xr-x 24 root        root        4096 Jul  2 06:40 ..
		lrwxrwxrwx  1 root        root          12 Jul  5 07:43 grails -> grails-3.3.6
		drwxr-xr-x 13 root        root        4096 Jul  7 09:00 .
		ashburndave@dphnuc4:~/Downloads/tmp$ 

