knockd-one-time-sequences-generator
===================================

Use this shell script to generate knockd one-time-sequences file

This script works with rl command for random number generation.

$ apt-get install randomize-lines

usage:

$ ./knockd-one-time-sequences-generator  -h
-h: this help
-l|--lines: how many lines to generate
-nu|--no-udp: turn off udp
-b|--port-max: the maximum port range
-s|--port-min: the minimum port range


just run without parameter to use default setting

$ ./knockd-one-time-sequences-generator  
 1,55956,63051:udp
 2,26814:udp,33941:udp,13157:udp,35731,61827:udp,61048:udp
 3,52658:udp,12884:udp
 4,7196,3371:udp
 5,46285:udp,59583:udp,53577,2770:udp
 6,7414:udp,64633,41811
 7,25486,26595
 8,30193,53658:udp,19398:udp,16365,38701
 9,65077:udp,9838
 10,13790,17368:udp,58729:udp,36772
