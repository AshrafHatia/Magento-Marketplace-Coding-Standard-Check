# Magento-Marketplace-Coding-Standard
Steps to check Magento 2 Marketplace Coding Standard 🔥🔥🔥

## 📦


Download Zip Folder from [here](https://github.com/magento/magento-coding-standard )
```python
https://github.com/magento/magento-coding-standard 

extract into your Magento 2 root folder
```
##

Run This command at root (outside of your magento folder)
```bash
composer global require "squizlabs/php_codesniffer=*"
```

## 🚀

open command line 
Go to Magento_Root_Folder/magento-coding-standard
```bash
cd var/www/html/Magento_root_Folder/magento-coding-standard
```

Run 

For Finding Error
```python
vendor/bin/phpcs --standard=Magento2 /var/www/html/magento2/app/code/Vendor
```

For Fixing Errors run this
```python
vendor/bin/phpcbf --standard=Magento2 /var/www/html/magento2/app/code/Vendor

```

⏩ Run Again Finging  Error Command So u can see how many error were Fixed 


## 🛠 Requirements

* PHP >=5.5.0
* [Composer](https://getcomposer.org)
* [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 3.*

> Notice: PHP and Composer should be accessible globally.

> Note : Don't forget to change your php path in composer.json file and if your CLI is not working then use Cygwin command line.

## ☎ Contact

[📧 Mail](mailto:ashraf.magento@gmail.com ) : ashraf.magento@gmail.com 

[https://ashrafhatia.github.io/](https://ashrafhatia.github.io)


## 🔗 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
