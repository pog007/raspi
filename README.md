# xmrig

Basic build

Basic build is good for local machine, because it is easy, but if you need to run the miner on other machines please take a look at advanced build.

1. sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
2. git clone https://github.com/xmrig/xmrig.git
3. mkdir xmrig/build && cd xmrig/build
4. cmake ..
5. make -j$(nproc)

---------
xmrig/src/donate.h
 - constexpr const int kDefaultDonateLevel = 0;
 - constexpr const int kMinimumDonateLevel = 0;
