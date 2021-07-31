### WARNING REMOTE HOST IDENTIFICATION HAS CHANGED

```
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@    WARNING: REMOTE HOST IDENTIFICATION HAS CHANGED!     @
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
IT IS POSSIBLE THAT SOMEONE IS DOING SOMETHING NASTY!
Someone could be eavesdropping on you right now (man-in-the-middle attack)!
It is also possible that a host key has just been changed.
The fingerprint for the RSA key sent by the remote host is
51:82:00:1c:7e:6f:ac:ac:de:f1:53:08:1c:7d:55:68.
Please contact your system administrator.
Add correct host key in /Users/isaacalves/.ssh/known_hosts to get rid of this message.
Offending RSA key in /Users/isaacalves/.ssh/known_hosts:12
RSA host key for 104.131.16.158 has changed and you have requested strict checking.
Host key verification failed.
```
>- # To solve this problem on vps connecton by ssh on terminal 👆 
```
ssh-keygen -R "you server hostname or ip"
```
>- # Run this command to Repair problem 👆
