# RhetraWallet
Lightweight wallet for Rhetra

## Build instructions
1. Install Visual Studio Community 2017 with C++ and Windows SDK.
2. Setup Git for Windows.
2. Download 32 or 64 bit dependency archive and unpack it either to C:\MyProjects32\ or C:\MyProjects\ respectively.
3. Run qmake_env_static.cmd and use opened command prompt for the next actions.
3. Clone this repository:
    git clone http://github.com/dtampu/RhetraWallet
4. Run the following commands:
```
    cd RhetraWallet
    mkdir build
    cd build && qmake ..
    nmake
```    
5. You're done

