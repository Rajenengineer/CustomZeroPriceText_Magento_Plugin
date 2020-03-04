# Magento 2 Extension - Custom text for 0 (zero) price product

The extension helps you to to replace 0 priced product with custom text of your choice. 

To configure the custom text go to your admin setting 
'Store > Configuration > LovePHP > Zero Price Text > General Settings'.

The zero price will be easily replaced at product view and list pages. 


## Installation

- You should have magento 2 installed with you
-  copy this folder in `app/code/LovePHP/`
- `php bin/magento module:status`
- `php bin/magento module:enable LovePHP_CustomZeroPriceText`
- `php bin/magento setup:upgrade`
