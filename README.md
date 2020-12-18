## ineed 

It helps you to configure and set up your required platform.

#### Installation
```bash
$ wget https://raw.githubusercontent.com/adnnor/ineed/master/ineed.sh
$ chmod +x ./ineed.sh
$ sudo mv ineed.sh /usr/local/bin/ineed
```

#### Usage
```bash
$ sudo ineed magento 2.3.6
```

#### Limitations

* Three digit version is required, right now no validation is implemented will fixed be in next version.
* Only supports Magento, Laravel is on its way.
* Nginx support is coming soon.
* Magento 2.4, the elasticsearch will be configured, but you have to put the details under `env.php` manually, next version will fix this. 
* SMTP, XDebug, Redis, RabbitMQ, Git and n98-magerun2 support will be introduced in next versions.
* Its BETA version, be careful ;)
* Works on Ubuntu only (tested on bionic and focal versions).
* Separate instance for sample data installation will be introduced in next version.
* More parameters will be introduced so you can;
    * Select whether you want to set up Magento or only want to set up the environment.
    * Option to set up the RabitMQ as cluster or not.
    
* AWS service integrations will be introduced in coming versions.

> **DISCALIMER:** This is made available for ease, therefore, not recommended for the production. I will not be responsible for any damage or lose of data under local nor under production environment ;)

Please contribute by sharing your ideas and/or report any bug you may encounter.