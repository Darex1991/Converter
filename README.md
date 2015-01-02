Converter
=========

##CSS into SASS##
**NODE**

*Setup with Ubuntu:* ```curl -sL https://deb.nodesource.com/setup | sudo bash -```

*Then install with Ubuntu:* ```sudo apt-get install -y nodejs```

*Upgrade into new version:* ```sudo npm install npm -g```

*Run server:* ```grunt serve```

##When you have problems##
1. *Don't have Bower? Paste in terminal:* 

  ```npm config set prefix /usr/local``` 
  
  ```npm install -g bower```
2. *No find Grunt? Paste:*
  
  ```npm install -g grunt-cli```

  ```npm install grunt-contrib-compass --save-dev```
3. *No find compass? Install ruby, sass and compass (if you want, you can use rvm). 
[Read about this problem.](http://www.acnenomor.com/410571p1/grunt-task-compass-fails-could-not-find-rubygem-compass-%3E-0)*

  ```gem install sass```
  
  ```gem install compass```
4. *No find haml files:*

  ```npm install grunt-haml```
