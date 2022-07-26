# PHP-V8
Simple HelloWorld PHP with V8 JavaScript engine extension code

Coding in PHP with V8 engine is equal to coding in C++ with V8 engine in performance.
In other words it is equal to coding in Node.js in performance, However Node.js is bitly faster than PHP. But PHP is more simple to coding.

Run below commands to install required packages and modules:

"sudo apt-get update"

"sudo apt install apache2 php libv8-dev"

"wget https://launchpad.net/~pinepain/+archive/ubuntu/php/+files/libv8-6.6_6.6.313-ppa1~xenial_amd64.deb"

"dpkg -i libv8-6.6_6.6.313-ppa1~xenial_amd64.deb"

"wget https://launchpad.net/~pinepain/+archive/ubuntu/php/+files/php-v8_0.2.2-ppa1~xenial_amd64.deb"

"dpkg -i php-v8_0.2.2-ppa1~xenial_amd64.deb"

"php --ri V8"


Note: PHP-V8 extension is only available for AMD processors. And i followed all of web guides to installing V8 extension for PHP, But all of these were confusing and unsuccessful.

After running last command you will see something like as this that shows V8 extension is installed successfully:

![image1](https://github.com/marzban2030/PHP-V8/raw/main/V8.jpg)

I did this in my VPS with AMD Ryzen 7 3700x 8-core CPU which is located in Germany. 
Finally after rebooting your system put "V8.php" file in your www root folder and navigate your browser to it by typing "http://your_host_ip/V8.php", You'll see something like as this:

![image2](https://github.com/marzban2030/PHP-V8/raw/main/V8_browser.jpg)


php-v8 documentation:
https://php-v8.readthedocs.io/

php-v8 source:
https://github.com/phpv8/php-v8
