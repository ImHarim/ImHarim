
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


### quary processing   
  primay key가 index로 활용된다. 
  Dense index files와 sparse index files. dense는 모든 primary key를 가지고 있어서 search 할때의 시간은 빠르지만 index의 공간을 많이 차지한다
  그러나 sparse index files는 몇몇개의 search key값을 가지고 key보다 큰가 작은가를 비교하면서 서칭을 한다. index의 공간은 적게 먹지만 검색속도는 조금 느리다.

  Multilevel index: primary index가 너무 커스 memory에 들어가지 않을때 접속이 힘들어질 수 있다. 그래서 outer와 inner level로 index를 나눌 수 있는데
  outer의 커다란 level에서 inner의 작은 index의 위치를 알려주는 것이다

  #### Query optimization
  Amongst all equivalent evaluation plans, choose the one lowest cost  
  Query cost means elapsed time for answering a query.  

  Selection Operation  
      
  - File scan: lowest level operator to access data  
  -   
      

   3-way external merge sort  
   
    3 way of input buffer   
    1 way of output buffer
    ex) in real, not (3,1) it might be (3000.1000)

  p.52 블록계산횟수 시험에 나옴!!
  
    
  

