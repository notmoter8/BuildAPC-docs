BuildAPC-docs
=============
## How to build on Linux

## NOTE: This doesn't currently work. I'll investigate why soon`tm`

We use Ubuntu's apt-get package manager in this how-to.
Swap out apt-get with yum if you are using Fedora. 

-

We install some dependencies to be able to build the html files and preview them in our browser.

(as root/sudo)

`apt-get update && apt-get install python-pip python-sphinx gem git npm make`

`pip install sphinx_rtd_theme`

`npm install -g bower grunt-cli`

`npm install`

-

(As User w/o sudo privileges)

git clone https://github.com/moter8/buildapc-docs.git

-
[![AGPLv3](https://gnu.org/graphics/agplv3-155x51.png)](https://gnu.org/licenses/agpl.html)
Licensed under the [AGPLv3 License](https://gnu.org/licenses/agpl.html).

Originally distributed on https://moter8.pw/
