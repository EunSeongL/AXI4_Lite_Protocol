# Day 1

AXI4-Lite

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

별도의 주소 및 데이터 채널을 사용하고 읽기 및 쓰기 채널 그룹 간에 타이밍 관계가 없으므로 인터페이스의 대역폭을 극대화할 수 있습니다. 이는 읽기 시퀀스가 쓰기 시퀀스와 동시에 일어날 수 있음을 의미합니다

CPU, DMA 가 각각 읽기, 쓰기를 시도하는 경우에는 동시에 발생 가능

### AXI_HandShake

![alt text](../img/AXI_HandShake.png)
