通用调优
-----------------

#. ulimit 限制
   一般一台机器，先用 `ulimit -a` 看一下，系统是否有限制资源使用, 例如::

    > ulimit

    core file size          (blocks, -c) 0
    data seg size           (kbytes, -d) unlimited
    scheduling priority             (-e) 0
    file size               (blocks, -f) unlimited
    pending signals                 (-i) 93592
    max locked memory       (kbytes, -l) 64
    max memory size         (kbytes, -m) unlimited
    open files                      (-n) 1024
    pipe size            (512 bytes, -p) 8
    POSIX message queues     (bytes, -q) 819200
    real-time priority              (-r) 0
    stack size              (kbytes, -s) 8192
    cpu time               (seconds, -t) unlimited
    max user processes              (-u) 1024
    virtual memory          (kbytes, -v) unlimited
    file locks                      (-x) unlimited


