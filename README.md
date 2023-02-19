Cloud and Security Focused. Heavily involved in automation. Focused primarily on busines improvement and optimisation. 

I hate Cisco. This is a terrible interface view.
```
!
interface FastEthernet0/14
 switchport access vlan 197
 switchport voice vlan  198
 switchport priority extend cos 1
 srr-queue bandwidth share 1 30 35 5
 priority-queue out
 mls qos trust cos
 auto qos trust
 spanning-tree portfast
!
```

That is all.
