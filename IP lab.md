# 1
```
192.168.1.102
```
# 2
```
ICMP(1)
```
# 3
```
20 bytes in IP header 
36 bytes 
```
# 4
```
fragment offset =0,没有被切片
```
# 5
```
header checksum和Identification
```
# 6
```
stay const: ip version(must), header length(must), total length(must),source address(must),upper layer protocol(must)
must change:header checksum, identification
原因：给分组标号
```
# 7
```
分组的idenfication逐渐增大
```
# 8
```
identification:0xa60b(42422)
ttl :224
```
# 9
```
ttl不变，每一跳的ttl是不变的
identification是改变的，每一个分组没有被切片，所以不同分组的identification是不同的
```
# 10
```
被切片了
```
# 11
```
flags:more fragments
通过fragment offset的值判断，如果是0，表示是第一个切片。偏移量/切片分组大小 的值判断是第几个分组。
```
# 12
```
fragment offset,flags:more fragments表示还有切片
```
# 13
```
fragment offst 和header checksum
```
# 14
```
3个
```
# 15
```
fragment offset, header checksum,total length,flags
```
