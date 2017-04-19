# composer4php
composer4php &amp; yii2 &amp; ...
http://www.yiiframework.com/


https://github.com/yiisoft/yii2
	The minimum required PHP version of Yii is PHP 5.4.
	It works best with PHP 7.

	yii2-guide.en.pdf	<<<

+++++++++
https://www.sitepoint.com/rendering-data-in-yii-2-with-gridview-and-listview/

--------------
==========================
http://www.yiiframework.com/download/


Install from an Archive File

Download one of the following archive files, and then extract it to a Web-accessible folder:

    Yii 2 with basic application template


http://www.yiiframework.com/doc-2.0/guide-start-installation.html


Installing from an Archive File

Installing Yii from an archive file involves three steps:

    Download the archive file from yiiframework.com.
	yii-basic-app-2.0.11.tgz <<<<<<<<<<<<<<<<

    Unpack the downloaded file to a Web-accessible folder.

    Modify the config/web.php file by entering a secret key for the cookieValidationKey configuration item (this is done automatically if you are installing Yii using Composer):

    // !!! insert a secret key in the following (if it is empty) - this is required by cookie validation
    'cookieValidationKey' => 'enter your secret key here',

http://www.yiiframework.com/doc-2.0/guide-start-installation.html#verifying-installation
Verifying the Installation

After installation is done, either configure your web server (see next section) or use the built-in PHP web server by running the following console command while in the project web directory:
	https://secure.php.net/manual/en/features.commandline.webserver.php

php yii serve

    Note: By default the HTTP-server will listen to port 8080. However if that port is already in use or you wish to serve multiple applications this way, you might want to specify what port to use. Just add the --port argument:

php yii serve --port=8888

You can use your browser to access the installed Yii application with the following URL:

http://localhost:8080/

...

000000000000000000000000000000

L:\TMPL\Yii_2\basic>
php yii serve
Server started on http://localhost:8080/
Document root is "L:\TMPL\Yii_2\basic/web"


http://localhost:8080/
        Congratulations!
    You have successfully created your Yii-powered application.
