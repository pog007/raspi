# xmrig

Basic build

Basic build is good for local machine, because it is easy, but if you need to run the miner on other machines please take a look at advanced build.

1. sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
2. git clone https://github.com/xmrig/xmrig.git
3. nano xmrig/src/donate.h
4. constexpr const int kDefaultDonateLevel = 0;
5. constexpr const int kMinimumDonateLevel = 0;
6. mkdir xmrig/build && cd xmrig/build
7. cmake ..
8. make -j$(nproc)

