Benchmarks

System:

             ...-:::::-...                 ferozakbar@fersys 
          .-MMMMMMMMMMMMMMM-.              ----------------- 
      .-MMMM`..-:::::::-..`MMMM-.          OS: Linux Mint 21.2 x86_64 
    .:MMMM.:MMMMMMMMMMMMMMM:.MMMM:.        Host: Vostro 15 3510 
   -MMM-M---MMMMMMMMMMMMMMMMMMM.MMM-       Kernel: 6.2.0-25-generic 
 `:MMM:MM`  :MMMM:....::-...-MMMM:MMM:`    Uptime: 3 days, 22 mins 
 :MMM:MMM`  :MM:`  ``    ``  `:MMM:MMM:    Packages: 3947 (dpkg), 17 (flatpak), 16 (snap) 
.MMM.MMMM`  :MM.  -MM.  .MM-  `MMMM.MMM.   Shell: zsh 5.8.1 
:MMM:MMMM`  :MM.  -MM-  .MM:  `MMMM-MMM:   Resolution: 1920x1080 
:MMM:MMMM`  :MM.  -MM-  .MM:  `MMMM:MMM:   DE: Xfce 4.18 
:MMM:MMMM`  :MM.  -MM-  .MM:  `MMMM-MMM:   WM: Xfwm4 
.MMM.MMMM`  :MM:--:MM:--:MM:  `MMMM.MMM.   WM Theme: Mint-Y-Aqua 
 :MMM:MMM-  `-MMMMMMMMMMMM-`  -MMM-MMM:    Theme: Adwaita [GTK2], Breeze [GTK3] 
  :MMM:MMM:`                `:MMM:MMM:     Icons: Sevi [GTK2] 
   .MMM.MMMM:--------------:MMMM.MMM.      Terminal: terminator 
     '-MMMM.-MMMMMMMMMMMMMMM-.MMMM-'       CPU: 11th Gen Intel i5-1135G7 (8) @ 4.200GHz 
       '.-MMMM``--:::::--``MMMM-.'         GPU: Intel TigerLake-LP GT2 [Iris Xe Graphics] 
            '-MMMMMMMMMMMMM-'              Memory: 6417MiB / 15728MiB 
               ``-:::::-``
                                                                   
                                                                   



nginx-fpm
Running 30s test @ http://127.0.0.1:8080
  12 threads and 400 connections
  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency    19.20ms   27.75ms 186.41ms   85.26%
    Req/Sec     3.64k     1.68k    7.93k    60.24%
  1301509 requests in 30.09s, 1.03GB read
Requests/sec:  43249.41
Transfer/sec:     35.18MB



roadrunner
Running 30s test @ http://127.0.0.1:8085
  12 threads and 400 connections
  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency    16.80ms    8.34ms  49.08ms   58.05%
    Req/Sec     1.97k   187.89     9.71k    85.14%
  707458 requests in 30.06s, 87.03MB read
Requests/sec:  23531.35
Transfer/sec:      2.89MB



workerman
Running 30s test @ http://127.0.0.1:2345
  12 threads and 400 connections
  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency     1.23ms    1.17ms  30.26ms   95.05%
    Req/Sec    29.20k     4.06k   84.94k    75.26%
  10477829 requests in 30.09s, 1.29GB read
Requests/sec: 348191.50
Transfer/sec:     43.83MB



nodejs
Running 30s test @ http://127.0.0.1:3000
  12 threads and 400 connections
  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency     8.87ms    2.68ms 100.11ms   96.37%
    Req/Sec     3.78k   510.88     9.53k    82.38%
  1357280 requests in 30.09s, 178.63MB read
Requests/sec:  45114.17
Transfer/sec:      5.94MB


openswoole
Running 30s test @ http://127.0.0.1:9501
  12 threads and 400 connections
  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency     2.04ms    2.58ms  91.79ms   96.83%
    Req/Sec    18.05k     2.49k   92.33k    86.88%
  6475734 requests in 30.10s, 1.00GB read
Requests/sec: 215138.73
Transfer/sec:     33.85MB
