## OSPFv2
router ospf 10
router(-id) <id>
network <red> <máscara invertida> area <area>
passive <interfaz>


## OSPFv3
ipv router ospf <id>
int <int>
router <id>
ipv enable
