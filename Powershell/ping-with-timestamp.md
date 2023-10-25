#### Ref
```
https://stackoverflow.com/questions/10679807/how-do-i-timestamp-every-ping-result
```

#### Commands
```
PS C:\Users\dangv> ping 192.168.10.20 -t |Foreach{"{0} - {1}" -f (Get-Date),$_}
10/25/2023 12:33:50 PM - 
10/25/2023 12:33:50 PM - Pinging 192.168.10.20 with 32 bytes of data:
10/25/2023 12:33:50 PM - Reply from 192.168.10.20: bytes=32 time=4ms TTL=128
10/25/2023 12:33:51 PM - Reply from 192.168.10.20: bytes=32 time=4ms TTL=128
10/25/2023 12:33:52 PM - Reply from 192.168.10.20: bytes=32 time=4ms TTL=128
```
