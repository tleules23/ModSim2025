Plan:

General: Make runs with max_time = 800 because I will change variability of thinking / eating times

- Look at if the statistics change with a higher number of philoophers (f.e. 10)

- Introduce variability: 
    - at first, just thinking time:  2 - 30 mins unformly distributed
    - then also eating time: 1 - 10 min uniformly distributed

- Selfish philosophers:
    - ignores timeout and still holds chopsticks
    - ignores priority ordering -> just takes left or right chopstick first randomly
    - does not drop chopsticks directly after eating
    - maybe is hungry again after eating once (NO) 
    - maybe does not care about starvation queue ? (NO)
    - maybe interrupts neighbor if he is hungry and neighbor is using chopstick (NO)

- conspiracy:
    - some philosophers just always hold at least one chopstick to prevent neighbors from eating
    - they just drop one chopstick at a time, so never both at the same time 

- DO NOT FORGET TO ADJUST TIMEOUT DURATION!!