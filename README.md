$ cat /etc/issue
 _ __ ___    __ _ | |_ | |_ | |__  (_)  __ _  ___ 
| '_ ` _ \  / _` || __|| __|| '_ \ | | / _` |/ __|
| | | | | || (_| || |_ | |_ | | | || || (_| |\__ \
|_| |_| |_| \__,_| \__| \__||_| |_||_| \__,_||___/
                                                  
            _                   _      _             
 ___   ___ | |__   _ __    ___ (_)  __| |  ___  _ __ 
/ __| / __|| '_ \ | '_ \  / _ \| | / _` | / _ \| '__|
\__ \| (__ | | | || | | ||  __/| || (_| ||  __/| |   
|___/ \___||_| |_||_| |_| \___||_| \__,_| \___||_|  

$ uname -a
Human #1 SMP PREEMPT 04 Sep 1982 15:04:05 +0100 x86_64

$ cat /etc/profile
DOMAIN=schneider.vip
GITHUB=mschneider82
TWITTER=matthiass82

$ kubectl get nodes
NAME                 STATUS                     ROLES                       AGE   VERSION
home                 Ready,SchedulingDisabled   husband,father              5y    v1.21.0
work                 Ready                      it-research,etcd,master     15y   v1.21.0
