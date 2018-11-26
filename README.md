# Simple Hello World Module - Extension for Magento 2.x

This is a basic/simple helloworld module in Magento2. It can be a good starting point on developing a module in Magento 2.x.

## Installation

1. The module's files should be placed in folder: `app/code/Chapagain/HelloWorld`
2. Open terminal/command-prompt
3. Go to your Magento website’s root directory with the following command:
    - `cd /path/to/your/magento/root/directory`
4. Enable the module and clear static content with the following command:
    - `php bin/magento module:enable Chapagain_HelloWorld –clear-static-content`
5. Do setup upgrade with the following command:
    - `php bin/magento setup:upgrade`
6. Flush cache with the following command:
    - `php bin/magento cache:flush`
7. That's all. The extension is installed now.
8. You can browse to: http://your-magento-site/helloworld . It will print a "Hello World" message on that page.

## Blog

http://blog.chapagain.com.np/magento-2-create-a-simple-hello-world-module-step-by-step-beginner-tutorial/
