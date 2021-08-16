
<p style='text-align: justify;'> commandline_hero </p>



<p style='text-align: justify;'> My Commandline Frequency - Komut satırında en çok kullandığım komutlar </p>

Copy - Paste
```
fc -l | awk '{CMD[$2]++;count++;}END { for (a in CMD)print CMD[a] " " CMD[a]/count*100 "% " a; }' | grep -v "./" | column -c3 -s " " -t | sort -nr | nl | head -n15
```
> 08.04.2017 
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
