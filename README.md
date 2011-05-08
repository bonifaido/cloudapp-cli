cloudapp-cli
============

In development, please do not use.

A simple cli for [CloudApp][getcloudapp] written in Ruby.

Install
-------

cloudapp-cli depends on Aaron Russell's [cloudapp_api][api], so first install it as a gem dependency:

	sudo gem install cloudapp_api

Then install it with the one-liner (please make sure that your /usr/local/bin is writeable):

	curl https://github.com/bonifaido/cloudapp-cli/raw/master/cloudapp -o /usr/local/bin/cloudapp && chmod +x /usr/local/bin/cloudapp

Usage
-----

Configuration:

	cloudapp config myemail@company.com mypassword

List all your drops:

	cloudapp list

Upload a file:

	cloudapp upload drumandbass.ogg

Upload a file as private:

	cloudapp upload -p topsecret.pdf


Enjoy!

[getcloudapp]:http://getcloudapp.com/
[api]:https://github.com/aaronrussell/cloudapp_api