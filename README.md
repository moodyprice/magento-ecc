# magento-ecc
A development environment for www.moodyprice.com built on Magento 1.9.3.1, integrated with Epicor Prophet 21 ERP via ECC API.

## Resource Dependencies
+ Epicor Prophet 21 version 12.16.2314
+ Epicor Ecommerce Connect API version 12.16.2314 (implied - ECC version should always match Prophet 21 version)
+ Linux Ubuntu/Xenial64 version 14.04
+ Apache Web Server version 2.4
+ MySQL Database version 5.6
+ PHP version 5.6
+ Magento version 1.9.2.4 (Updated by @epicor-gabriel 1/12/17)
+ Fastest - Fashion Theme version 1.3.5

## Local Environment
Vagrant is built with ScotchBox (last pulled 1-10-16)
```diff
git clone https://github.com/scotch-io/scotch-box.git magento && cd magento
vagrant up
```

