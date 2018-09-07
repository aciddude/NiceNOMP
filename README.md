### Welcome to the cryptopool.builders github! 
### This fork of NOMP is designed to work with our Ultimate Crypto-Server Installer program. 
Trying to install this on a server not built by our installer will cause headaches, frustrations, and screaming loudly at your monitor. 

## Helping give NOMP new life! With some style.
#### If you want to help contribute, please look at the original [project](https://github.com/foxer666/node-open-mining-portal) first!

This is all the things great about NOMP, now with modern style and design of BootStrap 4! Having disliked the previous UI, due to cramping, little to no info displayed while what is displayed is not very helpful to users. I decided to fork a already great project, and add some stylistic touches it severely needs. I would of considered requesting pulls to the main branch, though with such heavy changes to the project, I decided a hard fork would be well suited. But if you would like to contribute, please consider looking at the [original project](https://github.com/foxer666/node-open-mining-portal) first, as these guys are the ones who helped get this NOMP rebirthing process started.

-------
### Node Open Mining Portal consists from 3 main modules:
* [NOMP](https://github.com/cryptosharks131/node-open-mining-portal)
* [Stratum Pool](https://github.com/cryptosharks131/node-stratum-pool)
* [Node Multihashing](https://github.com/cryptosharks131/node-multi-hashing)

_Stratum Pool can be replaced with [node-merged-pool](https://github.com/UNOMP/node-merged-pool)._<br>
_Add new algorithms using [Node Multihashing](https://github.com/cryptosharks131/node-multi-hashing)._

Current version: v1.1.3

-------
### Install
```
git clone https://github.com/cryptopool-builders/NiceNOMP.git pool
cd pool
npm install
node init.js
```
-------
### Requirements
* Node 8.x.x or higher
* Coin daemon
* Redis Server

-------
### Hashing algorithms
#### Working
|   | Algorithm | Comment|
| ------------- | ------------- | ------------- |
| ✓ | __C11__ | tested shares and payments with Dixicoin |
| ✓ | __Groestl__ | tested only shares with AuroraCoin, blocks not tested |
| ✓ | __lyra2rev2__ | shares work, needs tests with payments. currently being tested with Lunex coin |
| ✓ | __lyra2z__ | Working in testnet *mining* and *payouts* |
| ✓ | __NeoScrypt__ | working now thanks to @foxer666 pushing update to parent repo |
| ✓ | __Qubit__ | Shares works, and blocks should now too. |
| ✓ | __Scrypt__ | tested with AntiLiteCoin, 1CREDIT, ArgusCoin, WAYAWOLFCOIN and many others |
| ✓ | __SHA256__ | tested with VCOIN, don't use with BTC, no Segwit tested |
| ✓ | __X11__ | tested with BrainCoin, CannabisCoin, AdzCoin and many others |
| ✓ | __X16r__ | tested with RavenCoin |
| ✓ | __Yescrypt__ | needs tests, though should work |
| ✓ | __YescryptR16__ | needs tests, though should work |
| ✓ | __YescryptR32__ | currently being tested with WaviCoin. shares work, payments unconfirmed |

#### Need tests
|   | Algorithm | Comment|
| ------------- | ------------- | ------------- |
| ? | __Argon2__ | need tests |
| ? | __Blake__ | need tests |
| ? | __Blake2S__ | need tests |
| ? | __Cryptonight__ | need tests |
| ? | __Dcrypt__ | need tests |
| ? | __Decred__ | need tests |
| ? | __Fresh__ | need tests |
| ? | __Fugue__ | need tests |
| ? | __GroestlMyriad__ | need tests |
| ? | __Quark__ | need tests |
| ? | __Hefty1__ | need tests |
| ? | __Keccak__ | need tests |
| ? | __Lbry__ | need tests |
| ? | __lyra2re__ | need tests |
| ? | __lyra2re2__ | need tests |
| ? | __lyra2z330__ | need tests |
| ? | __NIST5__ | need tests |
| ? | __S3__ | need tests |
| ? | __Scrypt-N__ | need tests |
| ? | __Scrypt-OG__ | need tests |
| ? | __Sha1__ | need tests |
| ? | __SHAvite-3__ | need tests |
| ? | __Skein__ | need tests |
| ? | __X11Ghost__ | need tests |
| ? | __X13__ | need tests |
| ? | __X14__ | need tests |
| ? | __X15__ | need tests |
| ? | __zr5__ | need tests |
| ? | __ziftr__ | need tests |

#### Don't work yet
|   | Algorithm | Comment|
| ------------- | ------------- | ------------- |
| - | __Scrypt-Jane__ | submitblock not working tested with CacheCoin, Yacoin |

-------

-------
### Credits
* [1301313Y](//github.com/1301313Y) - Upgraded the UI and stat modules
* [a2hill](//github.com/a2hill) - helped with X16r
* [devnulled](//github.com/devnull-ed) - helped with lyra2z, neoscrypt algo
* [Kris Klosterman / krisklosterman](https://github.com/krisklosterman) - Updated code for work wiht Node.JS >=8
* [Jerry Brady / mintyfresh68](https://github.com/bluecircle) - got coin-switching fully working and developed proxy-per-algo feature
* [Tony Dobbs](http://anthonydobbs.com) - designs for front-end and created the NOMP logo
* [LucasJones](//github.com/LucasJones) - got p2p block notify working and implemented additional hashing algos
* [vekexasia](//github.com/vekexasia) - co-developer & great tester
* [TheSeven](//github.com/TheSeven) - answering an absurd amount of my questions and being a very helpful gentleman
* [UdjinM6](//github.com/UdjinM6) - helped implement fee withdrawal in payment processing
* [Alex Petrov / sysmanalex](https://github.com/sysmanalex) - contributed the pure C block notify script
* [svirusxxx](//github.com/svirusxxx) - sponsored development of MPOS mode
* [icecube45](//github.com/icecube45) - helping out with the repo wiki
* [Fcases](//github.com/Fcases) - ordered me a pizza <3
* [yoshuki43](//github.com/yoshuki43) - his K-Nomp project has really help the development!
* Those that contributed to [node-stratum-pool](//github.com/zone117x/node-stratum-pool#credits)

-------
### License
Released under the GNU General Public License v2
http://www.gnu.org/licenses/gpl-2.0.html


### Donations


BTC: `1FJvtLBszQgY2eKBawov48RwSYy2yqEvn1`

ETH: `0x39acE9917e25E2A04643d30319cF34449A72441B`

LTC: `LR1Mmchr6Zz1vj51xecTiEdS1WHfJTVg5t`
