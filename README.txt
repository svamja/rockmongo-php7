Introduction
--------------------------------------
RockMongo is a MongoDB administration tool, written in PHP 7, very easy to install and use.

Requirements
------------
1. Apache / nginx with PHP 7
2. Composer
3. PHP MongoDB Driver

Installation
--------------------------------------
1. cd /var/www/
2. git clone https://github.com/svamja/rockmongo-php7 rockmongo
3. cd rockmongo
4. composer install
5. Open MongoDB in http://localhost/rockmongo
6. Login with admin username and password, which is set "admin" and "admin" as default
7. Play with your MongoDBs!


Upgrade from old version
--------------------------------------
1.Copy all files excluding config.php to your old version directory
2.Done!


Contributors
--------------------------------------
iwind.liu <iwind.liu@gmail.com> Leader
leblanc.simon <leblanc.simon@gmail.com> French translation
Klaus Silveira <klaussilveira@gmail.com> Brazilian translation
bmansion <bmansion@mamasam.net> Some small changes
Vladimir Razuvaev <vladimir.razuvaev@gmail.com> Implement features.
Anton Zering <anton.zering@gmail.com> German translation
Borda Juan Ignacio <juanignacioborda@gmail.com> Panels Layout
Diego Baravalle <diegobaravalle@gmail.com> Spanish Translation


Thanks
--------------------------------------
* Many thanks to led24.de for cute icons. 
* Thank Michal Migurski(<mike-json@teczno.com>) for perfect Services_JSON class.
* Thank OFC,  we borrowed json_format() function to make JSON pretty. 
* Thank jQuery, a popular javascript library.
* Thank snipplr.com for mime types mapping.
* Also thank these guys (Marcin, Tyler, Richard, Idan, ...) who spent their time on
  sending feedbacks and advices to me, and let me know i am not alone. 
* Thank Klaus Silveira for Brazilian translation
* Thank leblanc.simon for French translation

Bugs & Issues
--------------------------------------
Please feel free to report any bugs and issues to me, my email is: iwind.liu@gmail.com .


Source Code Repository
--------------------------------------
Repositories are located at 
  https://github.com/iwind/rockmongo.git


Contributing
--------------------------------------
Somebody who want to contribute to the project, may help us by doing these:
* Translate messages from English to other languages (you can see them in app/langs directory)
* Make donations here: http://rockmongo.com/donation
