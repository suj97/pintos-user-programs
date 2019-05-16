# pintos-user-programs
Implementing user programs in PintOS

## Prerequisites 
QEMU emulator.
- Can be installed on Ubuntu by simply running `sudo apt-get install qemu`

## Installation
1. `cd ~`
2. `git clone https://github.com/suj97/pintos-user-programs.git`
3. `cd pintos-user-programs/pintos/src/utils`
4. `make`
5. `cd ../threads`
6. `make`
7. `./pintos run alarm-multiple`

If you'd like to clone the repository in a different directory then do remember to change `line 4 in src/utils/pintos-gdb`, `line 257 in src/utils/pintos`, `line 362 in src/utils/Pintos.pm` accordingly.

The following will open a Qemu terminal window and run the alarm-multiple test. You can just close the Qemu terminal when the test execution completes.
