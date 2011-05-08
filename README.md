cloudapp-cli
============

A simple cli for [CloudApp][getcloudapp] written in Ruby.

Install
-------

cloudapp-cli depends on the [cloudapp_api][api], so first install it as a gem dependency:

	sudo gem install cloudapp_api

Install with the one-liner (shock!) (make sure that your /usr/local/bin is writable and is in PATH):

	cd /usr/local/bin && curl -fOs https://github.com/bonifaido/cloudapp-cli/raw/master/cloudapp && chmod +x cloudapp && cd -

Usage
-----

Configuration:

	cloudapp config myemail@company.hu passw0rd

List all your drops:

	cloudapp list

Show your stats:

	cloudapp stats

Upload a file:

	cloudapp upload drumandbass.ogg

Upload a file as private:

	cloudapp upload -p topsecret.pdf

Download a drop to current directory:

	cloudapp download dZ69

Change a drop to private:

	cloudapp private dZ69

Change all drops to public:

	cloudapp public

Rename a drop:

	cloudapp rename dZ69 UserGuide.txt

Delete a drop:

	cloudapp delete dZ69

Recover a drop:

	cloudapp recover dZ69

Enjoy!
------

[getcloudapp]:http://getcloudapp.com/
[api]:https://github.com/aaronrussell/cloudapp_api