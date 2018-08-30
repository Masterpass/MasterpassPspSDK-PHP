# Read Me

PHP Masterpass PSP(Payment Service Provider) SDK for use with PHP Core SDK on MasterCard Developer Zone (https://developer.mastercard.com) 

PSP SDK is used by Payment Service Provider to get payment data.

Pre-Requisites for using PHP Masterpass PSP SDK :

 *  PHP 5.5 or Higher
 *  Download MasterCardCoreSDK.phar from https://github.com/Masterpass/MasterCardCoreSDK-PHP
 *  Download MastercardPspPayment.phar for using Masterpass PSP SDK, github url: https://github.com/Masterpass/MasterpassPspSDK-PHP
 
##### Note: Refer to mastercard developer zone for documentation on SDKs for implementation reference and avoid potential break in your existing code if you upgrade with higher version.
 
 These phar can be downloaded from github directly or by using composer dependency.
 
 If you do not have composer installed you can download it from https://getcomposer.org/
 
 To download the phar as composer dependency, put a file named composer.json at the root of your project, containing as your project dependencies:
 ```
 {
  "require": {
  "masterpass/masterpasspspsdk":"1.3.0"
   }
 }
```

In order to import above package in your application, you need to use following composer command after installing composer locally:

> composer install or composer update

You can get more information about integrating Masterpass PSP(Payment Service Provider) SDK from MasterCard Developer Zone - 
##### Merchant Integration section. 