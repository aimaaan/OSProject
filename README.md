# OSProject Running Containers for Application Development

Group Name: __OS yeay__

Section: __1__ 

Team Mates:
1. __Ahmad Arif Aiman bin Ahmad Fauzi__ and __2113419__
2. __Nursyazira binti Mohd Naim__ and __2214076__
3. __Nur Raihan Syazwani binti Suhaimi__ and __2213262__
4. __Khairul Najmi bin Khairul Azam__ and __2016671__

The authors of the task are encased in square brackets as such: 
- [aiman] refers to [Ahmad Arif Aiman bin Ahmad Fauzi](https://github.com/aimaaan)
- [Syazira] refers to [Nursyazira binti Mohd Naim](https://github.com/syaziranaimm)
- [Syazwani] refers to [Nur Raihan Syazwani binti Suhaimi](https://github.com/rhsyazwani)
- [Najmi] refers to [Khairul Najmi bin Khairul Azam](https://github.com/jemiazam)

## Forking this OS project repository [aiman]

***Questions:***

1. What is the link of the fork OSProject in your repository. ***(1 mark)*** __https://github.com/aimaaan/OSProject.git__.
2. How many files and folders are in this repository. ***(1 mark)*** __1 files(README.md) and 1 folder(images)__.

## Exploring github codespaces [aiman]

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** __Ubuntu Linux__.
2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** __2 cores, 8 GB RAM, and 32 GB storage, up to 32 cores, 64 GB RAM, and 128 GB storage.__.
3. Why must we commit and sync our current work on source control? ***(1 mark)*** __Committing and syncing your work in source control is important because it keeps a record of all changes, helps team members work together, and protects your work from being lost. It also allows for automatic testing and deployment, keeps track of who made which changes, and helps resolve any conflicts early. Regular updates ensure everyone is on the same page and the project runs smoothly.__.

## Exploring the Terminal [Najmi]

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
```bash
@jemiazam ➜ /workspaces/OSProject (main) $ pwd
/workspaces/OSProject
```

2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
```bash
@jemiazam ➜ /workspaces/OSProject (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin

```
3. Run the command **df** . ***(1 mark)*** 
```bash
@jemiazam ➜ /workspaces/OSProject (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10387732  20765852  34% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 22415608   7866184  75% /vscode
/dev/sda1       46127956       96  43752284   1% /tmp
/dev/loop3      32847680 10387732  20765852  34% /workspaces
```
4. Run the command **du** . ***(1 mark)***.
```bash
@jemiazam ➜ /workspaces/OSProject (main) $ du
2204    ./images
12      ./myroot/myroot
16      ./myroot
8       ./.git/logs/refs/heads
8       ./.git/logs/refs/remotes/origin
12      ./.git/logs/refs/remotes
24      ./.git/logs/refs
32      ./.git/logs
4       ./.git/lfs/tmp
8       ./.git/lfs
8       ./.git/info
68      ./.git/hooks
4       ./.git/objects/info
3112    ./.git/objects/pack
3120    ./.git/objects
8       ./.git/refs/heads
4       ./.git/refs/tags
8       ./.git/refs/remotes/origin
12      ./.git/refs/remotes
28      ./.git/refs
4       ./.git/branches
3376    ./.git
28      ./nodejs-app/node_modules/etag
24      ./nodejs-app/node_modules/negotiator/lib
52      ./nodejs-app/node_modules/negotiator
24      ./nodejs-app/node_modules/toidentifier
36      ./nodejs-app/node_modules/type-is
32      ./nodejs-app/node_modules/express/lib/router
12      ./nodejs-app/node_modules/express/lib/middleware
124     ./nodejs-app/node_modules/express/lib
260     ./nodejs-app/node_modules/express
36      ./nodejs-app/node_modules/iconv-lite/lib
232     ./nodejs-app/node_modules/iconv-lite/encodings/tables
348     ./nodejs-app/node_modules/iconv-lite/encodings
412     ./nodejs-app/node_modules/iconv-lite
8       ./nodejs-app/node_modules/side-channel/test
8       ./nodejs-app/node_modules/side-channel/.github
68      ./nodejs-app/node_modules/side-channel
8       ./nodejs-app/node_modules/gopd/test
8       ./nodejs-app/node_modules/gopd/.github
44      ./nodejs-app/node_modules/gopd
20      ./nodejs-app/node_modules/object-inspect/example
8       ./nodejs-app/node_modules/object-inspect/test/browser
96      ./nodejs-app/node_modules/object-inspect/test
8       ./nodejs-app/node_modules/object-inspect/.github
216     ./nodejs-app/node_modules/object-inspect
24      ./nodejs-app/node_modules/destroy
24      ./nodejs-app/node_modules/parseurl
8       ./nodejs-app/node_modules/setprototypeof/test
32      ./nodejs-app/node_modules/setprototypeof
24      ./nodejs-app/node_modules/unpipe
20      ./nodejs-app/node_modules/ee-first
20      ./nodejs-app/node_modules/send/node_modules/ms
24      ./nodejs-app/node_modules/send/node_modules
92      ./nodejs-app/node_modules/send
24      ./nodejs-app/node_modules/cookie-signature
64      ./nodejs-app/node_modules/safer-buffer
20      ./nodejs-app/node_modules/process-nextick-args
24      ./nodejs-app/node_modules/encodeurl
40      ./nodejs-app/node_modules/serve-static
28      ./nodejs-app/node_modules/bytes
32      ./nodejs-app/node_modules/http-errors
20      ./nodejs-app/node_modules/readable-stream/lib/internal/streams
24      ./nodejs-app/node_modules/readable-stream/lib/internal
96      ./nodejs-app/node_modules/readable-stream/lib
8       ./nodejs-app/node_modules/readable-stream/doc/wg-meetings
12      ./nodejs-app/node_modules/readable-stream/doc
48      ./nodejs-app/node_modules/readable-stream/node_modules/safe-buffer
52      ./nodejs-app/node_modules/readable-stream/node_modules
224     ./nodejs-app/node_modules/readable-stream
24      ./nodejs-app/node_modules/merge-descriptors
12      ./nodejs-app/node_modules/has-symbols/test/shams
24      ./nodejs-app/node_modules/has-symbols/test
8       ./nodejs-app/node_modules/has-symbols/.github
72      ./nodejs-app/node_modules/has-symbols
28      ./nodejs-app/node_modules/content-type
48      ./nodejs-app/node_modules/safe-buffer
8       ./nodejs-app/node_modules/core-util-is/lib
24      ./nodejs-app/node_modules/core-util-is
36      ./nodejs-app/node_modules/content-disposition
20      ./nodejs-app/node_modules/escape-html
28      ./nodejs-app/node_modules/body-parser/lib/types
40      ./nodejs-app/node_modules/body-parser/lib
100     ./nodejs-app/node_modules/body-parser
12      ./nodejs-app/node_modules/mime/src
80      ./nodejs-app/node_modules/mime
8       ./nodejs-app/node_modules/hasown/.github
48      ./nodejs-app/node_modules/hasown
8       ./nodejs-app/node_modules/es-define-property/test
8       ./nodejs-app/node_modules/es-define-property/.github
56      ./nodejs-app/node_modules/es-define-property
8       ./nodejs-app/node_modules/has-property-descriptors/test
8       ./nodejs-app/node_modules/has-property-descriptors/.github
48      ./nodejs-app/node_modules/has-property-descriptors
40      ./nodejs-app/node_modules/cookie
32      ./nodejs-app/node_modules/proxy-addr
4       ./nodejs-app/node_modules/.bin
44      ./nodejs-app/node_modules/raw-body
16      ./nodejs-app/node_modules/get-intrinsic/test
8       ./nodejs-app/node_modules/get-intrinsic/.github
76      ./nodejs-app/node_modules/get-intrinsic
8       ./nodejs-app/node_modules/depd/lib/browser
12      ./nodejs-app/node_modules/depd/lib
52      ./nodejs-app/node_modules/depd
20      ./nodejs-app/node_modules/ms
24      ./nodejs-app/node_modules/path-to-regexp
24      ./nodejs-app/node_modules/inherits
16      ./nodejs-app/node_modules/define-data-property/test
8       ./nodejs-app/node_modules/define-data-property/.github
72      ./nodejs-app/node_modules/define-data-property
20      ./nodejs-app/node_modules/array-flatten
12      ./nodejs-app/node_modules/call-bind/test
8       ./nodejs-app/node_modules/call-bind/.github
64      ./nodejs-app/node_modules/call-bind
16      ./nodejs-app/node_modules/string_decoder/lib
48      ./nodejs-app/node_modules/string_decoder/node_modules/safe-buffer
52      ./nodejs-app/node_modules/string_decoder/node_modules
88      ./nodejs-app/node_modules/string_decoder
100     ./nodejs-app/node_modules/mysql/lib/protocol/packets
40      ./nodejs-app/node_modules/mysql/lib/protocol/sequences
288     ./nodejs-app/node_modules/mysql/lib/protocol/constants
496     ./nodejs-app/node_modules/mysql/lib/protocol
556     ./nodejs-app/node_modules/mysql/lib
48      ./nodejs-app/node_modules/mysql/node_modules/safe-buffer
52      ./nodejs-app/node_modules/mysql/node_modules
712     ./nodejs-app/node_modules/mysql
36      ./nodejs-app/node_modules/debug/src
112     ./nodejs-app/node_modules/debug
8       ./nodejs-app/node_modules/set-function-length/.github
60      ./nodejs-app/node_modules/set-function-length
12      ./nodejs-app/node_modules/sqlstring/lib
40      ./nodejs-app/node_modules/sqlstring
28      ./nodejs-app/node_modules/ipaddr.js/lib
64      ./nodejs-app/node_modules/ipaddr.js
28      ./nodejs-app/node_modules/util-deprecate
24      ./nodejs-app/node_modules/vary
40      ./nodejs-app/node_modules/finalhandler
24      ./nodejs-app/node_modules/utils-merge
220     ./nodejs-app/node_modules/mime-db
20      ./nodejs-app/node_modules/function-bind/test
12      ./nodejs-app/node_modules/function-bind/.github
80      ./nodejs-app/node_modules/function-bind
24      ./nodejs-app/node_modules/methods
24      ./nodejs-app/node_modules/forwarded
28      ./nodejs-app/node_modules/statuses
24      ./nodejs-app/node_modules/fresh
44      ./nodejs-app/node_modules/qs/lib
72      ./nodejs-app/node_modules/qs/dist
84      ./nodejs-app/node_modules/qs/test
8       ./nodejs-app/node_modules/qs/.github
288     ./nodejs-app/node_modules/qs
24      ./nodejs-app/node_modules/range-parser
32      ./nodejs-app/node_modules/mime-types
36      ./nodejs-app/node_modules/isarray
8       ./nodejs-app/node_modules/has-proto/test
8       ./nodejs-app/node_modules/has-proto/.github
52      ./nodejs-app/node_modules/has-proto
36      ./nodejs-app/node_modules/accepts
32      ./nodejs-app/node_modules/on-finished
92      ./nodejs-app/node_modules/bignumber.js/doc
420     ./nodejs-app/node_modules/bignumber.js
28      ./nodejs-app/node_modules/media-typer
8       ./nodejs-app/node_modules/es-errors/test
8       ./nodejs-app/node_modules/es-errors/.github
100     ./nodejs-app/node_modules/es-errors
5544    ./nodejs-app/node_modules
5592    ./nodejs-app
11348   .
```
5. Run the command **ls** . ***(1 mark)*** 
```bash
@jemiazam ➜ /workspaces/OSProject (main) $ ls
README.md  images  myroot  nodejs-app
```
6. Run the command **ls -asl** . ***(1 mark)*** 
```bash
@jemiazam ➜ /workspaces/OSProject (main) $ ls -asl
total 60
 4 drwxrwxrwx+ 6 codespace root  4096 Jun 30 02:28 .
 4 drwxr-xrwx+ 5 codespace root  4096 Jun 30 02:28 ..
 4 drwxrwxrwx+ 9 codespace root  4096 Jun 30 02:28 .git
36 -rw-rw-rw-  1 codespace root 36504 Jun 30 03:00 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 Jun 30 02:44 images
 4 drwxrwxrwx+ 3 codespace root  4096 Jun 30 02:28 myroot
 4 drwxrwxrwx+ 3 codespace root  4096 Jun 30 02:28 nodejs-app
```
7. Run the command **free -h** . ***(1 mark)***
<img src="images\FREE-H.png" width="auto" height="100px">

8. Run the command **cat /proc/cpuinfo** . ***(1 mark)***.
```bash
@jemiazam ➜ /workspaces/OSProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3242.197
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.83
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3242.436
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.83
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:
```
9. Run the command **top** and type **q** to quit. ***(1 mark)***.
 <img src="images/FREE-H.png" width=auto height=100px>


10. Run the command **uname -a**. ***(1 mark)***.
```bash
@jemiazam ➜ /workspaces/OSProject (main) $ uname -a
Linux codespaces-d529be 6.5.0-1022-azure #23~22.04.1-Ubuntu SMP Thu May  9 17:59:24 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux

```
11. What is the available free memory in the system. ***(1 mark)*** 
<br><br>According to the command **free -h**, the available free memory is **5.9GB**.<br><br>

12. What is the available disk space mounted on /workspace. ***(1 mark)*** 
<br><br>According to **df** command, the available disk space mounted on/workspace is **20765852 KB**.<br><br>

13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)***.
<br><br>The version is Linux #23~22.04.1-Ubuntu, and the hardware architecture is x86_64.<br><br>

14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** .
<br><br>The **ls** command lists the files and directories in the current directory, whereas **ls -asl** displays additional information such as file size, ownership, permissions, and timestamps.<br><br>

15. What is the TLB size of the Virtual CPU. ***(1 mark)***.
<br><br>The size of the **TLB (Translation Lookaside Buffer)** is **2560 4K pages**.<br><br>


16. What is the CPU speed of the Virtual CPU. ***(1 mark)***.<br><br>According to the **cat/ proc/cpuinfo** command, the CPU speed of the Virtual CPU is 3242.436 MHz. (equivalent to 3.2 GHz)<br><br>

17. What is the top running process that consumes the most CPU cycles. ***(1 mark)***.
<br><br>According to **top** command, the top running process that consumes the most CPU cycles is node which consumes 1.7%.<br><br>

## Running your own container instance. [aiman]

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available? __yes__.
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt? __helloworld.txt also are been deleted as well__.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** __No, files in a container are not persistent by default because containers are designed to be temporary. When a container stops or is deleted, any changes to the files inside are lost. To keep data safe, you need to use volumes or bind mounts, which store data outside the container.__.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** __Yes, you can run two or three instances of Debian Linux. Each instance can be a separate container, allowing you to run multiple isolated versions of Debian on the same system__.

## Running your own container with persistent storage [aiman]

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** __the user and the group are belong to the root__. 
```bash
@aimaaan ➜ /workspaces/OSProject/myroot (main) $ ls -la
total 12
drwxrwxrwx+ 3 codespace codespace 4096 Jun 15 04:40 .
drwxrwxrwx+ 6 codespace root      4096 Jun 15 03:40 ..
drwxr-xr-x+ 2 root      root      4096 Jun 15 04:40 myroot
```

2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot
```

__yes, after execute above command it change the permission to codespace from root__
```bash @aimaaan ➜ /workspaces/OSProject/myroot (main) $ ls -la
total 12
drwxrwxrwx+ 3 codespace codespace 4096 Jun 15 04:40 .
drwxrwxrwx+ 6 codespace root      4096 Jun 15 03:40 ..
drwxr-xr-x+ 2 codespace codespace 4096 Jun 15 04:40 myroot
```

***

## You are on your own, create your own static webpage [Syazwani]

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** __Permissions of folder /usr/local/apache2/htdocs: drwxrwxrwx+. User and group that owns the folder: User: root, Group: root__.
```bash
root@5c2a79602e26:/usr/local/apache2# ls -ld /usr/local/apache2/htdocs
drwxrwxrwx+ 2 root root 4096 Jun 15 06:16 /usr/local/apache2/htdocs
```
3. What port is the apache web server running. ***(1 mark)*** __80__.
4. What port is open for http protocol on the host machine? ***(1 mark)*** __8080__.

## Create SUB Networks [Syazira]

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** __A single application designed to be as tiny as possible, BusyBox is a shell that has built-in versions of most important system commands that are functional but small. The goal is to give embedded computers as much essential Unix command-line environment capabilities as feasible in the smallest available package.The command switch --name is used in Docker to assign a specific name to a container. This makes it easier to manage and reference the container instead of using its automatically generated ID.__.
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)***
  ```bash
Usage:  docker network COMMAND

Manage networks

Commands:
  connect     Connect a container to a network
  create      Create a network
  disconnect  Disconnect a container from a network
  inspect     Display detailed information on one or more networks
  ls          List networks
  prune       Remove all unused networks
  rm          Remove one or more networks

Run 'docker network COMMAND --help' for more information on a command.
 ```
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)*** __bluenet: 172.18.0.1 rednet: 172.19.0.1__.
4. What is the network address for the running container c1 and c2? ***(1 mark)*** __bluenet: 172.18.0.2 rednet: 172.19.0.2__.
5. Using the command ```docker exec c1 ping c2```, which basically tries to do a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)*** __No__.
```bash
ping: bad address 'c2'
```
## Bridging two SUB Networks [Syazira]
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```
***Questions:***

1. Are you able to ping? Show your output . ***(1 mark)*** __Yes__.
    ```bash
    PING c2 (172.20.0.3): 56 data bytes
    ```

2. What is different from the previous ping in the section above? ***(1 mark)*** __The first ping failed because failure occurred because c1 and c2 were on separate networks (bluenet and rednet), preventing them from communicating with each other directly. In the current setup, by creating the bridgenet network and connecting both containers (c1 and c2) to it, a common network is established that allows them to see each other and communicate__.

## Intermediate Level (10 marks bonus) [aiman]

### Node.js and MySQL in Docker Containers

This guide will help you set up a simple Node.js website that retrieves a random row from a MySQL database. Both the MySQL server and the Node.js server will run in separate Docker containers on two separate networks. Your job is to make it work by making the two containers in two separate network bridged together.

#### Step 1: Set Up the Docker Network

Create a Docker network to for the two containers.
For mysql, call it **mysqlnet** for nodejs call it **nodejsnet** .

#### Step 2: Set Up the MySQL Container

Run a MySQL container on the created network.

```sh
docker run --name mysql-container --network mysqlnet -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=mydatabase -e MYSQL_USER=myuser -e MYSQL_PASSWORD=mypassword -d mysql:latest
```

#### Step 3: Set Up the Node.js Container

1. **Create a directory for your Node.js application and initialize it.**

    ```sh
    mkdir nodejs-app
    cd nodejs-app
    npm init -y
    npm install express mysql
    ```

2. **Create a file named `index.js` with the following content:**

    ```js
    const express = require('express');
    const mysql = require('mysql');

    const app = express();
    const port = 3000;

    // Create a MySQL connection
    const connection = mysql.createConnection({
      host: 'mysql-container',
      user: 'myuser',
      password: 'mypassword',
      database: 'mydatabase'
    });

    // Connect to MySQL
    connection.connect((err) => {
      if (err) {
        console.error('Error connecting to MySQL:', err);
        return;
      }
      console.log('Connected to MySQL');
    });

    // Define a route to get a random row
    app.get('/random', (req, res) => {
      const query = 'SELECT * FROM mytable ORDER BY RAND() LIMIT 1';
      connection.query(query, (err, results) => {
        if (err) {
          console.error('Error executing query:', err);
          res.status(500).send('Server Error');
          return;
        }
        res.json(results[0]);
      });
    });

    // Start the server
    app.listen(port, () => {
      console.log(`Server running at http://localhost:${port}`);
    });
    ```

3. **Create a Dockerfile for the Node.js application:**

    ```Dockerfile
    # Use the official Node.js image
    FROM node:14

    # Create and change to the app directory
    WORKDIR /usr/src/app

    # Copy application dependency manifests to the container image
    COPY package*.json ./

    # Install production dependencies
    RUN npm install

    # Copy local code to the container image
    COPY . .

    # Run the web service on container startup
    CMD [ "node", "index.js" ]
    ```

#### Step 4: Build and Run the Node.js Container

1. **Build the Docker image for the Node.js application.**

    ```sh
    docker build -t nodejs-app .
    ```

2. **Run the Node.js container on the same network as the MySQL container.**

    ```sh
    docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
    ```

#### Step 5: Test the Setup

You can now test the setup by accessing the Node.js application in your browser or using a tool like `curl`:

```sh
curl http://localhost:3000/random
```

#### Step 6: Ensure `mytable` is Populated

Make sure you have created the `mytable` table and populated it with some data in your MySQL database for the above steps to work correctly.

You can use the following SQL commands to create and populate the table (run these commands in the MySQL container):

```sql
CREATE TABLE mytable (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  value VARCHAR(255) NOT NULL
);

INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
```

### Summary

You have now set up a Node.js application in a Docker container on nodejsnet netowrk and a MySQL database in another Docker container on mysqlnet network. Now bridge the two network together.

***Questions:***

1. What is the output of step 5 above, explain the error? ***(1 mark)*** __error shows `Cannot GET /`  This error occurs because the Node.js container cannot resolve the hostname mysql-container. This happens because the Node.js container and MySQL container are on separate Docker networks (nodejsnet and mysqlnet), and containers on different networks cannot communicate with each other by default. Furthermore, The error "Cannot GET /" typically means that the Node.js server is running, but there is no route defined to handle requests to the root URL ("/"). In the index.js file, the only defined route is /random. Therefore, when access http://localhost:3000/, the server doesn't know how to handle the request.__.
2. Show the instruction needed to make this work. ***(1 mark)*** __To make the Node.js container communicate with the MySQL container, it need to bridge the two networks together and To fix cannot /get error, need to add a route to handle requests to the root URL in the index.js file. below are detailed instructions:__.

- Updated the `index.js` file.
```Js
const express = require('express');
const mysql = require('mysql');

const app = express();
const port = 3000;

// Create a MySQL connection
const connection = mysql.createConnection({
  host: 'mysql-container',
  user: 'myuser',
  password: 'mypassword',
  database: 'mydatabase'
});

// Connect to MySQL
connection.connect((err) => {
  if (err) {
    console.error('Error connecting to MySQL:', err);
    return;
  }
  console.log('Connected to MySQL');
});

// Define a route to handle requests to the root URL
app.get('/', (req, res) => {
  res.send('Welcome to the Node.js and MySQL application!');
});

// Define a route to get a random row
app.get('/random', (req, res) => {
  const query = 'SELECT * FROM mytable ORDER BY RAND() LIMIT 1';
  connection.query(query, (err, results) => {
    if (err) {
      console.error('Error executing query:', err);
      res.status(500).send('Server Error');
      return;
    }
    res.json(results[0]);
  });
});

// Start the server
app.listen(port, () => {
  console.log(`Server running at http://localhost:${port}`);
});
```
The updated js file include the new route definition for the root URL('/') 
then, update the and run the application again by rebuliding the docker image for the node.js application

```bash
docker build -t nodejs-app .
```

run the updated Node.js container
```bash
docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
```

and dont forget to bridge the network if not already done yet
```bash
docker network connect mysqlnet nodejs-container
```

lastly, test the setup again. when Access http://localhost:3000/ in browser. it should see the message "Welcome to the Node.js and MySQL application!".


## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***AS STATED IN ITALEEM SYSTEM***
