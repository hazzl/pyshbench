# pyshbench
A benchmarking tool for the stockfish chess engine implemented in python

##running
`pyshbench` requires three arguments:
  - path to baseline
  - path to testcase
  - number of test runs for each

For example:  
```
$ pyshbench ~/base ~/test 30
~/test 30: 1388520
Result of  30 runs
Base nps:  1389093.28  stdev:  6041.287972690889
Test nps:  1382020.68  stdev:  6682.202674970863
Speed-up:  -0.5118%
p-value:   0.224
```

##To Do
  - run tasks sequentially when there is just one physical core 
