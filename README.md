# nuc4info

		ashburndave@dphnuc4:~$ 
		ashburndave@dphnuc4:~$ java -version
		java version "1.8.0_162"
		Java(TM) SE Runtime Environment (build 1.8.0_162-b12)
		Java HotSpot(TM) 64-Bit Server VM (build 25.162-b12, mixed mode)
		ashburndave@dphnuc4:~$ javac -version
		javac 1.8.0_162
		ashburndave@dphnuc4:~$ groovy --version
		Groovy Version: 2.5.0 JVM: 1.8.0_162 Vendor: Oracle Corporation OS: Linux
		ashburndave@dphnuc4:~$ grails --version
		| Grails Version: 3.3.6
		| Groovy Version: 2.4.15
		| JVM Version: 1.8.0_162
		ashburndave@dphnuc4:~$ gradle --version
		Welcome to Gradle 4.8.1!
		Here are the highlights of this release:
		 - Dependency locking
		 - Maven Publish and Ivy Publish plugins improved and marked stable
		 - Incremental annotation processing enhancements
		 - APIs to configure tasks at creation time
		For more details see https://docs.gradle.org/4.8.1/release-notes.html
		------------------------------------------------------------
		Gradle 4.8.1
		------------------------------------------------------------
		Build time:   2018-06-21 07:53:06 UTC
		Revision:     0abdea078047b12df42e7750ccba34d69b516a22
		Groovy:       2.4.12
		Ant:          Apache Ant(TM) version 1.9.11 compiled on March 23 2018
		JVM:          1.8.0_162 (Oracle Corporation 25.162-b12)
		OS:           Linux 4.13.0-45-generic amd64
		ashburndave@dphnuc4:~$ 
		ashburndave@dphnuc4:~$ printenv | sort | grep HOME
		ECLIPSE_HOME=/opt/eclipse
		GGTS_HOME=/opt/ggts-bundle/ggts-3.6.4.RELEASE
		GRADLE_HOME=/opt/gradle
		GRAILS_HOME=/opt/grails
		GROOVY_HOME=/opt/groovy
		HOME=/home/ashburndave
		JAVA_HOME=/opt/jdk
		ashburndave@dphnuc4:~$ 

		ashburndave@dphnuc4:/opt$ ls -la
		total 60
		drwxr-xr-x 15 root        root        4096 Jul  8 07:44 .
		drwxr-xr-x 24 root        root        4096 Jul  2 06:40 ..
		lrwxrwxrwx  1 root        root          37 Jul  7 09:06 eclipse -> eclipse-jee-photon-R-linux-gtk-x86_64
		drwxr-xr-x  8 ashburndave ashburndave 4096 Mar 14  2017 eclipse-jee-neon-3-linux-gtk-x86_64
		drwxr-xr-x  8 ashburndave ashburndave 4096 Apr  5 11:13 eclipse-jee-oxygen-3a-linux-gtk-x86_64
		drwxr-xr-x  8 ashburndave ashburndave 4096 Jul  7 09:18 eclipse-jee-photon-R-linux-gtk-x86_64
		drwxr-xr-x  6 root        root        4096 Apr  9 07:08 ggts-bundle
		lrwxrwxrwx  1 root        root          12 Jul  8 07:44 gradle -> gradle-4.8.1
		drwxr-xr-x  6 ashburndave ashburndave 4096 Jun 21 07:56 gradle-4.8.1
		lrwxrwxrwx  1 root        root          12 Jul  5 07:43 grails -> grails-3.3.6
		drwxr-xr-x 11 root        root        4096 Apr  9 07:41 grails-2.4.4
		drwxr-xr-x 10 root        root        4096 Mar  3  2016 grails-2.5.4
		drwxr-xr-x  7 root        root        4096 Apr  4 16:52 grails-3.3.4
		drwxr-xr-x  7 root        root        4096 Jun 15 18:19 grails-3.3.6
		lrwxrwxrwx  1 root        root          12 Jul  8 07:15 groovy -> groovy-2.5.0
		drwxr-xr-x  8 ashburndave ashburndave 4096 May 27 13:01 groovy-2.5.0
		lrwxrwxrwx  1 root        root          12 Apr 10 19:28 jdk -> jdk1.8.0_162
		drwxr-xr-x  8 uucp                143 4096 Apr 10  2015 jdk1.7.0_79
		drwxr-xr-x  8 uucp                143 4096 Dec 20  2017 jdk1.8.0_162
		drwxr-xr-x  4 root        root        4096 Jun 19 08:32 sublime_text
		ashburndave@dphnuc4:/opt$ 

## eclipse   https://www.eclipse.org/downloads/eclipse-packages/

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
		ashburndave@dphnuc4:~/Downloads/tmp$ cd /opt
		ashburndave@dphnuc4:/opt$ 
		ashburndave@dphnuc4:/opt$ sudo ln -s eclipse-jee-photon-R-linux-gtk-x86_64 eclipse
		ashburndave@dphnuc4:/opt$ ls -latr
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
		lrwxrwxrwx  1 root        root          37 Jul  7 09:06 eclipse -> eclipse-jee-photon-R-linux-gtk-x86_64
		drwxr-xr-x 13 root        root        4096 Jul  7 09:06 .
		ashburndave@dphnuc4:/opt$ 

## groovy   http://groovy-lang.org/download.html

		ashburndave@dphnuc4:~/Downloads$ ls -latr | tail
		-rw-rw-r--  1 ashburndave ashburndave   28293248 Jul  8 07:03 apache-groovy-binary-2.5.0.zip
		-rw-rw-r--  1 ashburndave ashburndave        838 Jul  8 07:04 apache-groovy-binary-2.5.0.zip.asc
		-rw-rw-r--  1 ashburndave ashburndave         66 Jul  8 07:04 apache-groovy-binary-2.5.0.zip.sha256
		-rw-rw-r--  1 ashburndave ashburndave   16252731 Jul  8 07:05 apache-groovy-docs-2.5.0.zip
		-rw-rw-r--  1 ashburndave ashburndave        838 Jul  8 07:05 apache-groovy-docs-2.5.0.zip.asc
		-rw-rw-r--  1 ashburndave ashburndave         66 Jul  8 07:05 apache-groovy-docs-2.5.0.zip.sha256
		-rw-rw-r--  1 ashburndave ashburndave   52300089 Jul  8 07:07 apache-groovy-sdk-2.5.0.zip
		-rw-rw-r--  1 ashburndave ashburndave        838 Jul  8 07:07 apache-groovy-sdk-2.5.0.zip.asc
		-rw-rw-r--  1 ashburndave ashburndave         66 Jul  8 07:07 apache-groovy-sdk-2.5.0.zip.sha256
		drwxr-xr-x  2 ashburndave ashburndave      12288 Jul  8 07:09 .
		ashburndave@dphnuc4:~/Downloads$ 
		ashburndave@dphnuc4:~/Downloads$ mkdir tmp
		ashburndave@dphnuc4:~/Downloads$ cp -p apache-groovy-binary-2.5.0.zip tmp
		ashburndave@dphnuc4:~/Downloads$ cd tmp
		ashburndave@dphnuc4:~/Downloads/tmp$ unzip apache-groovy-binary-2.5.0.zip 
		ashburndave@dphnuc4:~/Downloads/tmp$ 
		ashburndave@dphnuc4:~/Downloads/tmp$ ls -latr
		total 27652
		drwxr-xr-x 8 ashburndave ashburndave     4096 May 27 13:01 groovy-2.5.0
		-rw-rw-r-- 1 ashburndave ashburndave 28293248 Jul  8 07:03 apache-groovy-binary-2.5.0.zip
		drwxr-xr-x 3 ashburndave ashburndave    12288 Jul  8 07:10 ..
		drwxr-xr-x 3 ashburndave ashburndave     4096 Jul  8 07:12 .
		ashburndave@dphnuc4:~/Downloads/tmp$ sudo mv groovy-2.5.0 /opt
		[sudo] password for ashburndave: 
		ashburndave@dphnuc4:~/Downloads/tmp$ cd /opt
		ashburndave@dphnuc4:/opt$ sudo ln -s groovy-2.5.0 groovy
		ashburndave@dphnuc4:/opt$ 

## gradle   https://gradle.org/releases/

		ashburndave@dphnuc4:~/Downloads$ ls -latr | tail
		-rw-rw-r--  1 ashburndave ashburndave   52300089 Jul  8 07:07 apache-groovy-sdk-2.5.0.zip
		-rw-rw-r--  1 ashburndave ashburndave        838 Jul  8 07:07 apache-groovy-sdk-2.5.0.zip.asc
		-rw-rw-r--  1 ashburndave ashburndave         66 Jul  8 07:07 apache-groovy-sdk-2.5.0.zip.sha256
		drwxr-xr-x  2 ashburndave ashburndave       4096 Jul  8 07:13 tmp
		drwxr-xr-x 44 ashburndave ashburndave       4096 Jul  8 07:28 ..
		-rw-rw-r--  1 ashburndave ashburndave   75889282 Jul  8 07:35 gradle-4.8.1-bin.zip
		-rw-rw-r--  1 ashburndave ashburndave         64 Jul  8 07:35 gradle-4.8.1-bin.zip.sha256
		-rw-rw-r--  1 ashburndave ashburndave  110900951 Jul  8 07:35 gradle-4.8.1-all.zip
		-rw-rw-r--  1 ashburndave ashburndave         64 Jul  8 07:35 gradle-4.8.1-all.zip.sha256
		drwxr-xr-x  3 ashburndave ashburndave      12288 Jul  8 07:36 .
		ashburndave@dphnuc4:~/Downloads$ 
		ashburndave@dphnuc4:~/Downloads$ cat gradle-4.8.1-bin.zip.sha256
		af334d994b5e69e439ab55b5d2b7d086da5ea6763d78054f49f147b06370ed71ashburndave@dphnuc4:~/Downloads$ 
		ashburndave@dphnuc4:~/Downloads$ 
		ashburndave@dphnuc4:~/Downloads$ shasum -a 256 gradle-4.8.1-bin.zip
		af334d994b5e69e439ab55b5d2b7d086da5ea6763d78054f49f147b06370ed71  gradle-4.8.1-bin.zip
		ashburndave@dphnuc4:~/Downloads$ 
		ashburndave@dphnuc4:~/Downloads$ mkdir tmp
		ashburndave@dphnuc4:~/Downloads$ cp -p gradle-4.8.1-bin.zip tmp
		ashburndave@dphnuc4:~/Downloads$ cd tmp
		ashburndave@dphnuc4:~/Downloads/tmp$ unzip gradle-4.8.1-bin.zip 
		ashburndave@dphnuc4:~/Downloads/tmp$ ls -latr
		total 74132
		drwxr-xr-x 6 ashburndave ashburndave     4096 Jun 21 07:56 gradle-4.8.1
		-rw-rw-r-- 1 ashburndave ashburndave 75889282 Jul  8 07:35 gradle-4.8.1-bin.zip
		drwxr-xr-x 3 ashburndave ashburndave    12288 Jul  8 07:41 ..
		drwxr-xr-x 3 ashburndave ashburndave     4096 Jul  8 07:42 .
		ashburndave@dphnuc4:~/Downloads/tmp$ 
		ashburndave@dphnuc4:~/Downloads/tmp$ sudo mv gradle-4.8.1 /opt
		ashburndave@dphnuc4:~/Downloads/tmp$ cd /opt
		ashburndave@dphnuc4:/opt$ sudo ln -s gradle-4.8.1 gradle
		ashburndave@dphnuc4:/opt$ 

## grails   https://grails.org/download.html

		mkdir tmp
		cp -p grails-3.3.6.zip tmp
		cd tmp
		unzip grails-3.3.6.zip
		sudo mv grails-3.3.6 /opt
		cd /opt
		sudo rm grails
		sudo ln -s grails-3.3.6 grails

## netbeans 8.2

		cd ~/Downloads
		mkdir tmp
		cp -p netbeans-8.2-linux.sh tmp
		cd tmp
		chmod +x netbeans-8.2-linux.sh 
		./netbeans-8.2-linux.sh 
		# added tomcat installation (turned off by default) ... I accepted installation into /home/ashburndave
		drwxr-xr-x  2 ashburndave ashburndave  4096 Jul  6 07:20 Desktop
		drwxr-xr-x 17 ashburndave ashburndave  4096 Jul  6 07:20 .config
		drwxr-xr-x  8 ashburndave ashburndave  4096 Jul  6 07:21 glassfish-4.1.1
		drwxr-xr-x  9 ashburndave ashburndave  4096 Jul  6 07:21 apache-tomcat-8.0.27
		drwxr-xr-x  7 ashburndave ashburndave  4096 Jul  6 07:23 .nbi
		drwx------ 17 ashburndave ashburndave  4096 Jul  6 07:24 .cache
		drwxr-xr-x 23 ashburndave ashburndave  4096 Jul  6 07:24 netbeans-8.2
		drwxr-xr-x  3 ashburndave ashburndave  4096 Jul  6 07:25 .netbeans
		drwxr-xr-x  3 ashburndave ashburndave  4096 Jul  6 07:26 .netbeans-derby
		drwxr-xr-x  3 ashburndave ashburndave  4096 Jul  6 07:27 NetBeansProjects

## sublime

## vs code

## ggts

## sts

## ubuntu 18.04 (bionic beaver)   http://releases.ubuntu.com/   http://releases.ubuntu.com/bionic/

		ashburndave@dphnuc4:~/Downloads$ ls -latr | tail
		-rw-rw-r--  1 ashburndave ashburndave  201489834 Jul  6 05:42 eclipse-java-photon-R-linux-gtk-x86_64.tar.gz
		-rw-r--r--  1 ashburndave ashburndave        176 Jul  6 05:42 eclipse-java-photon-R-linux-gtk-x86_64.tar.gz.sha512
		drwxr-xr-x 43 ashburndave ashburndave       4096 Jul  7 09:17 ..
		-rw-rw-r--  1 ashburndave ashburndave 1921843200 Jul  7 16:07 ubuntu-18.04-desktop-amd64.iso
		-rw-rw-r--  1 ashburndave ashburndave        198 Jul  7 16:08 SHA256SUMS
		-rw-rw-r--  1 ashburndave ashburndave        916 Jul  7 16:08 SHA256SUMS.gpg
		-rw-rw-r--  1 ashburndave ashburndave       8084 Jul  7 16:08 ubuntu-18.04-desktop-amd64.list
		-rw-rw-r--  1 ashburndave ashburndave      54520 Jul  7 16:09 ubuntu-18.04-desktop-amd64.manifest
		-rw-rw-r--  1 ashburndave ashburndave      46536 Jul  7 16:09 ubuntu-18.04-desktop-amd64.metalink
		drwxr-xr-x  2 ashburndave ashburndave      12288 Jul  7 16:10 .
		ashburndave@dphnuc4:~/Downloads$ 
		ashburndave@dphnuc4:~/Downloads$ mv SHA256SUMS ubuntu-18.04-desktop-amd64.sha256
		ashburndave@dphnuc4:~/Downloads$ mv SHA256SUMS.gpg ubuntu-18.04-desktop-amd64.sha256.gpg
		ashburndave@dphnuc4:~/Downloads$ 
		ashburndave@dphnuc4:~/Downloads$ ls -latr | tail
		-rw-rw-r--  1 ashburndave ashburndave  201489834 Jul  6 05:42 eclipse-java-photon-R-linux-gtk-x86_64.tar.gz
		-rw-r--r--  1 ashburndave ashburndave        176 Jul  6 05:42 eclipse-java-photon-R-linux-gtk-x86_64.tar.gz.sha512
		drwxr-xr-x 43 ashburndave ashburndave       4096 Jul  7 09:17 ..
		-rw-rw-r--  1 ashburndave ashburndave 1921843200 Jul  7 16:07 ubuntu-18.04-desktop-amd64.iso
		-rw-rw-r--  1 ashburndave ashburndave        198 Jul  7 16:08 ubuntu-18.04-desktop-amd64.sha256
		-rw-rw-r--  1 ashburndave ashburndave        916 Jul  7 16:08 ubuntu-18.04-desktop-amd64.sha256.gpg
		-rw-rw-r--  1 ashburndave ashburndave       8084 Jul  7 16:08 ubuntu-18.04-desktop-amd64.list
		-rw-rw-r--  1 ashburndave ashburndave      54520 Jul  7 16:09 ubuntu-18.04-desktop-amd64.manifest
		-rw-rw-r--  1 ashburndave ashburndave      46536 Jul  7 16:09 ubuntu-18.04-desktop-amd64.metalink
		drwxr-xr-x  2 ashburndave ashburndave      12288 Jul  7 16:12 .
		ashburndave@dphnuc4:~/Downloads$ 
