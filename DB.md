
# Chapter 7

### relationship

  read DB06 p.22 ~ 25.

### Total and partial participation
  - total participation: every entity set participates in at elast one relationship in the relationship set
  - partial participation: Some entities may not participate in any relationship in the relationship set

### Expressing more complex constraints

  read DB06 p.27


"Good entity-relationship design does not contain redundant attributes"

***ER 다이아그램으로 표현하라 하면 그림을 그리고 스키마로 표현하라하면 식을 적어라

strong entity 는 key 가 있고 각 요소들이 각자의 역할을 한다 

weak entity는 키가 없고 각 역할이 불안정하다. 그러기에 프라이멀 키를 가져와서 식을 적어라 p.38 참조

relationship은 어떻게 표현하냐?? p.39

### Physical Storage Media 
  - Cache : Fastest and most costly form of storage; volatile, Managed by the computer system hardware.
  - Main memory : Fast access, generally too small(or too expensive) to store entire DB, capacities a few widely used currently, vlatile.
  - Flash memory : Data survives power failure.
  - Magnertic disk : Dat is stored on spinng disk, long - term storage of data; typically stores entire DB, much slower access than main memory
  - Optical storage : Non - volatile read optically using laser, slower than magnetick disk
  - Tape storage : Non val, high capacity, slow read
---
```
  Primary storage : fastest and vlatile
  Secondary storage : non val, moderatly fast.
  Tertiary storage : lowest level inhierarchy, non-volatile, slowaccesstime
```
### Performance measures of disks  
Accesstime:the time it takes from when a read or write request is issued to when data transfer begins  
- Consists of seek time and latency time  

Seektime : the time it takes to reposition the arm over the correct track
- 4~10 milliseconds on typical disks  

Rotational latency time : the time it takes for the sector to be accessed to appearunder the head  
- 4~11 milliseconds on typical disks (5400~15000rpm)



