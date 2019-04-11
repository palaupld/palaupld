

# PLD - The Most Powerful Infrastructure for Decentralized Applications

Welcome to the Palau PLD source code repository! This software enables businesses to rapidly build and deploy high-performance and high-security blockchain-based applications.

Some of the groundbreaking features of PLD include:

1. Free Rate Limited Transactions
1. Low Latency Block confirmation (0.5 seconds)
1. Low-overhead Byzantine Fault Tolerant Finality
1. Designed for optional high-overhead, low-latency BFT finality
1. Smart contract platform powered by WebAssembly
1. Designed for Sparse Header Light Client Validation
1. Scheduled Recurring Transactions
1. Time Delay Security
1. Hierarchical Role Based Permissions
1. Support for Biometric Hardware Secured Keys (e.g. Apple Secure Enclave)
1. Designed for Parallel Execution of Context Free Validation Logic
1. Designed for Inter Blockchain Communication

PLD is released under the open source MIT license and is offered “AS IS” without warranty of any kind, express or implied. Any security provided by the PLD software depends in part on how it is used, configured, and deployed. PLD is built upon many third-party libraries such as WABT (Apache License) and WAVM (BSD 3-clause) which are also provided “AS IS” without warranty of any kind. Without limiting the generality of the foregoing, Block.one makes no representation or guarantee that PLD or any third-party libraries will perform as intended or will be free of errors, bugs or faulty code. Both may fail in large or small ways that could completely or partially limit functionality or compromise computer systems. If you use or implement PLD, you do so at your own risk. In no event will Block.one be liable to any party for any damages whatsoever, even if it had been advised of the possibility of damage.  

Block.one is neither launching nor operating any initial public blockchains based upon the PLD software. This release refers only to version 1.0 of our open source software. We caution those who wish to use blockchains built on PLD to carefully vet the companies and organizations launching blockchains based on PLD before disclosing any private keys to their derivative software.

There is no public testnet running currently.

**If you have previously installed PLD, please run the `PLD_uninstall` script (it is in the directory where you cloned PLD) before downloading and using the binary releases.**

#### Mac OS X Brew Install
```sh
$ brew tap PLD/PLD
$ brew install PLD
```
#### Mac OS X Brew Uninstall
```sh
$ brew remove PLD
```
#### Ubuntu 18.04 Debian Package Install
```sh
$ wget https://github.com/PLD/eos/releases/download/v1.7.1/PLD_1.7.1-1-ubuntu-18.04_amd64.deb
$ sudo apt install ./PLD_1.7.1-1-ubuntu-18.04_amd64.deb
```
#### Ubuntu 16.04 Debian Package Install
```sh
$ wget https://github.com/PLD/eos/releases/download/v1.7.1/PLD_1.7.1-1-ubuntu-16.04_amd64.deb
$ sudo apt install ./PLD_1.7.1-1-ubuntu-16.04_amd64.deb
```
#### Debian Package Uninstall
```sh
$ sudo apt remove PLD
```
#### Centos RPM Package Install
```sh
$ wget https://github.com/PLD/eos/releases/download/v1.7.1/PLD-1.7.1-1.el7.x86_64.rpm
$ sudo yum install ./PLD-1.7.1-1.el7.x86_64.rpm
```
#### Centos RPM Package Uninstall
```sh
$ sudo yum remove PLD.cdt
```
#### Fedora RPM Package Install
```sh
$ wget https://github.com/PLD/eos/releases/download/v1.7.1/PLD-1.7.1-1.fc27.x86_64.rpm
$ sudo yum install ./PLD-1.7.1-1.fc27.x86_64.rpm
```
#### Fedora RPM Package Uninstall
```sh
$ sudo yum remove PLD.cdt
```

## Supported Operating Systems
PLD currently supports the following operating systems:  
1. Amazon 2017.09 and higher
2. Centos 7
3. Fedora 25 and higher (Fedora 27 recommended)
4. Mint 18
5. Ubuntu 16.04
6. Ubuntu 18.04
7. MacOS Darwin 10.12 and higher (MacOS 10.14.x recommended)

## Important

See LICENSE for copyright and license terms.  Block.one makes its contribution on a voluntary basis as a member of the PLD community and is not responsible for ensuring the overall performance of the software or any related applications.  We make no representation, warranty, guarantee or undertaking in respect of the software or any related documentation, whether expressed or implied, including but not limited to the warranties or merchantability, fitness for a particular purpose and noninfringement. In no event shall we be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or documentation or the use or other dealings in the software or documentation.  Any test results or performance figures are indicative and will not reflect performance under all conditions.  Any reference to any third party or third-party product, service or other resource is not an endorsement or recommendation by Block.one.  We are not responsible, and disclaim any and all responsibility and liability, for your use of or reliance on any of these resources. Third-party resources may be updated, changed or terminated at any time, so the information here may be out of date or inaccurate.
