
<p style='text-align: justify;'> commandline_hero </p>



<p style='text-align: justify;'> My Commandline Frequency - Komut satırında en çok kullandığım komutlar </p>

Copy - Paste
```
fc -l 1 | awk '{CMD[$2]++;count++;}END { for (a in CMD)print CMD[a] " " CMD[a]/count*100 "% " a; }' | grep -v "./" | column -c3 -s " " -t | sort -nr | nl | head -n30

>05.10.2021
```
     1  3411  25.1679%     ls
     2  2397  17.6861%     cd
     3  537   3.96222%     cat
     4  467   3.44573%     git
     5  387   2.85546%     exit
     6  360   2.65624%     code
     7  323   2.38324%     sudo
     8  321   2.36848%     flutter
     9  291   2.14713%     python
    10  283   2.0881%      rm
    11  282   2.08072%     dnf
    12  203   1.49782%     adb
    13  194   1.43142%     pwd
    14  189   1.39453%     make
    15  147   1.08463%     echo
    16  134   0.988711%    telegrambeta
    17  115   0.848521%    cmake
    18  103   0.759979%    g++
    19  94    0.693573%    grepsift
    20  85    0.627167%    su
    21  83    0.612411%    mkdir
    22  83    0.612411%    LS
    23  79    0.582897%    mv
    24  78    0.575518%    history
    25  71    0.523869%    pip
    26  69    0.509112%    socialmedia
    27  67    0.494355%    shutdown
    28  64    0.47222%     source
    29  60    0.442706%    micro
    30  54    0.398436%    scrcpy
```

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
