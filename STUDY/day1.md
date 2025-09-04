# Day 1

![alt text](../img/AXI_protocol.png)
AXI Interconnect component - IP 사용


### AXI_Protocol
📝 AXI 프로토콜은 **버스(bus) 사양이 아니라 점대점(point-to-point)** 따라서 인터페이스 간의 신호와 타이밍만을 기술.

모든 연결은 상호연결을 통해 1:1로 연결

### AXI_Channel
![alt text](../img/AXI_Channel.png)

```
AW for signals on the Write Address channel
AR for signals on the Read Address channel
W for signals on the Write Data channel
R for signals on the Read Data channel
B for signals on the Write Response channel
```

