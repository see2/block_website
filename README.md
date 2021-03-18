# Block Website in Mac

It is a very easy way to block/unblock social/news website which may overwhelming my emotion in special time period.

```
sudo vim /etc/hosts
```

Input the passowrd, and add the lines in the end of the file.

```
# the website block in this computer
127.0.0.1 [website url]
127.0.0.1 [website url]
```

Quit the vim file.

Delete of mark two line out when you want visit the website again.
