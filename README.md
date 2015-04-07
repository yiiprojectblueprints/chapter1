## Yii Project Blueprints Chapter 1 Source Code

The following source code is the project for Chapter 1 of Yii Project Blueprints
ISBN-CH: 978-1-78328-773-4_01

### A Task Management Application

### Requirements

- PHP 5.3+
- [Yii's Requiremnts](https://github.com/yiisoft/yii/blob/master/requirements/index.php)
- A Webserver

### Installation

1. Have a web capable server (Apache, Nginx). See [here](http://www.yiiframework.com/doc/guide/1.1/en/quickstart.installation) and [here](http://www.yiiframework.com/doc/guide/1.1/en/quickstart.apache-nginx-config) for how to do that.

[DigitalOcean](https://www.digitalocean.com/community/articles/how-to-install-and-setup-yii-php-framework) has a pretty comprehensive guide for setting up things if you aren't familiar with the process.

2. Download/Clone this project to your web directory, and setup your server so that it can be accessed.

3. Open up a Terminal window to the current working directory.

4. Make sure the following directories are writable by your webserver process

	- protected/runtime
	- assets/
	- protected/data/

5. Install the database

```
php protected/yiic.php migrate up
```

Once the database has been installed you can use the application.

### License for Source Code

The MIT License (MIT)

Copyright (c) 2014 Charles R. Portwood II

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.