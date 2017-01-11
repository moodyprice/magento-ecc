# magento-ecc
A development environment for www.moodyprice.com built on Magento 1.9.x, integrated with Epicor Prophet 21 ERP via ECC API.

## Resource Dependencies
+ Epicor Prophet 21 version XX.xx
+ Epicor Ecommerce Connect API version XX.xx (ECC version should always match Prophet 21 version)
+ Linux Ubuntu/Xenial64 version XX.xx
+ Apache Web Server version XX.xx
+ MySQL Database version XX.xx
+ PHP version XX.xx
+ Magento version 1.9.x
+ Fastest - Fashion Theme version 1.3.5

## Local Environment
Vagrant is built with ScotchBox
```diff
git clone https://github.com/scotch-io/scotch-box.git magento && cd magento
vagrant up
```

