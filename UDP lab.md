# 1
```
4个部分，分别是：source port destination port length checksum
```
# 2
```
source port :2 bytes
destination port :2bytes
length:2bytes
checksum:2bytes
```

# 3
```
58
```
# 4
```
$2^16-1-8=65527$
```
# 5
```
$2^16 -1 =65535$
```

# 6
```
十进制：17

十六进制：0x11
```
# 7
```
第一个udp的包的destination port是第二个udp包的source port,第二个udp包的destination port是第一个udp包的source port。
```
