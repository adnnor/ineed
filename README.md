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
$ sudo ineed --platform="magento" --version="2.3.6"
$ sudo ineed --platform="magento" --version="2.3.6" --configure-only
$ sudo ineed --platform="magento" --version="2.3.6" --install-only
```

#### Limitations

* Its BETA version, be careful ;)
* Only supports Magento, Laravel is on its way.
* Nginx support is coming soon.
* SMTP, XDebug, Redis, RabbitMQ, Git and n98-magerun2 support will be introduced in next versions.
* Works on Ubuntu only (tested on bionic and focal versions).
* Separate instance for sample data installation will be introduced in next version.
* AWS service integrations will be introduced in coming versions.

> **DISCALIMER:** This is made available for ease, therefore, not recommended for the production. I will not be responsible for any damage or lose of data under local nor under production environment ;)

Please contribute by sharing your ideas and/or report any bug you may encounter.