# codeception-magento
Automated testing for Magento using Codeception and Phantomjs

# install

- phantomjs  
```
cd /opt
sudo wget https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-1.9.8-linux-x86_64.tar.bz2
sudo tar xjf phantomjs-1.9.8-linux-x86_64.tar.bz2
sudo ln -s /opt/phantomjs-1.9.8-linux-x86_64/bin/phantomjs /usr/local/share/phantomjs
sudo ln -s /opt/phantomjs-1.9.8-linux-x86_64/bin/phantomjs /usr/local/bin/phantomjs
sudo ln -s /opt/phantomjs-1.9.8-linux-x86_64/bin/phantomjs /usr/bin/phantomjs
```

- codeception
```
cd path/to/project OR any/other/directory
wget http://codeception.com/codecept.phar .
php codecept.phar bootstrap
```
