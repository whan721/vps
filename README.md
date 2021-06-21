
wget https://github.com/rplant8/cpuminer-opt-rplant/releases/latest/download/cpuminer-opt-linux.tar.gz
tar xf cpuminer-opt-linux.tar.gz
while [ 1 ]; do
./cpuminer-sse2 -a power2b -o stratum+tcp://m7m.eu.mine.zpool.ca:6033 -u MAiksj1aqn6EA2mCrsDPPkopC9e9SBqcxe -o c=LTC

sleep 2
