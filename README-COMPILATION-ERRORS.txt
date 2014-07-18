For Error on Linux compilation: 
--------------------------------
zerocoin/Accumulator.cpp:106:1: fatal error: opening dependency file obj/zerocoin/Accumulator.d: No such file or directory
compilation terminated.


Use the following command to fix: 
--------------------------------
mkdir -p obj/zerocoin && chmod +x leveldb/build_detect_platform‏


>> Compile again