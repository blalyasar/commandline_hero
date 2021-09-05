
<p style='text-align: justify;'> commandline_hero </p>



<p style='text-align: justify;'> My Commandline Frequency - Komut satırında en çok kullandığım komutlar </p>

Copy - Paste
```
fc -l 1 | awk '{CMD[$2]++;count++;}END { for (a in CMD)print CMD[a] " " CMD[a]/count*100 "% " a; }' | grep -v "./" | column -c3 -s " " -t | sort -nr | nl | head -n15
```
>05.09.2021
```
     1  2708  26.999%      ls
     2  1841  18.3549%     cd
     3  420   4.18744%     git
     4  363   3.61914%     cat
     5  288   2.87139%     flutter
     6  270   2.69192%     exit
     7  235   2.34297%     code
     8  221   2.20339%     rm
     9  220   2.19342%     sudo
    10  215   2.14357%     python
    11  213   2.12363%     dnf
    12  176   1.75474%     adb
    13  128   1.27617%     make
    14  114   1.13659%     pwd
    15  110   1.09671%     echo
```
> 04.08.2021
```
     1  527  24.1632%    ls
     2  410  18.7987%    cd
     3  119  5.45621%    flutter
     4  79   3.62219%    exit
     5  75   3.43879%    adb
     6  72   3.30124%    code
     7  59   2.70518%    cat
     8  49   2.24668%    sudo
     9  39   1.78817%    dnf
    10  37   1.69647%    pwd
    11  35   1.60477%    python
    12  35   1.60477%    history
    13  33   1.51307%    vlc
    14  29   1.32967%    git
    15  29   1.32967%    echo
```
